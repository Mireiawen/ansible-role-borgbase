![Build Status](https://img.shields.io/gitlab/pipeline-status/mireiawenrose/ansible-roles/borgbase?branch=master&style=plastic) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.borgbase-blueviolet?style=plastic)](https://galaxy.ansible.com/mireiawen/borgbase)

# Borg
Installs [BorgBackup](https://borgbackup.readthedocs.io/), [Borgmatic](https://torsion.org/borgmatic/) and optionally configures the repository at [BorgBase](https://www.borgbase.com/).

The repository creation is not part of the testing and it may or may not work.

## Requirements
- [adhawkins.borgbase](https://galaxy.ansible.com/adhawkins/borgbase)

## Role Variables
see the `defaults/main.yml`

## Dependencies
None.

## Example Playbook
```yaml
- hosts: "servers"
  roles:
  - role: "mireiawen.borgbase"
```

## License
MIT, see `LICENSE`
