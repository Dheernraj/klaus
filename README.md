#vagrant is a tool for building & managing virtual Machine environment
#vagrant init bento/ubuntu-18.04
#vagrant up
- hosts: servers
  roles:
     - { role: username.rolename, x: 42 }
