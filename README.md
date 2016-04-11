jvm.ansible
=========

[![Build Status](https://travis-ci.org/erbriones/jvm.ansible.svg?branch=master)](https://travis-ci.org/erbriones/jvm.ansible)

An opinionated installation and configuration of the jdk. The role follows the
latest stable release of java.

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
