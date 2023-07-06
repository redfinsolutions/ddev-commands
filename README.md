[![tests](https://github.com/ddev/drupal-rfs-custom-commands/actions/workflows/tests.yml/badge.svg)](https://github.com/ddev/drupal-rfs-custom-commands/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

# drupal-rfs-custom-commands <!-- omit in toc -->

* [What is drupal-rfs-custom-commands?](#what-is-drupal-rfs-custom-commands)
* [Components of the repository](#components-of-the-repository)

## What is drupal-rfs-custom-commands?

The addon 'drupal-rfs-custom-commands' was developed to offer DDEV command shortcuts for common actions working with Drupal sites, like enabling/disabling Twig debugging or caching. 

In DDEV addons can be installed from the command line using the `ddev get` command, for example, `ddev get ddev/drupal-rfs-custom-commands` or `ddev get ddev/ddev-drupal9-solr`.

## Components of the repository

* A web command [ctoggle](commands/web/ctoggle) that will enable or disable caching.
* A web command [tdebug](commands/web/tdebug) that will enable or disable Twig debugging.
* A web command [make](commands/web/make) that...
* A host command [x](commands/host/x) that... 
* A [docker-compose.drupal-rfs-custom-commands.yaml](docker-compose.drupal-rfs-custom-commands.yaml) file.
* An [install.yaml](install.yaml) file that describes how to install the service or other component.
* A test suite in [test.bats](tests/test.bats) that makes sure the service continues to work as expected.
* [Github actions setup](.github/workflows/tests.yml) so that the tests run automatically when you push to the repository.

**Contributed and maintained by [@CONTRIBUTOR](https://github.com/CONTRIBUTOR) based on the original [ddev-contrib recipe](https://github.com/ddev/ddev-contrib/tree/master/docker-compose-services/RECIPE) by [@CONTRIBUTOR](https://github.com/CONTRIBUTOR)**

**Originally Contributed by [somebody](https://github.com/somebody) in <https://github.com/ddev/ddev-contrib/>
