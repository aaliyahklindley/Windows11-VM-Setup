# Windows 11 Virtual Machine Lab

### Objective
This lab was created to practice virtualization, operating system installation, and basic IT administration skills using VirtualBox and Windows 11.

---

## Technologies Used
- Windows 11
- VirtualBox
- ISO Installation Media

---

## Downloading VirtualBox

VirtualBox is the environment used to create and manage virtual machines for practicing hands-on IT concepts.

### Requirements
- Install VirtualBox
- Install the VirtualBox Extension Pack
<p align="center">
<img width="1920" height="1032" alt="Screenshot 2026-05-09 163923" src="https://github.com/user-attachments/assets/9f9dca7e-5e09-434d-b20a-9a1d0de2c143" />
</p>

---

# Creating Windows 11 Virtual Machine

## Windows 11 Download
Downloaded the Windows 11 ISO directly from Microsoft's website.
<p align="center">
<img width="1920" height="1032" alt="Screenshot 2026-04-18 182308" src="https://github.com/user-attachments/assets/30fbfc6c-764f-4abe-9a0b-c2b568b469af" />
</p>

### ISO Used
```text
Windows 11 Disk Image (ISO) for x64 devices
```

> Note: The download file is large and may take some time to complete.

---

## Set up Virtual Machine, Operating System, and Unattended Guest OS Installation
- Open Virtual Box
- Begin Virtual machine creation by opening "New" on the Virtual Box ToolBar
- Link you recently downloaded Windows 11 ISO file in the "ISO Image" section.  
- Proceed to the Unattended Guest OS Installation and input a password and a username.
> Important: Keep passwords and security question answers documented securely.
<p align="center">
<img width="1920" height="1032" alt="Screenshot 2026-05-09 172517" src="https://github.com/user-attachments/assets/205e3fcd-81b4-4fc8-b43e-6f3219ae629b" />
</p>

### Recommended Hardware Configuration
```text
Base Memory: 8192 MB (8 GB)
Processors: 2 CPUs
EFI Enabled: Yes
Disk Size: 80 GB
```

After configuring hardware settings, the virtual machine was powered on to begin installation.

---

## Windows 11 Setup Process

### Installation Configuration
- Proceed with default installation settings
- No product key selected during setup
- Installed Windows 11 Pro
<p align="center">
<img width="511" height="386" alt="Screenshot 2026-05-09 175516" src="https://github.com/user-attachments/assets/29672876-96aa-4388-a780-79510745c260" />
<img width="509" height="383" alt="Screenshot 2026-05-09 175600" src="https://github.com/user-attachments/assets/de582d54-4833-4d50-89b7-792aeb26e98e" />
</p>

### Account Setup
- Proceed with default installation settings
- Configured as a work/school environment
- Selected “Join Domain Instead”
- Created local account credentials and security questions for the virtual machine environment.
<p align="center">
<img width="509" height="382" alt="Screenshot 2026-05-09 175708" src="https://github.com/user-attachments/assets/866f3d52-6249-495d-9bfd-d04447f5fbf4" />
<img width="511" height="383" alt="Screenshot 2026-05-09 181808" src="https://github.com/user-attachments/assets/d5053b7c-7f5b-4f45-842f-696ef1a2bb6c" />
</p>

---

## Fixing Small Screen Resolution/ Guest Additions Installation

<p align="center">
  <img width="510" height="383" alt="Screenshot 2026-05-09 182812" src="https://github.com/user-attachments/assets/a4cdd247-1cee-4149-a91d-c50ef402f305" />
  <br>
  <em>Before</em>
</p>

<p align="center">
  <img width="1920" height="1080" alt="Screenshot 2026-05-09 182720" src="https://github.com/user-attachments/assets/991c290a-f5eb-476e-82f9-3db56ec17f7b" />
  <br>
  <em>After</em>
</p>

- Step 1
Outside the VM:
```text
Devices > Insert Guest Additions CD Image
```
- Step 2
Inside the VM:
```text
File Explorer > CD Drive > VBoxWindowsAdditions
```
- Step 3
  - Install drivers
  - Reboot the virtual machine
- Step 4
Outside the VM:
```text
View > Full Screen
Host + F
```

---

## Challenges Encountered

### Problem
The VM initially displayed a very small screen resolution.

### Solution
Installed VirtualBox Guest Additions and enabled full-screen mode.

---

## Skills Practiced
- Virtual machine deployment
- Windows 11 installation
- Resource allocation
- VirtualBox configuration
- Guest Additions installation
- Basic troubleshooting
- System configuration
  
---

## What I Learned
This lab helped reinforce virtualization concepts, operating system deployment, VM configuration, and troubleshooting skills commonly used in IT support environments.
