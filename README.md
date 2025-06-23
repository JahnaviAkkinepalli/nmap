# nmap
# Cyber Security Internship – Task 1

## 🔍 Task: Scan Local Network for Open Ports

### 🎯 Objective:
Use Nmap to find open ports in your local network and identify potential vulnerabilities.

---

### 🧰 Tools Used:
- Nmap v7.95
- Linux terminal

---

### 🖥️ My Network:
- IP Address: 192.168.245.128
- Subnet: 192.168.245.0/24

---

### 📥 Scan Command:
```bash
nmap -sS 192.168.245.0/24 -oN scan_result.txt
