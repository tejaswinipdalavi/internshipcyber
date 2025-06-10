# Cybersecurity Internship – Task 1: Port Scanning with Nmap

##  Objective
The goal of this task was to learn basic network reconnaissance by scanning the local network for open ports using Nmap.

---

## Tools Used
- **Nmap** for scanning local IP range
- **Wireshark** *(optional)* for analyzing packet captures

---

##  IP Range Scanned
My local IP range: `192.168.1.0/24`

---

##  Command Used
```bash
nmap -sS 192.168.1.0/24 -oN scan_results.txt
# internshipcyber
