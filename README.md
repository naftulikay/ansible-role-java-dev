# ansible-role-java-dev [![Build Status][travis.svg]][travis]

Installs and configures a Java development environment.

Available on Ansible Galaxy at [`naftulikay.java-dev`][galaxy].

## Requirements

Officially tested operating systems are listed in the Galaxy manifest.

## Role Variables

Please see `defaults/main.yml` for a list of supported variables.

## Dependencies

None.

## Example Playbook

Here are some example playbooks to get started with.

### Defaults

Simply get a Java development environment installed:

```yaml
---
- name: install
  hosts: all
  become: true
  roles:
    - role: java-dev
```

## License

MIT

 [travis]: https://travis-ci.org/naftulikay/ansible-role-java-dev
 [travis.svg]: https://travis-ci.org/naftulikay/ansible-role-java-dev.svg?branch=master
 [galaxy]: https://galaxy.ansible.com/naftulikay/java-dev/
