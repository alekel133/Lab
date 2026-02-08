# Network Device Inventory
- Description: Physical Network Device Inventory
- Revision: 1.0.0 (Revision changes with format change)
- Author: Alexander Kellough (alekel101301@gmail.com)
- Date: 2026-02-02 CST
 
## Home Rack
### labrou001.xander-lab.it.com
- __IPv4 Addresses__  : 
  - 192.168.1.251/24   - OOB Management IP Address
  - 172.30.0.1/30      - labl3s001 uplink L3 via Po1
    
- __Description__     : Lab Main Router
- __Manufacturer__    : Cisco
- __Model Number__    : ISR4351/K0
- __Serial Number__   : FLM2011WON4
- __Operating System__:
- __Notes__           : 
  - Default Route via 192.168.1.1 (Home Network WAN Link)
  - Temporarily serving as default DHCP server
  - NAT Overload enabled for internet connectivity.
    - Access List NAT created for this. <!-- *TODO: *Need a scheduled documentation review, to decide when a new document is needed -->

### labl3s001.xander-lab.it.com
- __IPv4 Addresses__  :
  - 172.16.0.1/24      - VLAN 999 - Management IP Address
  - 10.200.0.1/24      - VLAN 899 - Server Administrative VLAN
  - 172.30.0.2/30      - labrou001 uplink L3 via Po1

- __Description__     : Lab Core Switch
- __Manufacturer__    : Cisco
- __Model Number__    : WS-C3560CX-8PC-S V02
- __Serial Number__   : FDC2024Z22Q
- __Operating System__: IOS Version 15.2(4) E1
- __Notes__           : 
  - Default route via 172.30.0.1
  - Temporary DHCP helper address 172.30.0.1

### labswi001.xander-lab.it.com
- __IPv4 Addresses__  :
  - 172.16.0.2/24      - VLAN 999 - Management IP Address - DG: 172.16.0.1
  
- __Description__     : Lab Access Switch 1
- __Manufacturer__    : Cisco
- __Model Number__    : WS-2960X-48YS-L V05
- __Serial Number__   : FCW2111B2TC
- __Operating System__:
- __Notes__           :

### labswi002.xander-lab.it.com
- __IPv4 Addresses__  :
  - 172.16.0.3/24      - VLAN 999 - Management IP Address - DG: 172.16.0.1
  
- __Description__     : Lab Access Switch 2
- __Manufacturer__    : Cisco
- __Model Number__    : WS-2960X-48YS-L V05
- __Serial Number__   : FCW2111A1TX
- __Operating System__:
- __Notes__           : 
  - Has port chanell Po2 with Proxmox Hypervisor
