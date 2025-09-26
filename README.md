# Setup-and-Used-a-Firewall-on-Windows

## 📌 Objective
Configure and test basic firewall rules to allow or block traffic on Windows Firewall 

---

## 🛠 Tools Used
- Windows Firewall with Advanced Security  
- Telnet

---

## ⚡ Steps Performed
1. Opened firewall configuration tool.  
2. Listed current firewall rules.  
3. Added a rule to block inbound traffic on **port 23 (Telnet)**.  
4. Tested the rule using `telnet localhost 23` → connection failed (blocked).    
6. Removed test rule to restore original state.  

---

## 📷 Screenshots
- Telnet test result (connection blocked)  

---

## 📝 Summary
Firewalls filter network traffic by allowing or blocking connections based on defined rules.  
In this project, Telnet (port 23) was blocked successfully, demonstrating how firewalls secure systems from unauthorized access.  

---
