# Born2beroot - 42 Network Project

---

## 🎯 **What is Born2beroot?**  
Born2beroot is a **system administration project** where you configure a Linux server (Debian/Ubuntu) to meet strict security and operational standards.  
**Why?** To learn:  
- Server hardening (security-first mindset).  
- Partitioning with **LVM** (flexible disk management).  
- User/group permissions and **sudo policies**.  
- Automation with **bash scripting** and **cron jobs**.  

---

## 📜 **What You Must Do**  
### 1. **Partitioning & LVM**  
- Create encrypted partitions using **LVM**.  
- Allocate logical volumes for `/`, `/home`, `/var`, etc.  
- *Why?* Master dynamic disk management for scalable systems.  

### 2. **SSH & Firewall**  
- Configure SSH to run on **port 4242**, disable root login.  
- Set up **UFW** (firewall) to allow only necessary ports.  
- *Why?* Secure remote access and block unauthorized traffic.  

### 3. **Sudo & Password Policies**  
- Create a custom `sudo` group with restricted privileges.  
- Enforce password rules:  
  - 30-day expiration.  
  - 10+ character length.  
  - Prevent recent password reuse.  
- *Why?* Mitigate brute-force attacks and privilege abuse.  

### 4. **Monitoring Script**  
- Write a `monitoring.sh` script to track:  
  - CPU/RAM usage.  
  - Disk space.  
  - Running services.  
- Schedule it via **cron** to run every 10 minutes.  
- *Why?* Automate system health checks.  

### 5. **Bonus (Optional)**  
- Deploy a **WordPress** site with **LEMP stack** (Nginx, MySQL, PHP).  
- Implement service auto-restart (e.g., SSH).  

---

## 🔗 **Learning Resources**  
### **LVM & Partitioning**  
- [LVM Deep Dive](https://www.digitalocean.com/community/tutorials/an-introduction-to-lvm-concepts-terminology-and-examples)  
- [Encrypting Partitions](https://ubuntu.com/tutorials/configure-full-disk-encryption#1-overview)  

### **SSH & Security**  
- [SSH Hardening Guide](https://ssh.com/academy/ssh/hardening)  
- [UFW Firewall Basics](https://www.linode.com/docs/guides/configure-firewall-with-ufw/)  

### **Sudo & Password Policies**  
- [Sudoers File Manual](https://www.sudo.ws/man/1.8.27/sudoers.man.html)  
- [Password Quality Control](https://manpages.debian.org/testing/libpam-pwquality/pam_pwquality.8.en.html)  

### **Bash Scripting & Cron**  
- [Bash Scripting Tutorial](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)  
- [Cron Job Examples](https://www.cyberciti.biz/faq/how-do-i-add-jobs-to-cron-under-linux-or-unix-oses/)  

### **General Linux Admin**  
- [Debian System Administration](https://www.debian.org/doc/manuals/debian-reference/)  
- [Linux Filesystem Hierarchy](https://www.tldp.org/LDP/Linux-Filesystem-Hierarchy/html/)  

---

## ❓ **Why This Project?**  
- **Real-World Relevance**: Mimics enterprise server setups.  
- **Security Focus**: Teaches defense against common attacks.  
- **Automation Skills**: Prepares you for DevOps/Cloud roles.  

---

## ✅ **What You’ll Need**  
- **Virtualization Software**: VirtualBox, VMWare, or UTM.  
- **Debian/Ubuntu ISO**: Download from [Debian](https://www.debian.org/download) or [Ubuntu](https://ubuntu.com/download/server).  
- **Patience**: Trial-and-error is part of sysadmin life.  

---

🚀 **Good luck, future sysadmin!**  
