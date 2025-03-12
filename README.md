# 🌐 Enterprise Network Design Project

This project simulates a small-to-medium-sized enterprise network, featuring core and access switches, a main router, DHCP, VLANs, ACLs, and high availability planning.

## 📁 Project Structure
```
enterprise-network-design/
├── configs/
├── documentation/
├── diagrams/
├── README.md
└── setup-guide.md
```

## 📌 Key Features
- VLAN segmentation for departments
- IP addressing and subnetting plan
- DHCP and ACL configurations
- OSPF routing and static routes
- Firewall and NAT (optional expansion)
- High availability and backup planning

## 🔧 Sample Configuration Snippet
```plaintext
interface vlan 10
  ip address 192.168.10.1 255.255.255.0
  no shutdown
```

## 🔍 Topology Diagram
📎 Refer to `diagrams/enterprise-topology.png` *(upload your Draw.io diagram)*

## 💡 Future Improvements
- Add NAT configuration examples
- Simulate BGP for multi-homing
- Integrate wireless controllers and APs

## 🤝 Contributions
Feel free to fork and contribute!

---