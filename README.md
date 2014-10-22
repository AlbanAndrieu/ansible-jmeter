ansible-jmeter
====================

A role for installing jmeter.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-jmeter.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-jmeter)

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
