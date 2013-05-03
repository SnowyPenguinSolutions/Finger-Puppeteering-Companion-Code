# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  
  config.vm.define :puppetmaster do |puppetmaster|
    puppetmaster.vm.box = "fingerpuppeteering32"

    puppetmaster.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
  end

  config.vm.define :web do |web|
    web.vm.box = "fingerpuppeteering32"

    web.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
  end

  config.vm.define :database do |db|
    db.vm.box = "fingerpuppeteering32"

    db.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
  end

  config.vm.define :logging do |logging|
    logging.vm.box = "fingerpuppeteering32"

    logging.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
  end


end
