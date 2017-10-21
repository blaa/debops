## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) gitlab

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-gitlab.svg?style=flat)](https://travis-ci.org/debops/ansible-gitlab)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--gitlab-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-gitlab/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.gitlab-660198.svg?style=flat)](https://galaxy.ansible.com/debops/gitlab)


This role installs [GitLab](https://about.gitlab.com/), an Open Source
GitHub clone.  `debops.gitlab` role will also automatically update
installed GitLab instance if new patches are pushed to the repository.

You can also use this role to upgrade an already installed GitLab instance
to new version when support for it becomes available (new GitLab version is
released on 22nd of each month, usually `debops.gitlab` role is updated
to support new version shortly after that).

### Installation

This role requires at least Ansible `v2.1.0`. To install it, run:

```Shell
ansible-galaxy install debops.gitlab
```

### Documentation

More information about `debops.gitlab` can be found in the
[official debops.gitlab documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-gitlab/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).