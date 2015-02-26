mapr_license
=========

Apply a license to a MapR cluster.

Requirements
------------

You should have a license string or file available, and a cluster up and running.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

    - hosts: cluster
      run_once: yes
      roles:
         - { role: mapr_license, license: '' }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
