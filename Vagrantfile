# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "stromweld/windows-11"
  config.vm.boot_timeout = 768
  config.vm.provider "virtualbox" do |vb|
    vb.customize ['modifyvm', :id, '--clipboard', 'bidirectional']    
  end
  config.vm.provider "vmware_fusion" do |vm|
    vm.gui = true
  end
end
