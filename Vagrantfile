Vagrant.configure("2") do |config|
  config.vm.box = "vatman/xenial64"
  config.vm.provision :shell, :path => "hello.py", :privileged => false
end

