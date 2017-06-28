rbenv-install-dep-ubuntu
==========================

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-rbenv-install-dep-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-rbenv-install-dep-ubuntu)

Install rbenv install dependencies on Ubuntu.

https://github.com/rbenv/ruby-build/wiki#suggested-build-environment

> # This role is deprecated
>
> From the version 2.0.0, [suzuki-shunsuke.rbenv](https://galaxy.ansible.com/suzuki-shunsuke/rbenv/) supports to install build dependencies.

Requirements
------------

Nothing.

Role Variables
--------------

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.rbenv-install-dep-ubuntu
```

License
-------

MIT
