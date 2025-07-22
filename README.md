# 🐧 Linux Installation & Developer Setup Guide

Welcome to the **Complete Linux Installation & Programming Environment Setup Guide**.  
এই গাইডটি আপনাকে Linux ইনস্টলেশন থেকে শুরু করে ডেভেলপমেন্ট সেটআপ পর্যন্ত ধাপে ধাপে সহায়তা করবে।  

---

## 📋 Table of Contents

1. [System Requirements](#system-requirements)
2. [Choosing a Linux Distribution](#choosing-a-linux-distribution)
3. [Step-by-Step Installation Guide](#step-by-step-installation-guide)
4. [First Boot & Post-Installation Setup](#first-boot--post-installation-setup)
5. [Installing Essential Development Tools](#installing-essential-development-tools)
6. [You're Ready!](#youre-ready)

---

## 🖥️ System Requirements

- ✅ **4 GB RAM** (Recommended 8 GB)
- ✅ **20 GB Free Disk Space**
- ✅ USB Drive (Minimum 8 GB for bootable)
- ✅ Internet Connection

---

## 🐧 Choosing a Linux Distribution

| Distribution | Best For | Features |
|--------------|----------|----------|
| **Ubuntu** | Beginners, Developers | User-friendly, LTS Support, Vast Community |
| **Fedora** | Latest Software, Developers | Cutting-edge packages, Security features |
| **Debian** | Stability, Servers | Rock-solid performance, Stable releases |

---

## 📝 Step-by-Step Installation Guide

### 1️⃣ Download Linux ISO  

- **Ubuntu:** [https://ubuntu.com/download](https://ubuntu.com/download)  
- **Fedora:** [https://getfedora.org/](https://getfedora.org/)  
- **Debian:** [https://www.debian.org/distrib/](https://www.debian.org/distrib/)  

---

### 2️⃣ Create a Bootable USB  

- For **Windows:** Use **Rufus** — [https://rufus.ie/](https://rufus.ie/)
- For **Linux/Mac:** Use **balenaEtcher** — [https://www.balena.io/etcher/](https://www.balena.io/etcher/)

**Steps:**
- Insert USB Drive
- Open Rufus/balenaEtcher
- Select ISO file
- Start the process to create bootable USB

---

### 3️⃣ Boot from USB & Install Linux  

- Insert bootable USB & Restart your PC
- Enter BIOS/UEFI (F2, F12, ESC, DEL — depends on your system)
- Select **Boot from USB**
- Follow On-Screen Installation Wizard:
  - Choose Language & Keyboard
  - Set Timezone
  - Partition Disk (Automatic Recommended)
  - Create Username & Password
  - Start Installation

---

## 🛠️ First Boot & Post-Installation Setup

### ✅ 1️⃣ Update System

```bash
sudo apt update && sudo apt upgrade -y
###Install Basic utilities
sudo apt install -y curl wget git vim build-essential
### Setup Firewall (optional)
sudo ufw enable
💻 Installing Essential Development Tools

Tool	Installation Command

###Git
sudo apt install git
###Python3 & pip
sudo apt install python3 python3-pip
###Node.js & npm
sudo apt install nodejs npm
###GCC/G++
sudo apt install build-essential
###VS Code (via Snap)
sudo snap install code --classic
