# Day 1 – Lab Setup & Documentation Framework

## 🎯 Objective
Prepare lab environment (Proxmox,TPLink Switch, OPNsense, Windows Server, Windows Client)

## 🛠 Steps Completed
1. Verified Proxmox networking (vmbr0 bridge linked to physical NIC).  
   - **Why:** Ensures reliable VM communication.  
2. Confirmed OPNsense firewall GUI accessible at 192.168.1.1.  
   - **Why:** Firewall/router is required for segmentation and secure lab operation.  
3. Created VM shells:  
   - DC01 (Windows Server 2022)  
   - CLIENT01 (Windows 11 Pro)  
   - **Why:** Core of AD environment for testing.  
4. Captured baseline screenshots (Proxmox, OPNsense, GitHub).  
   - **Why:** Provides proof of environment build.  

## 📸 Screenshots
- [ ] Proxmox network config
- [ ] TPLink switch homelab isolation (vlan10) config  
- [ ] OPNsense dashboard  
- [ ] GitHub repo structure  

## 🧠 Reflection
- Lab environment is now ready for building Active Directory.   
- Tomorrow: Install and configure AD DS on DC01.
