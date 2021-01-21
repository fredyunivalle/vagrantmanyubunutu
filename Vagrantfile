# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define "web_1" do |web_1|
      web_1.vm.box = "ubuntu/xenial64"
      web_1.vm.provision "shell", path: "script.sh"
      web_1.vm.provision  "docker"
      web_1.vm.network "forwarded_port", guest: 80, host: 8009
      web_1.vm.synced_folder "C:/zonework/maquinas/vagrantso/www1/", "/var/www/html/"
  end
  config.vm.define "web_2" do |web_2|
      web_2.vm.box = "ubuntu/xenial64"
      web_2.vm.provision  "docker"
      web_2.vm.provision "shell", path: "script.sh"
      web_2.vm.network "forwarded_port", guest: 80, host: 8008
      web_2.vm.synced_folder "C:/zonework/maquinas/vagrantso/www2/", "/var/www/html/"
  end
  config.vm.define "web_3" do |web_3|
    web_3.vm.box = "ubuntu/xenial64"
    web_3.vm.provision "shell", path: "script.sh"
    web_3.vm.provision  "docker"
    web_3.vm.network "forwarded_port", guest: 80, host: 8010
    web_3.vm.synced_folder "C:/zonework/maquinas/vagrantso/www2/", "/var/www/html/"
  end
  config.vm.define "web_4" do |web_4|
    web_4.vm.box = "ubuntu/xenial64"
    web_4.vm.provision  "docker"
    web_4.vm.provision "shell", path: "script.sh"
    web_4.vm.network "forwarded_port", guest: 80, host: 8011
    web_4.vm.synced_folder "C:/zonework/maquinas/vagrantso/www2/", "/var/www/html/"
  end
  config.vm.define "web_5" do |web_5|
    web_5.vm.box = "ubuntu/xenial64"
    web_5.vm.provision  "docker"
    web_5.vm.provision "shell", path: "script.sh"
    web_5.vm.network "forwarded_port", guest: 80, host: 8012
    web_5.vm.synced_folder "C:/zonework/maquinas/vagrantso/www2/", "/var/www/html/"
  end
  config.vm.define "web_6" do |web_6|
    web_6.vm.box = "ubuntu/xenial64"
    web_6.vm.provision  "docker"
    web_6.vm.provision "shell", path: "script.sh"
    web_6.vm.network "forwarded_port", guest: 80, host: 8013
    web_6.vm.synced_folder "C:/zonework/maquinas/vagrantso/www2/", "/var/www/html/"
  end
end