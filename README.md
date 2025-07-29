role-rke2-init-cp-node
=========

Initializes RKE2 Control Plane Node:
- renders configuration template
- starts systemd `rke2-server.service`


Requirements
------------

- RKE2 control plane components are install on the node but not initialized


Role Variables
--------------

- see [defaults](defaults/main.yml)
- see [vars](vars/Linux.yml)


Dependencies
------------

- None

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: role-rke2-init-cp-node
```


License
-------

BSD

Author Information
------------------

https://vlads.tech
