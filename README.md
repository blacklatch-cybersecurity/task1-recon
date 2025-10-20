---

## 📊 Findings (Short)
- Local VM IP **10.0.2.15** is up.  
- Scans show limited open ports — filtered by firewall or access control.  
- Evidence is saved in the `nmap/`, `wireshark/`, and `screenshots/` folders.

---

## 🧾 Evidence Files
- `nmap/nmap_filtered_reason.txt`
- `nmap/nmap_filtered_common_ports.txt`
- `wireshark/capture_local.pcap`
- `screenshots/nmap_terminal.png`
- `screenshots/wireshark_icmp.png`

---

## 🛡️ Short Remediation Suggestions
1. If hosts are intentionally filtered, document the firewall or segmentation policy.
2. If services should be reachable, adjust firewall rules or allow specific ports.
3. Verify host-based firewall and router ACLs.
4. Disable unnecessary services and update network access lists regularly.

---

## 👤 Author
**Name:** Balamurugan  
**Date:** October 20, 2025  
---

## 💻 Git Commands Used (Project Workflow)

These are the exact commands used during the creation and upload of this project.

### 🔹 Repository Setup
```bash
git init
git remote add origin https://github.com/blacklatch-cybersecurity/task1-recon.git
git branch -M main

