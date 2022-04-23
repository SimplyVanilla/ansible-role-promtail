# ansible-role-promtail

[![CircleCI](https://circleci.com/gh/SimplyVanilla/ansible-role-promtail/tree/main.svg?style=svg)](https://circleci.com/gh/SimplyVanilla/ansible-role-promtail/tree/main)

Ansible role to install [promtail](https://grafana.com/docs/loki/latest/clients/promtail/) on Debian-like systems.

## Role Variables

```
promtail_version: '2.5.0'
```

## Dependencies

_none_

## Example Playbook

```
- hosts: servers
  roles:
    - src: simplyvanilla.promtail
```

## License

[GPLv3](LICENSE)
