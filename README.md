kemumaki-box-rhel7
==================

Kemumaki build environment provides rpmbuild and vmimage file build.

General
-------

+ [OS](vmbuilder.conf#L5-L6)
  + CentOS-7.0.1406 x86_64
+ Disk
  + [rootfs: 40 GB](vmbuilder.conf.d/disk.conf#L1)
  + [swap: 1 GB](vmbuilder.conf.d/disk.conf#L2)

Accounts
--------

| username | password |
|:---------|:---------|
| root     | (locked) |
| kemumaki | kemumaki |

Current Boxes
-------------

KVM Guests:

+ minimal-7.0.1406-x86_64.kvm.box

OpenVZ Container(s):

+ ...

Linux Container(s):

+ ...

Build Environment
-----------------

Links
-----

+ [buidbook-rhel7](https://github.com/hansode/buildbook-rhel7)
+ [vmbuider](https://github.com/hansode/vmbuilder)
