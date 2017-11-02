[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-ruby)

# lifeofguenter.ruby

An Ansible role that installs ruby (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
ruby_version: 2.3.5
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: ruby
  roles:
    - { role: lifeofguenter.ruby }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[Gunter Grodotzki](https://lifeofguenter.de)
