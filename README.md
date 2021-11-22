# ansible-provi_nutanix_ahv

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-provi_nutanix_ahv-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/provi_nutanix_ahv)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-provi_nutanix_ahv.svg)](https://github.com/lotusnoir/ansible-provi_nutanix_ahv/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-provi_nutanix_ahv?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/57044)](https://galaxy.ansible.com/lotusnoir/provi_nutanix_ahv)
![Ansible Quality Score](https://img.shields.io/ansible/quality/57044)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Create a vm on Nutanix AHV hypervisors

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: provi_nutanix_ahv
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-provi_nutanix_ahv


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

