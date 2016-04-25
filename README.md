bvansomeren.docker
=========

Installs and starts Docker inside CentOS 7
Can deliver both the CentOS included version of Docker or the upstream variant

Requirements
------------

This role installs all required packages for Docker

Role Variables
--------------

There is just one switch to chose the version:

	docker_userepo: True

Setting this to false uses the platform supplied version (Note: It does not currently uninstall docker when changing)

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bvansomeren.docker }

License
-------

BSD

Author Information
------------------

