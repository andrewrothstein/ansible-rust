andrewrothstein.rust
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-rust.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-rust)

Installs [Rust](https://www.rust-lang.org) with rustup

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
    - andrewrothstein.rust
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
