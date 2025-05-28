# Data Communications and Networks Lab

> **Course**: Data Communications and Networks Laboratory  
> **Total Experiments**: 7  
> **Tools**: Cisco Packet Tracer, Wireshark

## 📋 Course Overview

Hands-on laboratory course covering fundamental networking concepts using simulation and packet analysis tools.

## 🛠️ Software Requirements

- **Cisco Packet Tracer 8.2+** - Network simulation ([Download](https://www.netacad.com/courses/packet-tracer))
- **Wireshark 4.0+** - Packet analyzer ([Download](https://www.wireshark.org/))
- **System**: Windows/macOS/Linux, 4GB RAM, 2GB storage

## 🧪 Lab Experiments

### Experiment 1: Network Topologies
- Design Bus, Star, Ring topologies in Packet Tracer
- Test basic connectivity with ping
- **Tool**: Cisco Packet Tracer

### Experiment 2: OSI Model & Protocol Analysis
- Capture and analyze HTTP, TCP, IP packets
- Use Wireshark filters for protocol examination
- **Tools**: Wireshark, Packet Tracer

### Experiment 3: IP Addressing & Subnetting
- Configure IP addressing schemes
- Implement subnetting and VLSM
- **Tool**: Cisco Packet Tracer

### Experiment 4: Routing Protocols
- Configure static and dynamic routing (RIP, OSPF)
- Analyze routing tables
- **Tool**: Cisco Packet Tracer

### Experiment 5: Switching & VLANs
- Configure VLANs and inter-VLAN routing
- Implement Spanning Tree Protocol
- **Tool**: Cisco Packet Tracer

### Experiment 6: Network Security
- Configure Access Control Lists (ACLs)
- Basic firewall implementation
- **Tools**: Packet Tracer, Wireshark

### Experiment 7: Network Troubleshooting
- Diagnose connectivity issues
- Use diagnostic tools (ping, traceroute)
- **Tools**: Packet Tracer, Wireshark

## 🚀 Getting Started

### Installation
1. **Cisco Packet Tracer**: Create NetAcad account → Download → Install
2. **Wireshark**: Download from official site → Install with admin rights

### Quick Test
- **Packet Tracer**: Create 2 PCs + 1 switch, test connectivity
- **Wireshark**: Start capture → Browse web → Analyze packets

## 🔧 Command Reference

### Router Configuration
```cisco
Router> enable
Router# configure terminal
Router(config)# interface fastethernet 0/0
Router(config-if)# ip address 192.168.1.1 255.255.255.0
Router(config-if)# no shutdown
```

### Wireshark Filters
```
http                    # HTTP traffic
ip.addr == 192.168.1.1  # Specific IP
tcp.port == 80          # HTTP port
```

## 📚 Resources

- **Textbook**: "Computer Networking: A Top-Down Approach" - Kurose & Ross
- **Online**: Cisco NetAcad courses, Wireshark documentation
- **Video**: Professor Messer Network+ series

## 🏆 Skills Developed

- Network design and configuration
- Protocol analysis and troubleshooting
- Router/switch configuration
- Network security implementation
- Technical documentation

---

*Created in year 2 semester 4 -> 2025*
