# Packer Example

## VirtualBox
  - Works fine:


##VMware
  - Dont work

```
$ packer validate centos71.json
$ packer build centos71.json

#Next:

$ vagrant box add 'centos-7.1-x86_64' './centos-7.1-x86_64.box'
$ vagrant init 'centos-7.1-x86_64'
$ vagrant up
$ vagrant ssh

```
