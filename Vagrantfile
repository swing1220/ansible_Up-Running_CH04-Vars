# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "ubuntu" do |ubuntu|
    ubuntu.vm.box = "ubuntu/bionic64"
    ubuntu.vm.network "private_network", ip: "192.168.4.10"
  end

  config.vm.define "centos" do |centos|
    centos.vm.box = "centos/7"
    centos.vm.network "private_network", ip: "192.168.4.11"
  end

  config.vm.define "precise" do |precise|
    precise.vm.box = "precise64"
    precise.vm.network "private_network", ip: "192.168.4.12"
  end
end
