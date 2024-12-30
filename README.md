Nodejs
======

Install Node.js and NPM

Requirements
------------

Debian Bullseye / Bookworm or Ubuntu Precise/Trusty/Xenial.

Role Variables
--------------

Specify the version of Node.js you want:

    nodejs_version: 6.x

See https://github.com/nodesource/distributions

Example Playbook
-------------------------

    - hosts: servers
      roles:
        - { role: f500.nodejs }

Linting
-------
Github actions will check this role with ansible-lint. To run this locally, you will need to follow the following steps:

```bash
brew install ansible-lint
brew install yamllint
ansible-lint
```

to fix the linting errors, run:

```bash
ansible-lint --fix
```

License
-------

LGPL-3.0

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
