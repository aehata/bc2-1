# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provider "virtualbox" do |vb|
    #vb.memory = "1024"
    vb.memory = "2048"
    #vb.memory = "4096"
  end
  config.vm.synced_folder "./bc2", "/bc2"
  config.vm.provision "shell", path: "provision.sh"
end
