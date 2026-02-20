# Scanning and Enumerating a Local Network using Nmap

## 📌 Objective
To perform SOC-style network reconnaissance and vulnerability assessment using Nmap.  
This project demonstrates practical skills in network discovery, port scanning, service/version detection, and vulnerability analysis.

---

## 🛠 Tools Used
- Nmap  
- Ubuntu Linux  
- VMware Workstation  

---

## 🔍 Lab Activities
- Network Discovery  
- Port Scanning  
- Service & Version Detection  
- Vulnerability Assessment  
- Result Documentation & Reporting  

---

## 💻 Commands Executed

```bash
nmap -sn 192.168.228.0/24
sudo nmap -sS 192.168.228.129
sudo nmap -sV 192.168.228.129
sudo nmap --script vuln 192.168.228.129
