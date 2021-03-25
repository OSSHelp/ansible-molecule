# molecule

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/molecule/status.svg)](https://drone.osshelp.ru/ansible/molecule)

This role installs [Molecule](https://github.com/ansible/molecule) via PIP.

## Usage (example)

```yaml
    - role: molecule
```

## Available parameters

### Main

| Param | Default | Description |
| -------- | -------- | -------- |
| `minimal_version` | `2.22` | Minimal molecule version to install |
| `paramiko_version` | `2.5.0` | Minimal paramiko version to install |

## FAQ

None, so far.

## Useful links

- [Official documentation for Molecule](https://molecule.readthedocs.io/en/latest/)
- [Ansible role for Ansible](https://github.com/OSSHelp/ansible-ansible)
- [Drone CI plugin with Molecule](https://hub.docker.com/r/osshelp/drone-molecule)

## TODO

None, so far.

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
