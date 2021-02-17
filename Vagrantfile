Vagrant.configure("2") do |config|
    # VM 1 Centos
    config.vm.box = "bento/centos-8.3"
    config.vm.define "web-server"
    config.vm.hostname = "server1"
    # VM 1 Centos
    config.vm.network "public_network", bridge: "Microsoft Wi-Fi Direct Virtual Adapter #2", ip: "192.168.137.111"
    config.vm.provider "virtualbox" do |vb|
      vb.gui = true
      # VM 1 Centos
      vb.name = "web-server"
   #   # Customize the amount of memory on the VM:
      vb.memory = "2048"
    end
  end