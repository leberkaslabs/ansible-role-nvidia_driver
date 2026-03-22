# Ansible Role: nvidia_driver

[![Ansible Molecule](https://github.com/leberkaslabs/ansible-role-nvidia_driver/actions/workflows/molecule.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-nvidia_driver/actions/workflows/molecule.yml)

Install the NVIDIA driver.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: leberkaslabs.nvidia_driver
```

## License

Copyright (c) 2026 Niclas Spreng
