Kafka @ Hortonworks Data Platform
=================================

An Ansible Role that installs Kafka from the Hortonworks Data Platform.  

Add to your playbooks requirements.yml:

```
- src: https://github.com/nickwallen/ansible-hdp-kafka
```

and then run:

```
ansible-galaxy install -r requirements.yml --ignore-errors
```

Requirements
------------

None.

Role Variables
--------------


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: kafka*
      roles:
         - { role: ansible-hdp-kafka, x: 42 }

License
-------

BSD

Author Information
------------------

Nick Allen
