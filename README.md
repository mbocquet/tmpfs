# tmpfs

Ansible role to configure tmpfs filesystems.

## Requirements

None.

## Role Variables

Many. See defaults/main.yml

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/tmpfs.git roles/tmpfs`

## Example Playbook

    - hosts: servers
      roles:
         - tmpfs


    - hosts: servers
      roles:
         - { role: tmpfs, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
