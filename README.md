# Unifi-Controller Ansible role

This role installs Unifi-Controller via Docker compose.

## Requirements

None

## Role Variables

All variables are listed below (see also `defaults/main.yml`).

```yml
---
```

## Dependencies

You need a machine with docker and docker-compose installed.

## Example Playbook

```yml
- hosts: servers
  roles:
      - 'laurivan.unifi-controller'
```

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license - see the [LICENSE](LICENSE) file for details.

![MIT License](https://img.shields.io/badge/license-MIT%20License-brightgreen)

## Author Information

This role was created in 2023 by [Laur Ivan](https://www.laurivan.com).

## Built With

![Ansible](https://img.shields.io/badge/ansible-5.2.0-green.svg)
![Molecule](https://img.shields.io/badge/molecule-3.4.0-green.svg)
![Goss](https://img.shields.io/badge/goss-0.3.16-green.svg)

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
