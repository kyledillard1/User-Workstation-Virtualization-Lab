# 🖥️ User Workstation Virtualization Lab (Windows 11)

## 📌 Project Overview
This project simulates a **real-world end-user workstation** using **Windows 11** in a virtualized environment. The purpose of this lab is to demonstrate foundational IT support and field technician skills, including operating system deployment, user account management, network connectivity verification, and troubleshooting common workstation issues.

This lab reflects tasks commonly performed by **IT Support Specialists, Desktop Support, and IT Field Technicians** during new workstation setups and break/fix support.

---

## 🎯 Objectives
- Install and configure a Windows 11 workstation in a virtual machine  
- Create and manage local user accounts  
- Verify and troubleshoot network connectivity  
- Simulate common help desk and field technician scenarios  
- Document configuration and troubleshooting steps  

---

## 🛠️ Tools & Technologies
- VirtualBox (hypervisor)
- Windows 11 (64-bit ISO)
- Command-line networking tools (`ipconfig`, `ping`, `tracert`)
- GitHub for documentation and version control

---

## 🧱 Lab Environment

### Host System
- Physical PC with virtualization enabled
- Minimum 8 GB RAM

### Virtual Machine Configuration
- **VM Name:** WS-01  
- **Operating System:** Windows 11 (64-bit)  
- **Memory:** 4–8 GB RAM  
- **CPU:** 2 cores  
- **Storage:** 50 GB virtual disk  
- **Network Mode:** NAT  
## 🔧 Tasks Performed

### 1️⃣ Operating System Installation
- Installed Windows 11 using an ISO file
- Completed initial system setup and updates
- Verified system information and performance

### 2️⃣ User Account Management
- Created a local administrator account
- Created a standard user account
- Tested permission differences between administrative and standard users

### 3️⃣ Network Configuration & Testing
- Verified IP addressing using `ipconfig`
- Tested network connectivity using `ping`
- Confirmed DNS resolution and internet access

### 4️⃣ Peripheral Setup
- Installed and configured a printer
- Set default printer and verified installation

### 5️⃣ Troubleshooting Scenarios
The following issues were intentionally introduced and resolved:
- Disabled network adapter resulting in loss of connectivity
- Incorrect IP/DNS configuration preventing internet access
- Permission restrictions when installing software as a standard user

## 📸 Screenshots
Screenshots are included to document:
- Virtual machine configuration settings
- Successful Windows 11 installation
- User account creation
- Network connectivity tests
- Troubleshooting resolutions  

➡️ See the `screenshots/` folder.
