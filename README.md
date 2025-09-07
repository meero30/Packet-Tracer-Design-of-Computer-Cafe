# Seamless Connectivity: Designing an Efficient Network Architecture for Computer Shops

This project focuses on designing and simulating an efficient and reliable **network architecture for computer shops (internet cafes)**. The goal is to provide seamless connectivity for both shop owners and customers, ensuring stable performance even under high-demand scenarios such as gaming and streaming.

## 📖 Background
Computer shops require robust and stable networks to handle multiple users simultaneously. Traditional low-budget setups rely on **ISP-provided routers and hubs**, which often suffer from data collisions, poor bandwidth management, and security limitations.  

This project addresses those issues by designing a more structured and **scalable network**, with dedicated routers, switches, subnetting, and VLAN concepts for enhanced stability, security, and user experience.

## 🎯 Objectives
1. Design a **computer shop network** that supports multiple desktops.  
2. Simulate the network in **Cisco Packet Tracer**.  
3. Apply **subnetting techniques** to separate Admin, Regular, and VIP users.  
4. Monitor and evaluate **network latency** and connectivity in the simulation.  

## 🛠️ Network Design
- **Routers and Switches**: Used to interconnect devices and manage traffic.  
- **Subnetting**: Three subnet groups were defined – Admin, Regular, and VIP.  
- **Static IP Assignment**: Ensures effective management and easy troubleshooting.  
- **Topology**: Star topology for scalability and stability.  
- **Security**: VLAN separation, firewall concepts, and access boundaries.  

### Subnet Groups
- **Admin LAN**: Full control and management of the network.  
- **Regular LAN**: Shared access for general users.  
- **VIP LAN**: Prioritized access for premium users.  

### Example IP Assignments
- **Admin PCs**: `192.168.1.x`  
- **Regular PCs**: `192.168.2.1 – 192.168.2.63`  
- **VIP PCs**: `192.168.2.64 – 192.168.2.253`  

## ⚙️ Simulation
- Implemented in **Cisco Packet Tracer**.  
- Message passing and **ping tests** were performed between different LANs.  
- Results validated seamless communication across subnets with minimal latency.  

## 📊 Key Features
- **Reliability**: Avoids single points of failure by structuring routers and switches logically.  
- **Scalability**: Easily extendable for more computers and future needs.  
- **Security**: VLAN separation and firewall considerations enhance data privacy.  
- **Performance**: Proper bandwidth allocation and QoS concepts for smooth user experience.  

## 👥 Authors
- **Concepcion Edwin Jr (EQ1)**  
- **Miro Manuel L. Hernandez (EQ2)**  
- **Athena Cerila Lee (EQ2)**  
- **James Bradley Sy (EQ2)**  
- **Dominic Yu (EQ1)**  

De La Salle University – Manila  
Department of Electronics and Computer Engineering  

## 📌 References
Full references are available in the [Final Project Report](./Project%20Documentation%20Comp%20Cafe.pdf).
