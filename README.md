HAproxy installer
=========

Installs [HAproxy](http://www.haproxy.org/).

Requirements
------------

Ubuntu 20.04
Debian 10

Role Variables
--------------

`haproxy_version` -- desired HAproxy version

Example Playbook
----------------

```
- name: Setting up HAproxy
  hosts: all
  remote_user: root
  roles:
    - haproxy_installer
  vars:
    haproxy_version: 2.2
```

License
-------

BSD

