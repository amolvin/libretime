# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.network "forwarded_port", guest: 8888, host:8888

  config.vm.provision "shell", path: "docs/scripts/install.sh"
  config.vm.provision "shell", path: "docs/scripts/serve.sh"

end