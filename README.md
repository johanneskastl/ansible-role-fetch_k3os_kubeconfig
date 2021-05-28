fetch_k3os_kubeconfig
=========

Fetch the kubeconfig file from a host running Rancher's k3os

**Attention**
 This role works, but uses a rather hacky solution, as there is no python installed and no way to install it.
See [this Github issue](https://github.com/rancher/k3os/issues/296) for details and discussion.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.fetch_k3os_kubeconfig' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
