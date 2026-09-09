---
## ![Cybersecurity First Week Achievement Badge](IMG_6582.png)
---
🐧 My first hands on cybersecurity lab, where i deployed Kali Linux in Oracle VirtualBox and established a controlled environment for ethical hacking and security testing.

## 📌 Project Overview
This project documents my first practical cybersecurity laboratory exercise.
---
The objective is to build a virtual cybersecurity laboratory environment for penetration testing and ethical hacking practice by deploying **Kali Linux v2026.2** using **Oracle VirtualBox v7.2**.

The project provided practical experience with:

- Virtualization
- Kali Linux
- Linux system administration
- Networking
- Troubleshooting
  

The laboratory was performed on a **Lenovo laptop running Windows with 4 GB of RAM**.

---

## 🎯 Objectives

The main objectives of this project was to:

- Install and use VirtualBox
- Deploy Kali Linux in a virtual machine
- Configure virtual machine resources
- Start and access Kali Linux
- Test network connectivity
- Understand NAT networking

---

## 🔐 Cybersecurity Lab Environment

| 🧩 Component | ⚙️ Details |
|:---|:---|
| 🎯 **Skill** | Cybersecurity |
| 🖥️ **VirtualBox** | Oracle VirtualBox **7.2** |
| 🐉 **Operating System** | Kali Linux **2026.2** |
## 💻 Lab Environment

> **Cybersecurity Lab Specification**

| 🖥️ **HOST SYSTEM** | 🐧 **VIRTUAL LAB** |
|:---|:---|
| **Lenovo Laptop · 81H5** | **Kali Linux · v2026.2** |
| Windows · **4 GB RAM** | Oracle VirtualBox · **v7.2** |
|  | Network · **NAT** |
|  | RAM and CPU · *Configured according to available host resources* |
|  | Storage · **Virtual Disk** |

# 🚀 Kali Linux Deployment

## Step 1 — VirtualBox Setup

VirtualBox v7.2 was used as the virtualization platform.

A virtual machine was created and configured for Kali Linux v2026.2.

The configuration included:

- Kali Linux v2026.2
- Virtual CPU resources
- Allocated RAM
- Virtual storage
- NAT networking

The resources were configured according to the available hardware of the host computer.

---

## Step 2 — Creating the Kali Linux Virtual Machine

The Kali Linux v2026.2 virtual machine was created in VirtualBox.

The VM was configured with:

- **Operating System:** Kali Linux v2026.2
- **Virtualization:** Oracle VirtualBox v7.2
- **Network:** NAT
- **Virtual RAM:** Configured according to available host resources
- **Virtual CPU:** Configured according to available host resources
- **Virtual Disk:** Virtual storage

---

## Step 3 — Starting Kali Linux

The virtual machine was started through VirtualBox.

Kali Linux began the boot process and loaded into the Linux desktop environment.

---

# 🐧 Linux System Validation

After starting Kali Linux, basic Linux terminal commands were used to validate the system.

## Check Current User

```bash
whoami
```

**Purpose:** Displays the username of the currently logged-in user.

---

# 🌐 Network Connectivity Testing

Network connectivity was tested from the Kali Linux virtual machine using:

```bash
ping -c 4 networkwalks.com
```

## Purpose

The `ping` command was used to test whether the Kali Linux virtual machine could communicate with an external internet host.

The `-c 4` option sends four packets.

## Result

The test was used to verify network connectivity through the VirtualBox NAT configuration.

Where replies were received, this confirmed that the virtual machine could communicate with the external host.

---

# 🧪 Practical Evidence

### 01 — Internet Connectivity Test

![Internet Connectivity Test](IMG_6495.png)

After installing Kali Linux, an internet connectivity test was performed using the `ping` command.

### 02 — Identifying the Current User

![Whoami Command](IMG_6496.png)

The `whoami` command was used in Kali Linux to identify the currently logged-in user.

### 03 — Checking the Current Directory

![PWD Command](IMG_6497.png)

The `pwd` command was used in Kali Linux to display the current working directory.
# 🧪 Commands Tested

The following Linux commands were used during the laboratory:

```bash
whoami
pwd
ping -c 4 networkwalks.com
```

## ⌨️ Command Summary

<p align="center">

| 🌐 **NETWORK** | 👤 **IDENTITY** | 📂 **NAVIGATION** |
|:---:|:---:|:---:|
| `ping -c 4 networkwalks.com` | `whoami` | `pwd` |
| **Connectivity Test** | **User Identification** | **Directory Check** |

</p>

## ⚠️ Problems Encountered & Solutions

### 01 — Limited RAM

The host computer has **4 GB RAM**, which limited performance while running Windows, VirtualBox, Kali Linux and other applications.

