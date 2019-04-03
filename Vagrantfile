Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vm.define "machine1" do |node1|
    node1.vm.network "private_network", ip: "192.168.0.101"
    node1.vm.hostname = "machine1"
    node1.vm.provider "virtualbox" do |v|
     v.memory = 1024
     v.cpus = 1
   end
  end
  config.vm.define "machine2" do |node2|
    node2.vm.network "private_network", ip: "192.168.0.102"
    node2.vm.hostname = "machine2"
    node2.vm.provider "virtualbox" do |v|
     v.memory = 1024
     v.cpus = 1
   end
  end
 end
