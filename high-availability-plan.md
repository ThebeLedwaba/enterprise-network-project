# High Availability Plan

- **HSRP (Hot Standby Router Protocol)** for gateway redundancy:
  - VLAN 10: HSRP group 10, virtual IP 192.168.10.254
  - VLAN 20: HSRP group 20, virtual IP 192.168.20.254

- **EtherChannel** for link aggregation between switches:
  - Configure Port-Channel 1 between Core and Access switches.

- **STP (Spanning Tree Protocol)** to prevent loops:
  - Enable Rapid PVST+ on all switches.

- **UPS and Generator Backup** for critical devices.