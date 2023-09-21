# Ansible provisioner (inside the VM) for Vagrant on Windows 10

## Requirements

* Ruby SDK
  * Download and install: https://rubyinstaller.org/downloads/
  * Run: c:\Ruby32-x64\bin\ridk.cmd enable
* Vagrant

## Setup

* Run: `rake build`
* Run: `vagrant plugin install pkg\vagrant-guest_ansible-0.0.4.gem`