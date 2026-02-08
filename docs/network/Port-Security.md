# Port Security
- Description: Outlines port security requirements for all network enabled devices.
- Revision: 1.0.0
- Author: Alexander Kellough (alekel101301@gmail.com)
- Date: 2026-02-07

## All
1. All unused ports/interfaces on networked devices are to be disabled/shutdown and set to native VLAN.
2. All Management VLAN ports are to be limnited to a single MAC Address:
   - This prevents random user's from accessing this network
   - This forces documented changes in management access.

3. All Server Administrative VLAN ports are to be limited to only server/vm MAC Addresses
   - This includes virtual networking equipment. <!-- Enforcing boundaries is important, even virtually -->
   
4. *Note this requirement is to be implemented in the future, for now, just log MAC Addresses in inventory*
   All user access ports should be limited to inventoried MAC addressses and in restrict (or non-Cisco equivalent) mode.
   
5. Experimental ports are exempt from above requirements.
   - They must be on experimental VLAN. <!-- To prevent post-hoc decleration of experiment -->
