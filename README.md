ansible-jmeter
====================

A role for installing jmeter.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-jmeter.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-jmeter)
[![Galaxy](http://img.shields.io/badge/galaxy-jmeter-blue.svg?style=flat-square)](https://galaxy.ansible.com/list#/roles/1997)
[![Tag](http://img.shields.io/github/tag/AlbanAndrieu/ansible-jmeter.svg?style=flat-square)]()

## Actions

- Ensures that jmeter is installed (using `apt`)

Usage example
------------

    - name: Install jmeter
      hosts: jmeter
      user: root
    
      roles:
        - jmeter      

Requirements
------------

none

Dependencies
------------

none

License
-------

MIT

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-jmeter/issues)!
