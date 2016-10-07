wrboyce.iterm2
==============

[![Build Status](https://travis-ci.org/wrboyce/ansible-iterm2.svg)](https://travis-ci.org/wrboyce/ansible-iterm2)

Install and Configure iTerm2.app

Requirements
------------

* [Homebrew](http://brew.sh)

Role Variables
--------------

Set the `iterm2_prefs_folder` variable if you wish to use a custom preferences folder.


Example Playbook
----------------

    - hosts: macos-workstations
      roles:
         - wrboyce.iterm2

License
-------

Apache 2.0
