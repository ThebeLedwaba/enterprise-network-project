# 🗂 IP Addressing Plan

| VLAN | Subnet | Gateway | Device Range | DHCP/Static |
|------|--------|---------|--------------|-------------|
| 10 (Admin) | 192.168.10.0/24 | 192.168.10.1 | .10 - .200 | Static |
| 20 (HR) | 192.168.20.0/24 | 192.168.20.1 | .10 - .200 | Static |
| 30 (IT) | 192.168.30.0/24 | 192.168.30.1 | .10 - .200 | DHCP |
| 40 (Engineering) | 192.168.40.0/24 | 192.168.40.1 | Reserved | TBD |

> Static IPs for critical infrastructure (servers, switches, routers)