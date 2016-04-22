jvm.ansible
=========

[![Build Status](https://travis-ci.org/erbriones/jvm.ansible.svg?branch=master)](https://travis-ci.org/erbriones/jvm.ansible)

An opinionated installation and configuration of the jvm. The role follows the
latest stable release of java.

Role Variables
--------------
The default java path can be set using `default_path`.

Use the `headless` flag to toggle between development or headless packages.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - { role: erbriones.jvm.ansible, default_path: /usr/lib/jvm/jdk-latest, headless: false }
```

LICENSE
-------

See [LICENSE](https://github.com/erbriones/jvm.ansible/blob/master/LICENSE)
