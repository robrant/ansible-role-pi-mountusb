

# About

Ansible role to mount an external USB disk on a raspberry Pi.

# Dependencies

I'm assuming you're interested in this role because you want to access external
storage on your Raspberry Pi. So, you'll need an external storage USB device
and it'll need to be plugged into your Pi.

# Usage

Drop into your own playbook using something similar to:

    - hosts: pis
      roles:
        - mount_external_usb
      tags: usb

# Works On

Tested on Raspbian Jessie on the Raspberry Pi B+.

# Todo?

1. Does this definitely automount the device/partition on reboot? Ansible docs
seem to suggest it should do, but I think i've observed it not working.
