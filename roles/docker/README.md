Docker install on Debian & Ubuntu
=================================

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - docker

License
-------

BSD

Author Information
------------------

Roman Adereyko

WARNING!!!
==========

Role checked for working ONLY ON DEBIAN!!!
Check it on Ubuntu systems with '--check' key!
Example:

    ansible-playbook {playbook_dir}/docker.playbook --check
