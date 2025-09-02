# 🔍 Python Port Scanner

This is a simple Python script to scan open ports on a given host.  
It uses the built-in `socket` module to check if ports are open or closed.

---

## 📌 Features
- Scans a range of ports (default: 20–1024)
- Uses Python's `socket` module (no external dependencies)
- Easy to customize (change host or port range)

---

## 🚀 Usage

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

python port_scanner.py
Scanning scanme.nmap.org...

[+] Port 22 is OPEN
[-] Port 23 is CLOSED
[+] Port 80 is OPEN
[-] Port 443 is CLOSED

⚠️ Disclaimer

This tool is for educational purposes only.
Do not scan systems you don’t own or have explicit permission to test.
