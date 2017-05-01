Grafana
=========

> Setup grafana

Requirements
------------

Need ansible 2

Role Variables
--------------

```yaml
grafana_packages_update_cache: no
```

Dependencies
------------

There is no dependency

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: SimpliField.grafana }
```

License
-------

BSD
