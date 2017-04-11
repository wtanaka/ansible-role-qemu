[![Build Status](https://travis-ci.org/wtanaka/ansible-role-qemu.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-qemu)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-qemu.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-qemu)

wtanaka.qemu
============

This ansible role installs Qemu

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.qemu

### `qemu_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "qemu" is already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
