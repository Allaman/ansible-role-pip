# ansible-role-pip

Install packages via python's pip as user.

## Test

Run `molecule test` to test this role in a docker container

## Requirements

- Arch Linux or Ubuntu based OS
- Sudo permissions (for dependencies)

## Role Variables

- NA

## Dependencies

ansible-role-basic

## Example Playbook

```
---
- name: Playbook
  hosts: localhost
  connection: local
  roles:
    - ansible-role-pip
```

## License

MIT
