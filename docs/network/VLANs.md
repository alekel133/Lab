# VLANs
- Description: Source of truth for instantiated VLANs
- Revision: 1.0.0 (Will not change main revision unless overall VLAN structure does. See [admin/VLANS.md](../admin/VLANS.md) for more details)
- Author: Alexander Kellough (alekel101301@gmail.com)
- Date: 2026-02-02 CST

## Reserved Range
- 172.30.0.0-172.31.255.255 - Reserved for P2P, no VLAN assignment.

## Active VLANs
- 999 - Management VLAN - 172.16.0.0/24 <!-- Currently, may grow -->

## VLAN Maintenance Policy
All VLAN configuration changes must follow the below rules:
- Must be propagated across all affected networking devices
- Must be reflected in this document as the single source of truth.
