# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  
  config.vm.define :puppetmaster do |puppetmaster|
    puppetmaster.vm.box = "fingerpuppeteering32"

    puppetmaster.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
    puppetmaster.vm.provision :shell, :inline => "printf \"127.0.0.1 localhost ip6-loopback \nfe00::0 ip6-localnet \nff00::0 ip6-mcastprefix \nff02::1 ip6-allnodes \nff02::2 ip6-allrouters \nff02::3 ip6-allhosts \n127.0.1.1 puppet\n\" > /etc/hosts && printf \"puppet\" > /etc/hostname"
  end

  config.vm.define :web do |web|
    web.vm.box = "fingerpuppeteering32"

    web.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
    web.vm.provision :shell, :inline => "printf \"127.0.0.1 localhost ip6-loopback \nfe00::0 ip6-localnet \nff00::0 ip6-mcastprefix \nff02::1 ip6-allnodes \nff02::2 ip6-allrouters \nff02::3 ip6-allhosts \n127.0.1.1 web\n\" > /etc/hosts && printf \"web\" > /etc/hostname"

  end

  config.vm.define :database do |database|
    database.vm.box = "fingerpuppeteering32"

    database.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
    database.vm.provision :shell, :inline => "printf \"127.0.0.1 localhost ip6-loopback \nfe00::0 ip6-localnet \nff00::0 ip6-mcastprefix \nff02::1 ip6-allnodes \nff02::2 ip6-allrouters \nff02::3 ip6-allhosts \n127.0.1.1 database\n\" > /etc/hosts && printf \"database\" > /etc/hostname"

  end

  config.vm.define :logging do |logging|
    logging.vm.box = "fingerpuppeteering32"

    logging.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/precise/current/precise-server-cloudimg-i386-vagrant-disk1.box"
    logging.vm.provision :shell, :inline => "printf \"127.0.0.1 localhost ip6-loopback \nfe00::0 ip6-localnet \nff00::0 ip6-mcastprefix \nff02::1 ip6-allnodes \nff02::2 ip6-allrouters \nff02::3 ip6-allhosts \n127.0.1.1 logging\n\" > /etc/hosts && printf \"logging\" > /etc/hostname"
  end


end
