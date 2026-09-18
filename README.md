# IaC Generator for Bicep V1

**Built by Martin Yeung**

Drag-and-drop visual builder for Azure Bicep - 100% frontend, free, no backend, GitHub Pages ready.

### Features V1
- Visual Canvas: Drag dots to link VM→Subnet→VNet, NSG↔Subnet, App/Func→Plan, Func→Storage, SQL DB→Server
- Foundation: Resource Group, Virtual Network, Subnet, NSG
- Compute: Virtual Machine (with OS disk type selector + 4x Data Disks), App Service Plan, App Service, Function App, Container Registry
- Data & Storage: Storage Account + 5 Blob Containers, SQL Server + Database, MySQL Flexible Server, PostgreSQL Flexible Server
- VM Details:
  - 12 common VM sizes (B1s to F2s_v2) with vCPU/RAM hints
  - OS presets: Ubuntu 22.04/20.04, Windows Server 2022/2019
  - OS Disk Type: Premium SSD (Premium_LRS), Standard SSD, Standard HDD
  - Data Disks up to 4: name, size (32-2048GB), type (Premium/Standard SSD/HDD), caching
- Storage: Blob Containers up to 5
- Resizable bottom panel (drag to resize Bicep editor)
- Bicep valid, ready to deploy
- 100% frontend, no API, no cost

### How to use
1. Open the GitHub Pages link
2. Drag resources from left to canvas
3. Click resource to edit settings on right
4. Drag dots to link resources
5. Copy code or Download Bicep

### GitHub Pages
This repo is deployed via GitHub Pages. Just push index.html to main branch and enable Pages.

### Author
Built by Martin Yeung
