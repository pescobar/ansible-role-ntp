ntp
=========

[![Build Status](https://travis-ci.org/robertdebock/ansible-role-ntp.svg?branch=master)](https://travis-ci.org/robertdebock/ansible-role-ntp)

Provides ntp for your system.

Requirements
------------

A Linux system. ;-)

Role Variables
--------------

None known.

Dependencies
------------

You can prepare your system using the role:

- robertdebock.bootstrap

Download the dependencies by issuing this command:
```
ansible-galaxy install --role-file requirements.yml
```

Example Playbook
----------------

```
- hosts: servers

  roles:
    - role: robertdebock.bootstrap
    - role: robertdebock.ntp
```

Install this role using `galaxy install robertdebock.tomcat`.

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
