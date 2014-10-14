# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.box_url = "https://vagrantcloud.com/ubuntu/boxes/trusty64"
  config.vm.network :private_network, ip:"192.168.33.77"

  config.vm.provider "virtualbox" do |v|
      v.name = "ansible_name"
  end
end
