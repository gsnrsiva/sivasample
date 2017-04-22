# Two Machines
Vagrant.configure("2") do |config|
 config.vm.define "aishu" do |aishu|
  		aishu.vm.box = "ubuntu/trusty64"
  		aishu.vm.hostname = "aishu"
  		aishu.vm.network "private_network", ip: "192.168.33.10"
  #		aishu.gui = true
  	end
	
 config.vm.define "nag" do |nag|
  		nag.vm.box = "ubuntu/trusty64"
  		nag.vm.hostname = "nag"
  		nag.vm.network "private_network", ip: "192.168.33.20"
  #		nag.gui = true
  	end
end