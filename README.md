[![Molecule Converge](https://github.com/aorfanos/server-utils-config/actions/workflows/test.yml/badge.svg)](https://github.com/aorfanos/ansible-users/actions/workflows/test.yml)
# Ansible Collection - aorfanos.server_utils


Configure users and groups, server unit testing, logging and others.

Requirements
------------

None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

`server_config.yml`:
```yaml
    - hosts: servers
      roles:
         - { role: aorfanos.server_utils.users }
         - { role: aorfanos.server_utils.promtail }
         - { role: aorfanos.server_utils.logrotate }
```

Usage:

```shell
ansible-playbook -i inventory users.yml
```

"""
```

License
-------

BSD
