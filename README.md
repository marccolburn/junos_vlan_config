VLANs Configuration
=========

Configure VLANs for Junos.

Requirements
------------


Role Variables
--------------
vlans: List of Dictionaries containing VLANs

vlan_settings: Dictionary containing settings for VLANs


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_vlan_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
