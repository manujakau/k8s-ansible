# k8s-ansible

```
$ vagrant up
$ vagrant ssh
$ sudo su
$ lxd init
```
use default values to complete lxd init except Name of the storage backend to use (btrfs, dir, lvm, zfs, ceph)  . use dir .

To run lxd container:

```
$ lxc launch images:ubuntu/focal/amd64
$ lxc list
$ lxc exec <Name of the Container from lxc list> bash
```