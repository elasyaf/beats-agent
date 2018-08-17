Role Name
=========

ansible role for installing beats agent ELK stack (include: metricbeat, auditbeat, packetbeat, filebeat) for Debian / Ubuntu based

Requirements
------------

None

Role Variables
--------------
```

elasticsearch_hosts: ""
kibana_hosts: ""

```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```

    - name: Start ansible beats
      hosts: beats
      roles:
        - { role: beats-agent}

      vars:
        - elasticsearch_hosts: "your elasticsearch IP address / host address"
        - kibana_hosts: "your elasticsearch IP address / host address"

```

License
-------

BSD

Author Information
------------------

This role was created in 2018 by elasyaf
