# Linux System Commands, Package Managers, User Management & File System Guide

This file explains the next set of Linux commands, package managers, user/group commands, file structure, and login shells in very simple language—with examples.

---

# 🔹 System Information Commands

## **1. uname**
Shows system information (OS type, kernel version).
### Example:
uname -a

---

## **2. uptime**
Shows how long the system has been running.
### Example:
uptime

---

## **3. date**
Displays or sets the system date and time.
### Example:
date


---

## **4. who**
Shows who is currently logged into the system.
### Example:
who

---

## **5. whoami**
Shows your current username.
### Example:
whoami

---

## **6. which**
Shows the path of a command.
### Example:
which python

---

## **7. id**
Shows user ID (UID), group ID (GID), and group memberships.
### Example:
id


---

## **8. sudo**
Runs commands with administrator/root privileges.
### Example:
sudo apt update


---

## **9. shutdown**
Shuts down the system.
### Example:
sudo shutdown -h now

---

## **10. reboot**
Restarts the system.
### Example:

---

# 🔹 Package Managers (Different Linux Distros)

## **1. apt (Debian/Ubuntu)**
### Example:
sudo apt install nginx


---

## **2. yum (CentOS/RHEL older versions)**
### Example:
sudo yum install httpd

---

## **3. dnf (CentOS/RHEL/Fedora newer versions)**
### Example:
sudo dnf install httpd

---

## **4. pacman (Arch Linux)**
### Example:
sudo pacman -S firefox

---

## **5. portage (Gentoo Linux)**
### Example:
emerge firefox

---

# 🔹 User & Group Management

## **1. View all users**
cat /etc/passwd


---

## **2. userdel**
Deletes a user account.
### Example:
sudo userdel john
---

## **3. groupadd**
Creates a new group.
### Example:
sudo groupadd developers

---

## **4. gpasswd**  
is a command used to manage group membership on Linux.
You use it when you want to add or remove users from a group.
### Example:
sudo gpasswd -a john developers


---

## **5. groupdel**
Deletes a group.
### Example:
sudo groupdel developers


---

## **6. umask**
Controls default permissions for new files/folders.
### Example:
umask


---

# 🔹 Linux File System Structure (Simple Guide)

Below is a simple explanation of important Linux directories:

## **/** (root)
- The base of the entire filesystem.

## **/bin**
- Basic user commands (ls, cp, mv, rm).

## **/sbin**
- System admin commands (shutdown, reboot, fdisk).

## **/etc**
- Configuration files for system and services.
- Example: `/etc/passwd`, `/etc/ssh/sshd_config`

## **/opt**
- Optional or third-party software installations.

## **/home**
- Home folders for users.
- Example: `/home/john`

## **/root**
- Home directory for the root user.

## **/var**
- Variable files (logs, mail, caches).
- Example: `/var/log/syslog`

## **/usr**
- User-installed programs and libraries.

## **/tmp**
- Temporary files (auto deleted).

## **/lib**
- Shared libraries required by system programs.

## **/mnt**
- Temporary mount directory for external devices.

## **/media**
- Auto-mounted devices (USB, CDs).

## **/dev**
- Device files (hard drives, USB, etc).

## **/proc**
- Virtual directory with system and process info.

---

# 🔹 Types of Login Shells in Linux

## **1. bash (Bourne Again Shell)**
- Most common, default in many Linux systems.
- User-friendly.

## **2. sh (Bourne Shell)**
- Original shell, simple, basic script support.

## **3. ksh (Korn Shell)**
- Advanced scripting, powerful features.

## **4. nologin**
- Used to disable user login.
- Usually set for system/service accounts.

---

# ✅ Summary

This guide covered:

- System commands  
- Package managers (APT, YUM, DNF, Pacman, Portage)  
- User & group management  
- Linux directory structure  
- Login shells  

Use this as a simple reference while learning Linux.

---


