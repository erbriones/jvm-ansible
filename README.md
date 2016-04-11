jvm.ansible
=========

An opinionated installation and configuration of the jdk. The package
follows the latest stable release of the jdk.

Role Variables
--------------
The default java path can be set using `default_jdk_path`.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - { role: erbriones.jvm.ansible default_path: /usr/lib/jvm/jdk-latest
```

LICENSE
-------

See LICENSE
