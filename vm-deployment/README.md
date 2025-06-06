# 📌 Project: Deploying an Azure Virtual Machine

## 🧾 Overview  
In this project, I deployed a Windows Server virtual machine (VM) on Microsoft Azure using both the Azure Portal and Azure CLI. The VM was configured with proper networking rules, secure access, and monitoring tools. I also tested remote access using Azure Bastion instead of exposing RDP to the public internet.

## 🔧 Objectives  
- Deploy a virtual machine in Azure  
- Configure network security groups (NSGs)  
- Enable Azure Bastion for secure access  
- Enable boot diagnostics and monitoring  
- Use Azure CLI for basic VM management

## 🧰 Tools & Services Used  
- Microsoft Azure Portal  
- Azure CLI  
- Azure Bastion  
- Network Security Groups (NSGs)  
- Azure Monitor  
- Resource Group & Virtual Network (VNet)  
- Windows Server 2019 Image

## 🛠️ Steps Taken  
1. Created a Resource Group  
2. Set Up Virtual Network and Subnet  
3. Provisioned a Windows VM  
4. Configured Azure Bastion  
5. Enabled Monitoring  
6. Cleaned up resources

## ✅ What I Learned  
- How to securely deploy and access a VM in Azure  
- Importance of NSGs and minimizing open ports  
- Azure Bastion improves VM security  
- How to use Azure Monitor for diagnostics

## 📸 Screenshots

**1. Virtual Machine Overview Page**  
Shows the Azure Portal dashboard with the VM running and details like public IP and resource group.  
![VM Summary](./screenshots/vm-summary.png)

**2. Connect to VM via RDP**  
Screenshot of the Connect blade showing RDP connection options or Azure Bastion.  
![Connect RDP](./screenshots/connect-rdp.png)

**3. Installing IIS with PowerShell**  
Inside the VM, running the PowerShell command to install the Web Server (IIS) role.  
![Install IIS](./screenshots/install-iis.png)

**4. IIS Web Server Welcome Page**  
Browser showing the default IIS page after accessing the VM’s public IP.  
![IIS Welcome Page](./screenshots/iis-welcome-page.png)
