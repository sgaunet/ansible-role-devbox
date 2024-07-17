# Ansible Role: devbox

[![CI](https://github.com/sgaunet/ansible-role-devbox/workflows/CI/badge.svg)](https://github.com/sgaunet/ansible-role-devbox/actions?query=workflow%3ACI)

An Ansible Role that installs [devbox][https://github.com/jetify-com/devbox] on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    devbox_version: "latest"
    devbox_bin_path: "/usr/local/bin"
    devbox_os: "linux"
    devbox_arch: "amd64"

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - sgaunet.devbox
```

## License

MIT
