**## ⚠️ Caution**

> ⚠️ **Warning:** This repository contains scripts that interact with live Microsoft 365, Azure, Intune, and other production environments.  
> 🧪 Always review the code thoroughly before executing any script.  
> 🛡️ Use test environments whenever possible.  
> 🧑‍💻 You are solely responsible for the outcomes — use at your own risk!


# 📂 PowerShell Scripts Repository

A collection of PowerShell scripts for automating administrative tasks, system maintenance, reporting, and more. Useful for sysadmins, DevOps engineers, and IT pros.


## 📌 Contents

This repo includes scripts for:

- 📨 Managing Exchange Online (EXO V2/V3)
- 💼 Microsoft 365 user, license, and group management
- 🔐 Entra ID (formerly Azure AD) group membership, roles, and policies
- ☁️ Azure resource and identity automation
- 📱 Intune (Endpoint Manager) device compliance, configuration, and app deployment
- 🛠️ Windows system administration and maintenance
- 📊 Reporting, audits, and automation across services
- 🧠 Microsoft Graph-based management (cross-service via Graph API)
- 🧾 SharePoint and OneDrive site access, sharing, and storage control
- 💬 Microsoft Teams provisioning, channel setup, and policies


## 🧰 Requirements

- PowerShell 5.1 or PowerShell 7+
- Relevant PowerShell modules (see each script's comments)
- Administrator or delegated access in Microsoft 365/Azure
- Internet connection (for cloud-based scripts like Microsoft 365)

## 🛠️ Setup

To install any required modules, use:

powershell

Install-Module -Name ModuleName -Scope CurrentUser


# Microsoft Graph PowerShell SDK
Install-Module Microsoft.Graph -Scope CurrentUser

# Exchange Online V2/V3
Install-Module ExchangeOnlineManagement

🔐 Connect to Services
Microsoft Graph
Connect-MgGraph -Scopes "User.Read.All", "Group.ReadWrite.All", "Device.Read.All"

📃 License
MIT License – free to use, modify, and redistribute.




