# 🧰 Virtual Machine Setup: Pop!_OS in VirtualBox

## 🔍 Objective
Set up and configure a Pop!_OS virtual machine using VirtualBox. This project demonstrates core virtualization skills including ISO installation, VM configuration, troubleshooting, and Guest Additions installation.

---

## 🛠 Tools Used
- VirtualBox 7.1.6
- Pop!_OS ISO
- Terminal (APT package manager)
- Windows 10 (host OS)

---

## 🧪 Key Steps

### ✅ Confirm Virtualization
- Opened **Task Manager > Performance > CPU**
- Verified virtualization was enabled

### ✅ Downloaded and Installed
- Downloaded Pop!_OS ISO and VirtualBox
- Removed previous version of VirtualBox
- Confirmed successful downloads

### ✅ Configured VM in VirtualBox
- Base memory: 2048 MB
- Processors: 1
- Storage: 25 GB
- Video memory: 128 MB

### ✅ Performed OS Installation
- Encountered crash on first boot  
- Reinstalled Pop!_OS cleanly
- Created user + encryption password
- Configured desktop display settings

### ✅ Installed Guest Additions
- Ran system updates:  
  `sudo apt update && sudo apt upgrade`
- Mounted Guest Additions CD
- Installed with:  
  `sudo ./VBoxLinuxAdditions.run`  
  `sudo /sbin/rcvboxadd quicksetup all`
- Restarted and confirmed:
  - **Bidirectional clipboard sharing**
  - **Resizable display window**

---

## 💡 What I Learned
- How to verify virtualization support on a host machine
- How to configure and install Linux in a VM
- How to troubleshoot common install errors
- Benefits and setup of Guest Additions
- How to manage Linux updates and permissions

---

## 📸 Screenshots
(Upload to GitHub and link here)
- [ ] Virtualization check in Task Manager  
- [ ] Pop!_OS settings summary in VirtualBox  
- [ ] Final desktop view  
- [ ] Clipboard test (copying from VM to host)

---

## 🧑‍💻 Author
**Jason Guzman**  
Course: IS-1003 (Spring 2025)  
Instructor: Professor Mitra  
Completed: February 11, 2025

