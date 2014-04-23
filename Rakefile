
#############################################################
# http://jasonseifer.com/2010/04/06/rake-tutorial

directory "tmp"
 
file "tmp/hello.tmp" => "tmp" do
  sh "echo 'Hello' >> 'tmp/hello.tmp'"
end

#############################################################

namespace :stujo do
  desc "Say Hello"
  task :say_hello do
    puts 'Hello'
  end
end
