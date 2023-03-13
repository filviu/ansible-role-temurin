# Ansible Role: Adoptium Temurin

[![CI](https://github.com/filviu/ansible-role-temurin/workflows/CI/badge.svg?event=push)](https://github.com/filviu/ansible-role-temurin/actions?query=workflow%3ACI)

Sets up Adoptium Temuirin JDK using native OS package management tools.

## Role Variables

See `defaults/main.yml`:

    temurin_jdk_version: 17


## Dependencies

None.

## Example Playbook

```yaml
---
- hosts: all

  roles:
    - role: filviu.temurin
      temurin_jdk_version: 11
```

## License

MIT / BSD


## Author Information

This role was created by Silviu Vulcan to scratch his own itch.
