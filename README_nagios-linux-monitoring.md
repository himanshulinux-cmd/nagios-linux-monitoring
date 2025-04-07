
# Linux Monitoring with Nagios

A full-fledged Nagios monitoring setup to track system health, service status, and performance metrics across Linux infrastructure.

## 📌 Tech Stack
- Nagios Core
- NRPE
- Bash Scripting
- Linux (Ubuntu/CentOS)

## 🔧 Features
- Monitor disk, CPU, memory, and web services
- Email alerts on thresholds
- Host groups and contact templates
- NRPE agent setup on remote clients

## 🏗️ Architecture
```bash
[Nagios Server] ---> [NRPE Client 1]
                 ---> [NRPE Client 2]
                 ---> [NRPE Client N]
```

## 🚀 Setup Steps
1. Install Nagios on master node
2. Install NRPE on monitored nodes
3. Define hosts in nagios.cfg
4. Add checks for services in commands.cfg

## 📂 Folder Structure
```
configs/
├── hosts.cfg
├── services.cfg
├── commands.cfg
scripts/
├── check_disk.sh
├── check_cpu.sh
```

## 📈 Outcome
- Proactive monitoring and alerting system
- Reduced downtime and faster incident response
