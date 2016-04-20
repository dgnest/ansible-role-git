# Ansible Role Git

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-git.svg)](https://travis-ci.org/hadenlabs/ansible-role-git)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-git.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-git)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-git.svg)](https://github.com/hadenlabs/ansible-role-git/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [git][link-git] on a host.

## Requirements

This role requires Ansible 1.9 or higher.

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for git


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: all
      roles:
         - hadenlabs.git

To install a specific version:

    - hosts: all
      roles:
         - { role: hadenlabs.git }

## License

MIT

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Author Information

- [Luis Mayta][link-luis]

## Credits

- [All Contributors][link-contributors]


<!-- Other -->

[link-git]: https://www.git-scm.com
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
