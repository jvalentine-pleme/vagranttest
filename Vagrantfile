# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.provision "shell", inline: "echo Configuring"
  
  config.vm.define "web" do |web|
    web.vm.box = "ubuntu/trusty64"
  end
  
  config.vm.define "middleware" do |middleware|
    middleware.vm.box = "ubuntu/trusty64"
  end
  
end
