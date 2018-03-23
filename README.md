Role for bigbrain Engine Deployment
=========

This Role will install and configure all the dependencies for Bigbrain Engine 

Install and configure Jupyter.

Requirements
------------

This Role is required for Engine Bigbrain.


Role Variables
--------------

Role variables are defined in Defaults folder.
User variable can be externalised in the main playbook file.

Dependencies
------------

Python3.5 (Bigbrain works on Python3+)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      remote_user: user
      become: true
      become_method: sudo
      roles:
         - ansible-role-engine-setup

License
-------

Razorthink INC

Author Information
------------------

Nishan P A

Devops Team
Razorthink Inc

Contributors:

Arjun Das M
Nitanka Gogoi
Muhammed Shahin
