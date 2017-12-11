Vagrant and Ansible Basic Example
=================================

This repository contains the basics for developing a Flask application
within a Vagrant VM, using Ansible for provisioning.

See the accompanying blog post on the PyCharm blog to read more about
developing within a VM.

Usage
-----

To start developing, you need:

- [Vagrant](https://vagrantup.com)
- Virtualization software compatible with Vagrant, like 
  [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
  
Check out this repository on your computer, and then run `vagrant up`
to start and provision the VM.

On provisioning, a virtualenv will be created in `/home/vagrant/venv`
with the packages listed in `requirements.txt`.
