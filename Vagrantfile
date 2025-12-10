Vagrant.configure("2") do |config|

  config.vm.define "ns" do |ns|
    ns.vm.box = "debian/bullseye64"
    ns.vm.hostname = "ns"
    ns.vm.network "private_network", ip: "192.168.56.101"
    
    ns.vm.provider "virtualbox" do |vb|
      vb.memory = "512"
      vb.name = "ns-nicolas"
    end
  end
end