| Issue | Solution |
|---|---|
| 🐌 Slow system & VM performance | Closed unnecessary applications |
| 💾 Limited available memory | Reduced background activity |
| ⏳ Longer VM startup | Allowed additional startup time |
| 🔧 Hardware limitation | Future upgrade to **8 GB RAM or more** |

**Result:** Kali Linux successfully operated within the available hardware resources.

---

### 02 — Slow Kali Linux Startup

Kali Linux experienced longer startup times due to the host's limited resources, particularly the **4 GB RAM constraint**.

**Troubleshooting:**
- Closed unnecessary Windows applications
- Reduced resource-intensive background processes
- Avoided running multiple demanding applications
- Allowed sufficient time for the VM to complete startup

**Result:** Kali Linux successfully booted and the Cybersecurity laboratory environment became operational.

> 💡 **Key Lesson:** Proper resource management is essential when running virtualised Cybersecurity environments on limited hardware.

## 🔧 Troubleshooting

| 🐌 **Issue** | 🔧 **Fix** |
|:---|:---|
| Slow Kali Linux | Closed unnecessary applications |
| Slow VM startup | Reduced background processes |
| Host responsiveness | Avoided unnecessary applications |
| Limited VM performance | Planned **8 GB+ RAM** upgrade |

---

# 🛠️ Tools & Resources

| 🧰 Tool | 📋 Description | 🔗 Resource |
|:---|:---|:---|
| 📦 **7-Zip** | 7-Zip was used as a file compression and extraction utility when working with downloaded files and archives. | [Download 7-Zip →](https://7-zip.org/download.html) |
| 🖥️ **Oracle VirtualBox** | Oracle VirtualBox was used to create and run the Kali Linux virtual machine. | [Download VirtualBox →](https://virtualbox.org/wiki/Downloads) |
| 🐉 **Kali Linux** | Kali Linux was used as the primary operating system for the hands-on cybersecurity laboratory and security testing exercises. | [Get Kali Linux →](https://kali.org/get-kali) |

**Kali Linux was used as the Cybersecurity focused operating system for the virtual laboratory environment*.


# 📚 Key Learning Outcomes

This project helped me develop practical knowledge of:

- Cybersecurity laboratory setup
- Virtualization
- Network interfaces
- NAT networking
- Hardware resource allocation
---

# 💭 Technical Reflection

This project demonstrated that cybersecurity requires more than simply learning security tools.

A cybersecurity professional also needs to understand operating systems, networking, virtualization, hardware resources and troubleshooting.

The **4 GB RAM limitation** provided practical experience of how insufficient system resources can affect a virtualized cybersecurity environment.

The experience also demonstrated the importance of monitoring system performance and allocating resources appropriately.

---

# 🔮 Future Improvements

For future cybersecurity laboratory projects, i plan to:
- Explore additional Kali Linux security tools
- Perform controlled network security exercises
- Build more cybersecurity laboratory projects

---
## 📊 Project Summary

> **Week 01 | Cybersecurity Lab**

| | |
|---|---|
| 🎯 **Project** | Cybersecurity Lab — Week 01 |
| 🛡️ **Focus** | Kali Linux Deployment & Virtualization |
| 💻 **Platform** | Oracle VirtualBox |
| 🔐 **Environment** | Isolated Cybersecurity Lab |
| ✅ **Status** | Completed |

---

# ⚖️ Ethical & Legal Disclaimer

All cybersecurity activities documented in this portfolio are intended for educational purposes.

Security testing should only be performed on systems, networks, applications and environments where appropriate authorization has been granted.

This laboratory environment is intended for controlled and authorized cybersecurity learning.

---

## 📚 References

*Official documentation used in this project.*

🐉 **Kali Linux** · [Documentation →](https://www.kali.org/docs/)  
📦 **Oracle VirtualBox** · [Documentation →](https://docs.oracle.com/en/virtualization/virtualbox/)  
🐙 **GitHub** · [Documentation →](https://docs.github.com/)  
🗜️ **7-Zip** · [Documentation →](https://www.7-zip.org/)

---

## 👤 Author

### Kabo Sekoto
**🔐 Junior Cybersecurity Practitioner**

> `Learning → Building → Testing → Securing`

This repository forms part of my practical cybersecurity learning portfolio, documenting hands-on labs, security experiments, and technical progression.

### 🌐 Cybersecurity Journey

<p align="center">
  <a href="https://linkedin.com/in/kabosekoto">
    <img src="https://img.shields.io/badge/🔵_LinkedIn-Professional%20Profile-0A66C2?style=for-the-badge" />
  </a>
  &nbsp;
  <a href="https://www.youtube.com/@IamSkottK">
    <img src="https://img.shields.io/badge/🔴_YouTube-Cybersecurity%20Lab-FF0000?style=for-the-badge" />
  </a>
</p>
