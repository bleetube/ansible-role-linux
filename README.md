# linux role

This is an Ansible role that installs a baseline of useful packages for the Linux system administrator.

It is intended to be composed along with other playbooks in the micro-stack pattern (as described by Kief Morris' Infrastructure as Code, 2nd edition).

## requirements

* role: bleetube-dotfiles

## TODO

* include difftastic
* maybe include fzf, but not via apt because its an old version
* selectively prevent updates (e.g. [postgresql](https://askubuntu.com/a/18656))
* add a RedHat profile for Almalinux and Opensuse
* configurable username
* CI tests
