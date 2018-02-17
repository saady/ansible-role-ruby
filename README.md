[![Build Status](https://travis-ci.org/NINEJKH/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/NINEJKH/ansible-role-ruby)

# NINEJKH.ruby

An Ansible role that installs ruby (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
ruby_version: 2.3.6
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: ruby
  roles:
    - { role: NINEJKH.ruby }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[9JKH (Pty) Ltd.](https://9jkh.co.za)
