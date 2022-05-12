# ansible.ServerConfig
This is designed to setup my servers from scratch

## Instructions
1. start with 
    `ansible-playbook --ask-become-pass bootstrap.yml`
2. then run
    `ansible-playbook Main.yml`


## Notes:
- htop - htop configs work on without a restart of ubuntu 22.04 - File not found.
  - fatal: [deskPlay]: FAILED! => {"changed": false, "checksum": "b1760a252146383d954b52e14be5c828e70734f2", "msg": "Destination directory /home/colin/.config/htop does not exist"}
  - 