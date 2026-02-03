# VLAN Plan
- Description: The outline for VLAN allocation and segmentation
- Revision: 1.0.0
- Author: Alexander Kellough (alekel101301@gmail.com)
- Date: 2026-02-02 CST

## Allocation
- 900 - 999 = Management
  - VLANs that are assigned to critical devices. Access to these is the highes priority.
    - Routers
    - Switches
    - VM Hypervisors
    - Cloud Gateways

  - Decrements from 999 -> 900
  
- 800 - 899 = Administrative
  - VLAN's to administrative interfaces.
    - Other servers
    - VM admin interfaces
    
  - Decrements from 899 -> 800

- 700 -799 = Experimental
  - Temporary LABs, experiments, etc. 
  - *SHOULD BE AIRGAPPED*

- 600 - 699 = Cloud VLAN's
  - Off site virtual machines and clients.

- 500 - 599 = Development / Container VLAN
  - VLANs for hosting development branches of software and containers
  
- 400 - 499 = Server VLANs
  - VLANs for on-site server and virtual machine access.
  
- 0 - 399 = Client VLANs
  - VLANs for client devices and simulated client devices.
  - *This allocation is being left ambigous on purpose. The exact allocation should be decided before use.*
