Ansible Role: Shadowsocks
=========================

Install [Shadowsocks](https://github.com/shadowsocks) via Ansible.

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements are listed in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows.

```yaml
shadowsocks_dependencies:
  - python-setuptools
  - m2crypto

shadowsocks_home: "/etc/shadowsocks"
```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
     - { role: sparanoid.shadowsocks, shadowsocks_home: /etc/shadowsocks }
```

License
-------

GPLv3

Author Information
------------------

**Tunghsiao Liu**

- Twitter: @[tunghsiao](http://twitter.com/tunghsiao)
- GitHub: @[sparanoid](http://github.com/sparanoid)
