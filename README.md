# Ansible Role: mcelog

An Ansible role that setup mcelogd

## Example Playbook
```sh
---
 - hosts: common
   roles:
        - { role: mcelog, when: ansible_distribution == 'CentOS' and  BareMetal == True }
```
## Requirements

None.

## Dependencies

None.

## License

BSD

