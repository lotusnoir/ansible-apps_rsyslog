# ansible-apps_rsyslog

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_rsyslog-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_rsyslog)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_rsyslog.svg)](https://github.com/lotusnoir/ansible-apps_rsyslog/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_rsyslog?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56793)](https://galaxy.ansible.com/lotusnoir/apps_rsyslog)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56793)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure rsyslog log forwarder

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_rsyslog
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-apps_rsyslog


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

