psp-ports
============

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-psp-ports.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-psp-ports)

This role installs and configures the open-source [psp-ports](https://github.com/pspdev/psp-ports) for PSP homebrew development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.psp-ports
```

```
# psp-ports.yml
- hosts: localhost
  roles:
    - nabilbendafi.psp-ports
```

```
$ ansible-playbook psp-ports.yml
```

Dependencies
------------

[nabilbendafi.psptoolchain](https://github.com/nabilbendafi/ansible-role-psptoolchain)

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
