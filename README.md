Shariff PHP
===========

The teams at c't and heise developed a free and open piece of software providing a fair way to use social media buttons - without leaking all personal data of all visitors (see https://github.com/heiseonline/shariff).

This role installs the shariff-php backend onto your webserver.

State
-----

Unstable.

Installation
------------

    # ansible-galaxy install inofix.shariff-php

Requirements
------------

* Ansible >2.0
* Python2/3 on target host
* Generic UNIX with FHS
* Sudo

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - inofix.shariff-php

License
-------

GPLv3

Author Information
------------------

* Michael Lustenberger at [inofix.ch](http://www.inofix.ch)

