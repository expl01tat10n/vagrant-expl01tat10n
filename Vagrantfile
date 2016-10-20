# -*- mode: ruby -*-
# vi: set ft=ruby :

# Setup Vagrant variables
Vagrant.configure("2") do |config|
  # config.vm.box = "tknerr/baseimage-ubuntu-16.04"
  # config.vm.hostname = "docker-kit"
  config.vm.provider "docker" do |docker|
    docker.vagrant_vagrantfile = "Vagrantfile"
    docker.image = "tknerr/baseimage-ubuntu-16.04"
    docker.ports = ['80:80', '443:443']
    docker.name = 'expl01t-container'
  end
end