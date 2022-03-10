# Scoop Bucket For NYDIG Devtools

## Purpose

The [scoop](https://scoop.sh/) bucket contains tools distributed by the NYDIG devtools team.

## Prerequisites

1. Install and configure `Scoop` as described [here](https://nydig.atlassian.net/wiki/spaces/EN/pages/959414291/Windows-native+development+environment+setup#Installing-Scoop).
2. Make sure your access to GitHub is configured using SSH keys. Instruction how to configure the access using command-line ssh client is [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh); steps to configure the access using Putty are listed [here](https://nydig.atlassian.net/wiki/spaces/EN/pages/959414291/Windows-native+development+environment+setup#Git-and-SSH-setup-using-Putty-tools).

## Installation

1. Add bucket to your scoop configuration: `scoop bucket add nydig-devtools git@github.com:astelmachonak-nydig/nydig-devtools.git`
2. Install application by running `scoop install <application>`. Required dependencies will be installed automatically.

## List of applications

- [okta-aws-cli-assume-role](https://github.com/oktadev/okta-aws-cli-assume-role)

## Uninstall

To uninstall the brew tap, you can run

`scoop bucket rm nydig-devtools`

You will need to uninstall any scripts you have installed from the nydig-devtools tap before running this command.
