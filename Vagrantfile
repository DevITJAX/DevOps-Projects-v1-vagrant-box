
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.provider :virtualbox do |v|

   v.memory  = 4096

   v.cpus    = 2

   v.customize ["modifyvm", :id, "--vram", "128"]

end

end
