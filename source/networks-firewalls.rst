Networks:: Firewalls
====================

The school has two main firewalls.

- Palo Alto 500 sitting between the LAN segment and the pfSense
- pfSense between the DMZ WAN and the LAN segment

.. warning:: Single Point of Failure

   If the Palo Alto fails, all outbound Internet traffic is blocked!

   If the pfSense fails, all outbound Internet traffic is disconnected!