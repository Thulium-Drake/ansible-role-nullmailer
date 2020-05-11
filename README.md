[![Build Status](https://drone.element-networks.nl/api/badges/jeff/ansible-role-nullmailer/status.svg)](https://drone.element-networks.nl/jeff/ansible-role-nullmailer)

# Nullmailer
This role will setup a nullmailer, a lightweight MTA for Linux.

# Requirements
Nullmailer is a send-only MTA, it does not host mailboxes. In order to use this
role, you still need a mailserver somewhere.

As a safeguard, you can disable this role from accidentally ruining a mailserver
by setting nullmailer_do_not_configure.
