# ⚙️ Setup Guide

This guide helps you set up and simulate the network using GNS3 or other tools.

## Tools You Can Use:
- GNS3 (recommended)
- EVE-NG or Cisco VIRL
- VirtualBox (for simulated endpoints)

## Setup Steps:
1. Open GNS3 and import required router and switch images.
2. Use configs/ to copy-paste CLI setup on devices.
3. Connect devices logically as per the diagram.
4. Assign VLANs and trunk ports on switches.
5. Configure routing (OSPF + static route) on router.

## Sample Topology
Upload the `.drawio` file and export PNG to `diagrams/`.

## Troubleshooting Tips:
- Use `show vlan brief`, `show ip route`, `show run`
- Ensure all interfaces are `no shutdown`
- Check GNS3 device idle-PC settings

---