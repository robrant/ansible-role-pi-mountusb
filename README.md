

# About

Ansible role to mount an external USB disk on a raspberry Pi.

# Usage

Drop into your own playbook using something similar to:

    - hosts: pis
      roles:
        - mount_external_usb
      tags: usb

# Works On

Tested on Raspbian Jessie.
