# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  (1..6).each do |i|
    config.vm.define "server#{i}" do |node|
      node.vm.box = "centos/7"
      node.vm.hostname = "server#{i}"
      node.vm.network :private_network, ip: "10.42.0.10#{i}"
      #config.ssh.port= "220#{i}"
      node.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
      end
    end
  end
end
