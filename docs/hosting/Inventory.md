# Hosting Device Inventory
- Description: Physical Hosting Device Inventory
- Revision: 1.0.0 (Revision changes with format change)
- Author: Alexander Kellough (alekel101301@gmail.com)
- Date: 2026-02-07 CST
 
## Home Rack
### labvmh001.xander-lab.it.com
- __IPv4 Addresses__  : 
  - 10.200.0.10/24 - VLAN 899 - DG: 10.200.0.1/24
    
- __Description__     : Proxmox Hypervvisor
- __Manufacturer__    : HP Enterprise
- __Model Number__    : 
- __Serial Number__   : 
- __Operating System__: ProxMox 
- __Notes__           : 
  - Has port channel with labswi002 via bond0
    - nic0, nic1, nic2, nic3
  - iLO currently non-functional due to outdated TLS, investigation path's forward.
