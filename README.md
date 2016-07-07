Filesystem
==========
Create local filesystems.

# Required variables (no defaults):
#   part: partition/disk for the volume group
#   vg: volume group suffix
#   lv: logical volume name
#   size: logical volume size
#   type: filesystem type
#   mount: point point
#   dump: dump frequency (see fstab)
#   passno: passno (see fstab)

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
See `defaults/main.yml`.

Dependencies
------------
None.

Example Playbook
----------------
Example:
```
- hosts: servers
  roles:
  - role: filesystems
```

TODO
----

Licence
-------
Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Author Information
------------------
Luis Gracia <luis.gracia@ebi.ac.uk>
