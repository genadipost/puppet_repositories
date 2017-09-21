puppet_repositories
=========

Configure Puppet yum repository.</br>
The role was copied from the [theforeman/forklift project](https://github.com/theforeman/forklift/tree/master/roles/puppet_repositories).

Requirements
------------

Role Variables
--------------

| Name    | Description    | Required    | Default    | Values | Examples |
|:--|:--|:-:|:-:|:-:|:--|
| puppet_repositories_version | puppet version | No | 4 | - | 5 |

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: genadipost.puppet_repositories }

License
-------

BSD

Author Information
------------------

genadipost@gmail.com
