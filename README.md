# Cloud-Network-Lab
Hybrid cloud networking project with hub-and-spoke architecture, VPN, firewall, and subnet segmentation in Azure.

# Azure Hub-and-Spoke Network Lab

## 📌 Overview
This project demonstrates the design and deployment of a **hub-and-spoke virtual network architecture in Microsoft Azure** with secure segmentation, hybrid connectivity, and firewall protection.

## 🏗️ Architecture
- **Hub VNet**: Azure Firewall + VPN Gateway
- **Spoke1 VNet**: Web servers behind Load Balancer
- **Spoke2 VNet**: Database servers
- **Security**: Network Security Groups (NSGs) + Host firewalls
- **Connectivity**: Site-to-Site VPN + Point-to-Site VPN

![Hub and Spoke Diagram](diagrams coming soon)

## 🔑 Key Skills Practiced
- Azure Networking (VNets, Subnets, Peering)
- Azure Firewall + NSG security layers
- Hybrid connectivity (VPN Gateway)
- Load balancing and high availability
- Infrastructure-as-Code basics (Terraform/Bicep)

## 🧪 Testing & Validation
- Verified subnet-to-subnet communication
- Tested VPN connectivity from on-prem lab
- Confirmed firewall rules blocking unauthorized traffic
- Load balancer distributing traffic across web VMs

## 📚 Lessons Learned
- Defense-in-depth with NSGs + Firewall
- Hub-and-Spoke simplifies security management
- Automation makes redeployment much faster

## 🔗 LinkedIn Post
[Check out my LinkedIn write-up of this project here](coming soon)




---

## 📜 License

- **Code and scripts**: Licensed under the [MIT License](./LICENSE).  
- **Documentation and diagrams**: Licensed under [CC BY-NC 4.0](./docs/LICENSE-docs.txt).  

This means you are free to use, share, and adapt the code with attribution.  
Documentation and diagrams may be shared for learning and collaboration, but not for commercial purposes.
