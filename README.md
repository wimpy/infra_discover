# Wimpy Infra Discover[![Build Status](https://travis-ci.org/wimpy/wimpy.infra_discover.svg?branch=master)](https://travis-ci.org/wimpy/wimpy.infra_discover)
Ansible role to search for VPC, subnets and security groups tagged with specific tag, so they can be used for [wimpy.deploy](https://github.com/wimpy/wimpy.deploy).

## Usage

```yaml
- hosts: localhost
  connection: local
  roles:
    - wimpy.infra_discover

```

