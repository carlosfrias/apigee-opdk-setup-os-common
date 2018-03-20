Apigee OPDK Common OS Setup
=========

This roles setups operating system packages and configs that would allow OPDK to function properly and 
for the system admin to have the tools needed to perform troubleshooting with greater ease. This role builds on the 
bare bones setup performed by apigee-opdk-setup-os-minimum. 

Requirements
------------
The installation of Apigee OPDK requires root access. Credentials must also be supplied to override the empty placeholders
provided here. It is recommended that credentials be consolidated into a single credentials.yml file that can be stored 
separately. It is assumed that files containing credentials are stored in the ~/.apigee folder. 


Role Variables
--------------

No variables defined here

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: apigee-opdk-setup-os-common }

License
-------

Apache License Version 2.0, January 2004

Author Information
------------------

Carlos Frias
<!-- BEGIN Google Required Disclaimer -->

# Required Disclaimer

This is not an officially supported Google product.
<!-- END Google Required Disclaimer -->