# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.provision "shell"
  
  config.vm.define "web" do |web|
    web.vm.box = "web"
  end
  
  config.vm.define "middleware" do |middleware|
    middleware.vm.box = "middleware"
  end
  
end
