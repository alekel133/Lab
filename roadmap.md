# Roadmap
This is the brief breakdown and stages of how I expect my lab to progress.

## Stage 0: Stable Backplane
- Design overall network layout
 1. Decide on naming scheme for devices
 2. Design VLAN map.
 3. Configure all devices with management interfaces and appropriate IP Addresses.

- Test Continuity
 1. Confirm continuity accessibility in case of failure.
 

## Stage 1: Critical Network Services
- Design basic Virtualization Server
 1. Load Proxmox on server box.
 2. Make VM section for local services (DNS, DHCP, Domain Controller, etc.)
 3. Load Virtualization Server and backbone VM's with management addresses.
 
 - Test Continuity
   1. Unplug cables, disable services, etc.
   2. Confirm that VM's are still accessible even when certain core features are down (TBD).
 
## Stage 2: More Services + Lab + Automation Setup
 1. Setup some basic services (Web Server, Plex, etc)
 2. Setup a lab environment and virtual network.
 3. Setup automation (Ansible, terraform)
 4. Setup basic monitoring.
 5. Deploy containerized traffic generators to test different services.
 
## Stage 3: Scale & Integration
 1. Increase monitoring and response
 2. Create Domain Services (smtp server, file server, local ticketing server, etc.)
 3. Test pushes to phone / alerting
 4. Make tunnel to AWS for practice with cloud and remote service management
 
## Stage 4: Build and Lab
 - This is the stage where the lab is generally working. From here, we make test scenarios, write and host 
   programs, etc. 
