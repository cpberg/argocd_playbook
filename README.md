argocd
=========

Installs argocd via HELM and sets up default namespace for argocd  

Requirements
------------

CentOs 8 or later (7 may work) 

Role Variables
--------------

N/A

Dependencies
------------

- kuberntes 
- helm

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
     - { role: argocd }

License
-------

GNU

See also
------------------

