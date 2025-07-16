# Trybe-Insurance-Network-Redesign-and-Optimization-with-Cisco-Packet-Tracer


## 📝 Overview  
A hands-on simulation resolving IP conflicts in an Insurance organization using **Cisco Packet Tracer**.  
This project showcases how dynamic addressing, domain resolution, and web services can streamline  
network operations for a team of 12 staff.

---

## ❗ Problem Statement  
The organization faced persistent IP address conflicts due to manual static assignments across workstations.  
These conflicts disrupted communication, delayed access to critical tools, and highlighted the need for automated  
IP management and internal resource accessibility.

---

## 💡 Solution Architecture  
This project introduces a scalable LAN setup with the following core components:

- **DHCP Server:** Automates IP allocation to eliminate conflicts  
- **DNS Server:** Simplifies host resolution using human-readable domain names  
- **Web Server:** Hosts internal resources accessible by all users  
- **Cisco Packet Tracer Simulation:** Represents a realistic network for training and prototyping  

---

## 🔒 VLAN-Based Network Segmentation (Security Enhancement)

To reinforce security and streamline traffic management, the network design incorporates **Virtual LANs (VLANs)** that 
segment the 12 staff users into departments which are Admin, HR, IT and Finace. This mitigates the risk of lateral movement 
during potential intrusions and reduces unnecessary broadcast traffic.
  
### 🔐 Benefits  
- **Traffic Isolation**: Staff devices are grouped by roles or departments, limiting exposure between unrelated units  
- **Security Boundaries**: Enables implementation of ACLs or firewall policies between VLANs  
- **Scalability**: Future teams can be added without disrupting the existing structure  
- **Performance Optimization**: Reduces broadcast domains and improves overall speed  

### 🧰 Implementation Highlights  
- VLANs are configured on switches using the `vlan` command and assigned to ports accordingly  
- Inter-VLAN routing can be activated via a multilayer switch or routed links based on scale  
- Devices within the same VLAN communicate freely, while cross-VLAN communication is controlled  

---

## 🔧 Features  
- ✅ Dynamic IP management for 12 staff via DHCP  
- 🌐 Internal DNS resolution for ease of access  
- 🖥️ On-premises web server simulation  
- 📊 Organized topology with clear device roles  
- 🛡️ Error-free configuration and verification through simulation  

---

## 🛠️ Tools Used  
- Cisco Packet Tracer  
- DHCP & DNS configuration  
- Web Server setup  
- Network simulation techniques  

---

## 📂 Project Files  
- `.pkt` simulation file  
- Configuration notes and guides  
- Network topology diagram  
- Optional logs and setup instructions  

---

## 🎓 Educational Value  
This repo serves as a learning model for IT students, network engineers, and cybersecurity enthusiasts  
to understand how real-world scenarios can be solved using virtual simulations.

---

## 👨‍💻 Project By  
**Adams Samson**  
🔗 [linkedn](https://www.linkedin.com/in/adams-samson/)
