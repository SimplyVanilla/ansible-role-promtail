# ansible-role-promtail

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
