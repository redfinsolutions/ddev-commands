![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

# Redfin Solutions Drupal Commands <!-- omit in toc -->

## What is it?

A package of helper commands for `ddev` commonly used when developing Drupal websites.

## How to install?
DDEV addons can be installed from the command line using the `ddev get` command. For this addon, run `ddev get redfinsolutions/ddev-commands` .

## Available commands

* A web command [ctoggle](commands/web/ctoggle) that will enable or disable caching.
* A web command [tdebug](commands/web/tdebug) that will enable or disable Twig debugging.
* A web command [make](commands/web/make) that runs a `make` command inside DDEV.
* A web command [phpunit](commands/web/phpunit) that runs a `make` command inside DDEV.
* A host command [login](commands/host/login) to open a browser to a Drupal site with an admin login.
* A host command [stop-other](commands/host/stop-other) to stop all other running DDEV projects.
* A host command [x](commands/host/x) to execute any command inside DDEV.


**Based on the original [ddev-contrib recipe](https://github.com/ddev/ddev-contrib/tree/master/docker-compose-services/RECIPE) by [@CONTRIBUTOR](https://github.com/CONTRIBUTOR)**
