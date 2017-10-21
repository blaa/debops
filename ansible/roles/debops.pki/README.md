## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) pki

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-pki.svg?style=flat)](https://travis-ci.org/debops/ansible-pki)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--pki-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-pki/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.pki-660198.svg?style=flat)](https://galaxy.ansible.com/debops/pki)


The `debops.pki` role provides a standardized management of the X.509
certificates on hosts controlled by Ansible. Other Ansible roles can utilize
the environment created by `debops.pki` to automatically enable TLS/SSL
encrypted connections.

Using this role, you can bootstrap a Public Key Infrastructure in your
environment using an internal Certificate Authority, easily switch the active
set of certificates between internal and external Certificate Authorities, or
use the ACME protocol to automatically obtain certificates from CA that
support it (currently, [Let's Encrypt][lets-encrypt]).

[lets-encrypt]: https://letsencrypt.org/

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.pki
```

### Documentation

More information about `debops.pki` can be found in the
[official debops.pki documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-pki/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) | [e-mail](mailto:ypid@riseup.net) | [Twitter](https://twitter.com/ypid) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).