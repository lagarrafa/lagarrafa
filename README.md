# 🚀 IT Skills Development Log

## Overview
This repository serves as a structured log of my continuous learning and hands-on practice in IT, focusing on system administration, networking, virtualization, and troubleshooting. The goal is to enhance my technical expertise and document real-world problem-solving approaches.

## 🖥️ Technical Proficiencies
- **Operating Systems:** Windows Server, Linux (Ubuntu, CentOS, Debian)  
- **Virtualization:** VMware ESXi, VirtualBox  
- **Networking:** TCP/IP, VLANs, DHCP, DNS, Firewall Configuration  
- **Firewall:** Configuration, management, and security policies  
- **Load Balancing:** Application and network load balancing strategies  
- **Storage:** RAID, NAS, SAN  
- **Scripting & Automation:** Bash, PowerShell  
- **System Troubleshooting:** Performance monitoring, log analysis, debugging 

 <details>
  <summary><strong>📜 Courses and Certifications</strong></summary>

  ### 🏆 Completed  
  - **ITIL® Foundation Certificate in IT Service Management**  
    - *AXELOS Global Best Practice*  
    - Credential ID: **GR750272269LG**  

  - **ITIL® 4 Foundation**  
    - *Pink Elephant*  

  - **ONTAP 9.3 Cluster Administration**  
    - *NetApp*  
    - Credential ID: **STRSW-ILT-ONTAPADM**  
    - Class ID: **361850**  

  - **Storage System Recovery & Troubleshooting for Partners (SSRTS)**  
    - *NetApp*  
    - Class ID: **360749**  

  - **VMware vSphere: Install, Configure, Manage [V6.7]**  
    - *VMware*  
    - Class ID: **359310**  


  ### 🎯 In Progress  
  

  *(More courses and certifications will be added as I progress!)*  

</details>

<details>
  <summary>💼 Work Experience</summary>

### 🏢 IT Hardware Asset Management – NTT DATA Europe & Latam  

### 🏢 Senior Team Leader – NTT Ltd.  

### 🏢 Senior Infrastructure Analyst – NTT Ltd.  

### 🏢 Infrastructure Analyst – Accenture Technology Solutions  

### 🏢 Data Centre Operator – Lenovo  

### 🏢 Tier 2 Support & Training – Microsoft  

</details>



## 📅 Learning Log
This section documents technical exercises, configurations, and troubleshooting steps undertaken.

### Week 1
**Date:** 2025-02-17
- 🛠 Installed and configured VirtualBox on Windows.
- 🏗️ Created a virtual machine and installed Ubuntu.
- ⚙️ Installed VirtualBox Guest Additions for improved VM integration.
- 🔍 Practiced basic and intermediate Linux commands, including file system navigation, process management, and user permissions.
- 🛑 Diagnosed and resolved initial connectivity issues with Ubuntu VM.

**Date:** 2025-02-18
- 🛠 Installed GNS3 and deployed a Cisco router for training purposes and troubleshooting.
- 🛡️ Practiced network troubleshooting commands:
  - `ping <destination>` to test connectivity.
  - `traceroute <destination>` (Linux) or `tracert <destination>` (Windows) to analyze packet paths.
  - `netstat -an` to display active network connections.
  - `mtu` adjustments to troubleshoot fragmentation issues.
 
**Date:** 2025-02-19

💾 Virtual Machine & Windows Installation:

- Created a Windows 10 VM in VirtualBox.
- Allocated 4GB RAM, 2 vCPUs, and 50GB dynamic disk.
- Installed Windows 10 and configured initial settings.
  
🖴 Storage & RAID 5 Configuration (via Windows Disk Management GUI):
- Created three virtual disks (10GB each) in VirtualBox.
- Launched Disk Management (diskmgmt.msc) and initialized disks as GPT.
- Formatted disks with NTFS.
- Created RAID 5 volume using the Disk Management GUI:
- Right-clicked unallocated space → New RAID-5 Volume.
- Selected the three disks and assigned a drive letter.
- Configured NTFS formatting with default allocation size.
- Verified RAID 5 was correctly built and accessible.

📄 Testing RAID 5:
- Created and saved document.txt on the RAID volume.

❌ Simulating Disk Failure:
- Removed one disk from VirtualBox (Settings → Storage → Remove Disk).
- Observed RAID degradation in Disk Management (Status: Failed Redundancy).

🔄 RAID Recovery:
- Added a new virtual disk to VirtualBox.
- Initialized and formatted the new disk using Disk Management.
- Replaced the failed disk in the RAID 5 array via the GUI.
- Monitored RAID rebuild process until redundancy was restored.

    
_(Entries will be updated weekly to reflect ongoing progress.)_

## 📂 Repository Structure
```
📁 it-skills-log
 ├── 📄 README.md        # Technical documentation and progress tracking
 ├── 📁 configs/         # Configuration files and system setups
 ├── 📁 scripts/         # Automation scripts (Bash, PowerShell)
 ├── 📁 troubleshooting/ # Documented issue resolutions and solutions
 ├── 📁 networking/      # Network configurations, firewall rules, and tools
 ├── 📁 storage/         # Disk management, RAID setups, backup strategies
```



## 📡 Contact & Networking
- 📧 Email: [leonel_g@hotmail.com]
- 🔗 LinkedIn: [https://www.linkedin.com/in/leonel-garrafa/]
- 🐙 GitHub: [https://github.com/lagarrafa]
  

## 📌 Best Practices for GitHub Documentation
- **Commit Regularly:** Maintain a consistent update history.
- **Use Clear Commit Messages:** Describe changes concisely.
- **Provide Structured Documentation:** Ensure ease of understanding.
- **Include Real Configurations & Scripts:** Showcase practical skills.
- **Engage in Open Source Contributions:** Participate in relevant projects.

---

This repository serves as a technical portfolio to demonstrate hands-on expertise. Contributions and feedback are welcome! 🚀
