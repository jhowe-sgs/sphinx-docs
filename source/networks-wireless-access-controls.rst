Networks:: Wireless:: Access Controls
=====================================

Access to the SGS Wireless network is controlled through the Aruba Instant Web Interface.

Access to the SGS Wireless has a secondary access level through the pfSense box. Known MACs are whitelisted for Internet access. Unknown MAC addresses are corraled into the Captive Portal system.

.. warning:: Cell Phone Not Allowed on SGS Wireless Networks

   Offenders will have their MAC addresses blacklisted on the Aruba Controller

   Cell Phones generally come with their own data plans. We have limited space in our DHCP range for guest devices.