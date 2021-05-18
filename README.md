Ansible Role: redis(pkg)
================================================================================
Install and configure Redis

- Install redis using yum at CentOS 7
- Configure /etc/redis.conf

Requirements
--------------------------------------------------------------------------------

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in defaults/main.yml file.

```yaml
redis:
  enabled: true
  started: true
  ...
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-redis-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

