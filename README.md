[![Build Status](https://travis-ci.org/mantti/ansible-role-apptainer.svg?branch=master)](https://travis-ci.org/mantti/ansible-role-apptainer)

ansible-role-apptainer
=========

Install and configure former singularity currently apptainer.

https://apptainer.org/

Requirements
------------

An already configured repository which has the apptainer packages.

The WLCG Linux Repo and OpenScienceGrid have apptainer packages.

Role Variables
--------------

see defaults/main.yml 

the settings in apptainer.conf is defined with this list:

<pre>
apptainer_settings:
</pre>

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-apptainer, x: 42 }

License
-------

MIT

Author Information
------------------

Inspiration from https://github.com/ryanolson/ansible-singularity
