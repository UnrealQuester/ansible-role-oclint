# Ansible Role: Oclint
[![Build Status](https://travis-ci.org/UnrealQuester/ansible-role-oclint.svg?branch=master)](https://travis-ci.org/UnrealQuester/ansible-role-oclint)

Installs [oclint](https://github.com/oclint/oclint) on Ubuntu/Debian systems.

# Requirements

Debian: Jessie or newer

Ubuntu: Trusty or newer

# Role Variables

Available variables aling with their default values:
```
oclint_install_dir: "/usr"
```
The directory where oclint will be installed. Because of the way
oclint searches for its library files, the binaries are copied to
`{{ oclint_install_dir }}/bin` and the libraries are copied to
`{{ oclint_install_dir }}/lib`.


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
