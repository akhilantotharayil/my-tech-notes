# Linux Networking Commands & Protocols — Simple Guide with Examples

This guide explains important Linux networking commands and protocols using **simple language**, along with **one example** each.

---

# 🔹 Linux Network Commands (With Examples)

## **1. ping**
Checks if another computer or website is reachable.
### Example:
ping google.com


---

## **2. traceroute**
Shows the path your data takes to reach a website.
### Example:
traceroute facebook.com


---

## **3. netstat**
Shows open ports and active network connections.
### Example:
netstat -tulpn


---

## **4. nmap**
Scans a device for open ports and services.
### Example:
nmap 192.168.1.10

---

## **5. tcpdump**
Captures and displays live network traffic.
### Example:
tcpdump -i eth0

---

## **6. ipconfig (Windows)**
Shows your IP address and network details.
### Example:
ipconfig

---

## **7. ifconfig (Linux)**
Displays your network interface information.
### Example:
ifconfig

---

## **8. dig**
Shows DNS records like IP addresses.
### Example:
dig google.com

---

## **9. nslookup**
Simple tool to look up DNS information.
### Example:
nslookup yahoo.com

---

## **10. host**
Finds the IP address of a domain.
### Example:
host example.com

---

# 🔹 Networking Protocols (With Examples)

## **1. FTP (File Transfer Protocol)**
Used to upload or download files.
### Example:
ftp ftp.example.com

---

## **2. SSH (Secure Shell)**
Secure remote login to another computer.
### Example:
ssh user@192.168.1.5
---

---

## **3. Telnet**
Remote login (not secure, no encryption).
### Example:
telnet 192.168.1.10 23

---

---

## **4. SMTP (Simple Mail Transfer Protocol)**
Used to send emails.
### Example:
telnet smtp.gmail.com 25

## **5. DNS (Domain Name System)**
Resolves domain names into IP addresses.
### Example:
dig google.com


---

## **6. DHCP (Dynamic Host Configuration Protocol)**
Automatically gives devices an IP address.
### Example:
sudo dhclient

---

## **7. HTTP (HyperText Transfer Protocol)**
Loads web pages (not encrypted).
### Example:
curl http://example.com


---

## **8. HTTPS (HyperText Transfer Protocol Secure)**
Loads secure and encrypted web pages.
### Example:
curl https://example.com


---

## **9. POP3 (Post Office Protocol v3)**
Downloads email from a server.
### Example:
telnet mail.example.com 110

---

## **10. NTP (Network Time Protocol)**
Synchronizes your computer's time with a server.
### Example:
sudo ntpdate time.google.com

---

## **11. SNMP (Simple Network Management Protocol)**
Monitors network devices like routers and switches.
### Example:
snmpget -v1 -c public 192.168.1.1 sysDescr.0

---

# ✅ Summary

This README covers:
- Basic network commands  
- Useful troubleshooting tools  
- Core internet protocols  
- Simple examples for each  

You can now use this file as a quick reference guide while learning Linux networking.

---



