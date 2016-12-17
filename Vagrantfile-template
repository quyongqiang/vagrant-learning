# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

  config.vm.box = "hashicorp/precise64"
  # config.vm.provision :shell, path: "bootstrap.sh"
  # config.vm.network :forwarded_port, guest: 80, host: 4567
  config.vm.network "public_network", ip: "192.168.0.11"

  config.vm.provider "virtualbox" do |vb|
    # Display the VirtualBox GUI when booting the machine
    #vb.gui = true

    # Customize the amount of memory on the VM:
    vb.memory = "1024"
  end

end
