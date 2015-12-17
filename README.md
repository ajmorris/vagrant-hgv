# Vagrant HGV

This Vagrantfile and ansible playbook provisions a simple WordPress LEMP stack environment.

The ansible playbook was pulled from https://github.com/zach-adams/hgv-deploy-full.

## Requirements

Virtual Box - https://www.virtualbox.org/wiki/Downloads
Homebrew - http://brew.sh/
Vagrant - https://www.vagrantup.com/
Ansible - http://www.ansible.com/

## Install

1) Install Vagrant and Homebrew first.

2) Install Ansible with `brew install ansible`

## Starting up

1) Clone the repo locally and `cd` into the directory.

2) Run `vagrant up` and this will create the install for you!

Happy coding!

## License

This is GPL. Feel free to use it, do pretty much whatever you want with it, as long as you follow GPL. The license is included in gpl.txt.

The ansible playbook was developed by Zach Adams as a test. It will be getting some updates over time, but it was his great start that gave me an idea to start with that as the starting point for this project.
