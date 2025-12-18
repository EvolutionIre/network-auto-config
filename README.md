# Automated Network Device Configuration

## 📌 Project Overview
Modern networks often consist of dozens or hundreds of devices that require consistent configuration and regular updates. Manual configuration is error‑prone, time‑consuming, and difficult to audit.  

This project provides a **fully automated workflow** to:
- Discover network devices
- Backup existing configurations
- Push standardized, template‑based configurations
- Validate applied changes
- Generate detailed deployment reports

By combining Python, Netmiko, NAPALM, Jinja2, and Pandas, this solution demonstrates how network automation can **reduce operational overhead, improve reliability, and enforce configuration standards** across multiple devices.

---

## 🎯 Objectives & Achievements
- **Automation of repetitive tasks** → Eliminate manual logins and CLI commands.
- **Configuration consistency** → Apply template‑based configs across devices to enforce standards.
- **Auditability** → Maintain backups and reports for compliance and troubleshooting.
- **Error reduction** → Validate changes automatically to catch misconfigurations early.
- **Scalability** → Easily extend to dozens or hundreds of devices with JSON/CSV inventory files.
- **Professional visibility** → Showcase reproducible workflows and measurable impact for recruiters.

---

## ⚙️ Prerequisites
- Python **3.10+**
- Install required libraries:
  ```bash
  pip install netmiko napalm jinja2 pandas


