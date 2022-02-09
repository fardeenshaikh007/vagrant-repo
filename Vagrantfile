Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.define "m1" do |m1|
     m1.vm.hostname  = "firstserver"
	 m1.vm.network "private_network", ip: "172.32.0.11"
	 m1.vm.provider "virtualbox" do |vb|
	   vb.name = "firstserver"
	 end
  end
  
  config.vm.define "m2" do |m2|
     m2.vm.hostname  = "secondserver"
	 m2.vm.network "private_network", ip: "172.32.0.12"
	 m2.vm.provider "virtualbox" do |vb|
	   vb.name = "secondserver"
	 end
  end
  config.vm.define "m3" do |m3|
     m3.vm.hostname  = "thirdserver"
	 m3.vm.network "private_network", ip: "172.32.0.12"
	 m3.vm.provider "virtualbox" do |vb|
	   vb.name = "thirdserverserver"
	 end
  end  
 end

