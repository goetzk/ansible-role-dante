# Ansible Role: Dante (SOCKS Proxy Server)

An Ansible role that installs Dante from source or packages on Debian flavoured systems

https://www.inet.no/dante/doc/1.4.x/config/server.html

## Requirements

None

## Role Variables

Available variables are listed below, along with default values:

    dante_version: 1.4.1
    dante_working_dir: /tmp
    dante_source_install: False

## Dependencies

None

## Example Playbook

    - hosts: socks
      roles:
        - { role: lifeofguenter.dante }

## License

MIT

