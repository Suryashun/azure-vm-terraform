## Architecture Diagram

This project provisions an Azure Virtual Machine using Terraform with the following components:

- Resource Group
- Virtual Network (VNet)
- Subnet
- Public IP
- Network Security Group (NSG)
- Virtual Machine (VM)

### Flow

Internet → Public IP → NSG → VNet → Subnet → VM
