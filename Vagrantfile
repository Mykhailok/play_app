Vagrant.configure(2) do |config|
config.vm.define "jenkins" do |jenkins|
jenkins.vm.box = "ubuntu/trusty64"
jenkins.vm.network "public_network", ip: "192.168.1.252"
jenkins.vm.hostname = "jenkins"
jenkins.vm.provider "virtualbox" do |v|
v.memory = 4096
v.cpus = 2
end
end
end