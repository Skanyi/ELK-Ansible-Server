Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = "elk-server"
  # config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.network "private_network", ip: "192.168.33.13"

end
