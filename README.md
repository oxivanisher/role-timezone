timezone
========
[![Ansible Lint](https://github.com/oxivanisher/role-timezone/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-timezone/actions/workflows/ansible-lint.yml)

Configure the system timezone.

Role Variables
--------------

| Name              | Comment                               | Default value                   |
|-------------------|---------------------------------------|---------------------------------|
| timezone_timezone | Which timezone should be configured.  | `Europe/Zurich` |

Example Playbook
----------------
```yaml
- name: Configure timezone
  hosts: all
  collections:
    - oxivanisher.linux_base
  roles:
    - role: oxivanisher.linux_base.timezone
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
