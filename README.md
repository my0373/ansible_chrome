Role Name
=========

An Ansible role to install the Google Chrome on RHEL7.

Requirements
------------

There are a number of dependant packages which are installed as part of this role]

Role Variables
--------------

LOCAL_RPM_PATH: "/tmp/"
CHROME_REPO:  "https://dl.google.com/linux/direct/"
CHROME_DEPS:
  - redhat-lsb
  - libXScrnSaver
CHROME_PACKAGE_NAME: "google-chrome-stable_current_x86_64.rpm"



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
        - rhel_chrome


License
-------

MIT

Author Information
------------------

Matt York (my0373@gmail.com)

https://github.com/my0373/rhel_chrome
