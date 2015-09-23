resolv
========

This roles enables users to configure the /etc/resolv.conf.

Requirements
------------

None.

Role Variables
--------------

```yaml
resolv_domain: ''

resolv_search: []

# loopback as a default
resolv_ns:
  - 127.0.0.1

  resolv_sortlist: []
  resolv_options: []
```

Dependencies
------------

None

License
-------

BSD

Author Information
------------------

Peter Hudec
