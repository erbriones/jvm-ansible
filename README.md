jvm-ansible
=========

[![Build Status](https://travis-ci.org/erbriones/jvm-ansible.svg?branch=master)](https://travis-ci.org/erbriones/jvm-ansible)

An opinionated installation and configuration of the jvm. The role follows the
latest stable release of java.

Role Variables
--------------

The `JAVA_HOME` path can be set using `default_path`. This creates a symbolic
link to the `default_path` and sets the environment variable.

Use the `headless` flag to toggle between development or headless packages.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - { role: erbriones.jvm-ansible, default_path: /usr/lib/jvm/jdk-latest, headless: false }
```

LICENSE
-------

MIT License, see the [LICENSE](https://github.com/erbriones/jvm.ansible/blob/master/LICENSE) file.
