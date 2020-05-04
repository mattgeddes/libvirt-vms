libvirt-vms
===========

Deploys VMs from a template under KVM using libvirt

Requirements
------------

Requires that KVM is installed and configured (libvirt-kvm role) and that there
is a template repository with VM template files (cloud-image role for example).

Role Variables
--------------

my\_vms: []

Dependencies
------------

* mattgeddes.libvirt\_kvm

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache-2.0

