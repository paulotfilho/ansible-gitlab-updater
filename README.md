ansible-gitlab-updater
=========

Ansible role to update GitLab instances installed via repository.

Requirements
------------

- Ansible
- A GitLab instance
- Postfix for sending update email.

Role Variables
--------------

- send_from: Email address to send "updated instance" email.
- send_to: Email address to receive "updated instance" email.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: gitlab01
      gather_facts: no
 
      roles:
         - ansible-gitlab-updater


License
-------

BSD

