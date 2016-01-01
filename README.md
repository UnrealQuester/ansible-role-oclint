# Ansible Role: Oclint
[![Build Status](https://travis-ci.org/UnrealQuester/ansible-role-oclint.svg?branch=master)](https://travis-ci.org/UnrealQuester/ansible-role-oclint)

Installs [oclint](https://github.com/oclint/oclint) on Ubuntu/Debian systems.

# Requirements

Debian: Jessie or newer

Ubuntu: Trusty or newer

# Install

```ansible-galaxy install UnrealQuester.oclint```

# Example Playbook

```ansible
- hosts: dev-server
  roles:
    - UnrealQuester.oclint
```

# License
MIT
