andrewrothstein.dotnet-runtime
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-dotnet-runtime.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-dotnet-runtime)

Installs the .Net Core Runtime

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.dotnet-runtime
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
