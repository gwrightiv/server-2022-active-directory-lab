# Windows Server 2022 On-Prem Active Directory Lab

This project replicates a real-world scenario where an IT admin deploys and hardens a cloud-based domain controller in Microsoft Azure. It shows my ability to manage an enterprise Windows Server environment from provisioning through automation and security, using Active Directory, PowerShell, NTFS, and firewall rules. It also highlights my cost-conscious thinking with features like auto-shutdown and scripted updates.

The lab includes:
- Promotion of a Windows Server 2022 to a Domain Controller
- Joining a Windows 11 client to the domain
- OU and security group design
- GPO implementation for folder redirection and desktop wallpaper
- Shared folder access control with documented permission results
- Subnetting and network configuration

This project builds on my previous cloud-based AD experience in Azure and reflects the ability to manage on-prem enterprise environments.

---

## 🛠️ Lab Environment

- **Host Machine**: iMac (Intel)
- **Virtualization**: VirtualBox
- **Server OS**: Windows Server 2022
- **Client OS**: Windows 11
- **Domain Name**: `gwright.local`

---

## 📘 Skills Demonstrated

### ✅ Active Directory
- Created domain `gwright.local`
- OU structure for `Sales`, `Marketing`, and `Managers`
- Users and groups with appropriate descriptions

### ✅ Group Policy
- Deployed custom desktop wallpaper via GPO
- Redirected user `Documents` folders to a network share

### ✅ Shared Folder Access
- Created `Graham Sales` and `Graham Marketing` shares
- Controlled access using security group membership
- Verified results by testing login scenarios and file access

### ✅ Network & Subnetting
- Planned and implemented subnetting (up to /30)
- Used ICMP PING to validate connectivity across subnet boundaries

---

## 🖼️ Screenshots

Organized in the `/screenshots/` folder:
- `domain-join/`: Domain membership validation
- `gpo-wallpaper/`: Wallpaper successfully deployed
- `folder-redirection/`: Server redirect and access denied behavior
- `ou-structure/`: ADUC with proper user/OU layout
- `shared-access/`: Verified shared folder permissions

---

## 📄 Docs

Located in `/docs/`:
- Folder Redirection Setup
- Client Join Process
- Subnetting Design
- Group Policy Screens
- Final worksheets for IT125

---

## 🔄 Progression of Skills

This project represents the foundation of my Active Directory experience:

- [✔] **On-prem AD DS** using Windows Server 2022 in VirtualBox on my iMac (this project)
- [✔] **[Azure-based AD DS](https://github.com/gwrightiv/azure-vm-deployment)**: domain join, VM deployment, and role assignments in the cloud

