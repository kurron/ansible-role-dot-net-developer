Role Name
=========

Installation of tools than any self-respecting cross-platform .NET developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

TODO

Dependencies
------------

* kurron.jdk

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.dot-net-developer, rider_version: 2016.2.1, rider_install: true }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
