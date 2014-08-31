Ansible Role - Ntp
==================

A ntp role for elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    ntp restart  # Restart ntp service


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.ntp }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
