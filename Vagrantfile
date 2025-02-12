Vagrant.configure("2") do |config|
  config.vm.box = "debian/bookworm64"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.network "private_network", ip: "192.168.33.10"
end

## sudo apt update
## sudo apt upgrade
## sudo apt install npm
## sudo apt install node

