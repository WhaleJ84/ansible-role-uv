uv
=========

Installs and configures uv.

Requirements
------------

This role has no requirements.

To include this role in your `requirements.yml` file, add the following list item:

```yaml
---
roles:
  - name: whalej84.uv
    src: https://github.com/whalej84/ansible-role-uv.git
    scm: git
```

The role can then be installed using `ansible-galaxy install -r requirements.yml whalej84.uv`.

Role Variables
--------------

See [defaults](./defaults/main.yml).

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

This exmaple playbook shows how I would use this role, with custom variables to suit my needs:

```yaml
---
- hosts: localhost

  roles:
    - role: whalej84.uv
      tags: [ uv ]
```
