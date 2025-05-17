# University Network Project  
**IT Infrastructure Management**  
February 11, 2023  

---

## Project Overview

This project involves designing and configuring a network for a small educational organization, specifically a university network connecting several colleges. The network setup facilitates communication and resource sharing to enhance the educational process. The topology and device selection align with the project requirements, incorporating various network devices and protocols to build a robust infrastructure.

---

## Network Topology and Devices

- **Routers:** 3  
- **Switches:** 4  
- **PCs:** 7  
- **Laptops:** 6  
- **Tablets:** 3  
- **Printers:** 2  
- **Servers:** 2  
- **Wireless LAN Controllers:** 2  
- **Lightweight Access Points:** 2  
- **Cabling:** Straight-through, crossover, serial, console cables

---

## Key Configurations

### Static IP Configuration  
- PCs and laptops were configured with static IP addresses relevant to their VLANs.

### Printer Configuration  
- Printers assigned IP addresses, subnet masks, and default gateways to enable network printing.

### DHCP Server  
- DHCP enabled on servers to assign dynamic IP addresses to certain devices automatically.

### Wireless LAN Controller (WLC) & Lightweight Access Points  
- Configured for centralized management of wireless network devices to simplify deployment and security management.

### Routing Protocols  
- **RIPv2:** Configured on Router 0 and Router 1 for basic routing.  
- **OSPF:** Configured on Router 2 to enable efficient and scalable routing.

### VLANs Configuration  
- Four VLANs were created representing different colleges/departments: Nursing, Computer Science, Engineering, and Faculty/Staff.

### Console Cable Configuration  
- Used for initial device setup and management.

---

## Testing and Validation  
Connectivity tests were performed to verify communication within and across VLANs and subnets, confirming successful network setup.

---

## Conclusion  
The project successfully established a well-structured university network integrating VLANs, routing protocols, wireless controllers, and diverse devices. The network supports seamless communication across different colleges, facilitating enhanced academic collaboration and resource sharing.

---

## References  
- Techopedia. (2022). *IT Infrastructure*. Retrieved from https://www.techopedia.com/definition/29199/it-infrastructure  
- Din, A. (2021). *What Is WLC in Networking and Why Is It Important?* Heimdal Security Blog. Retrieved from https://heimdalsecurity.com/blog/what-is-wlc-in-networking/  

