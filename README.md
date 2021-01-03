toni.wg-client
===========

Ansible role to install wireguard clients. Only useable with server role.

Requirements
------------

Roles:
  - toni.wg-server

Role Variables
--------------

```bash
wg_interface: wg0 
wg_dir: "/etc/wireguard" # configuration dir
wg_server_ip: "10.8.0.1"
nfs_mount_dir: "/mnt/shared"
```

License
-------

MIT

Author Information
------------------

T.Nissen