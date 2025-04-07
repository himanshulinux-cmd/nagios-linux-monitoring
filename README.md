
---

### 📦 2. `nagios-linux-monitoring` – README

```markdown
# Nagios Linux Monitoring Setup (Automated)

A configuration-ready setup for Nagios Core to monitor Linux infrastructure efficiently, including host and service checks via plugins and NRPE.

## 🔧 Tech Stack
- Nagios Core
- Nagios Plugins
- NRPE (Remote Execution)
- Bash scripting
- CentOS / Ubuntu Linux

## 📁 Folder Structure
- `/configs/` – Nagios host/service definitions
- `/scripts/` – NRPE agent installer and automation scripts
- `/inventory.ini` – Inventory for automation (Ansible optional)

## 🚀 Key Features
- Monitors CPU, Memory, Disk, Load
- Host/Service alerting via email
- Custom threshold configuration
- NRPE-based remote monitoring

## 🤖 How to Use
1. Install Nagios Core on central monitoring server
2. Deploy NRPE on remote Linux hosts
3. Import host/service definitions from `/configs/`
4. Reload Nagios configuration

## 📷 Screenshots
*(Add if available)*

## 👨‍💻 Author
[Himanshu Kaushik – Linux Engineer | DevOps Enthusiast](https://www.linkedin.com/in/himanshulinux)
