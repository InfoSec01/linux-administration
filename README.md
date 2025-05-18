# 🛡️ Linux Administration: Real-World Skills for Secure & Reliable Systems

Welcome to the **Linux Administration** lab — a professionally built and documented guide through core system administration tasks that ensure security, reliability, and performance in any production environment.

This project isn't just academic—it's designed to demonstrate how I apply real-world Linux knowledge to protect business assets, optimize infrastructure, and support mission-critical operations.

---

## 📁 Contents

1. [👥 User & Group Management](#user--group-management)
2. [📂 Filesystem Permissions](#filesystem-permissions)
3. [🔧 Services & Processes](#services--processes)
4. [🌐 Network Services](#network-services)
5. [💾 Backup & Restore](#backup--restore)
6. [📊 Centralized Logging & Monitoring](#centralized-logging--monitoring)

---

## 👥 User & Group Management

Creating and managing users and groups ensures fine-grained access control to system resources.

- Set up multiple users and groups for secure role-based access.
- Assigned proper permissions using `usermod`, `groupadd`, and `chmod`.

> 🔽 **Screenshots:**

![User Group](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Users%20and%20Groups.png)

---

## 📂 Filesystem Permissions

Controlled access to sensitive files and directories using Linux's robust permission system.

- Used `chown`, `chmod`, and `umask` to restrict access.
- Ensured only authorized users could modify or view specific files.

> 🔽 **Screenshots:**

![Permission Settings](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Filesystem%20Access%20Control.png)

---

## 🔧 Services & Processes

Managed and troubleshooted services to ensure high system uptime and performance.

- Monitored and restarted services using `systemctl`, `top`, and `ps`.
- Diagnosed memory and CPU usage by rogue processes.

> 🔽 **Screenshots:**

![Systemctl Status](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/top%20CPU-consuming%20process.png)  
![Process Check](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/htop%20PID%20743%20user%20student%20CPU%20100%25.png)
![Process Check](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/kill%20%E2%80%939%20743%20PID%20743%20stopped.png)

---

## 🌐 Network Services

Configured critical services like DHCP, DNS, and Apache.

- Set up DHCP and DNS for automated IP and domain resolution.
- Installed and configured Apache for web services.

> 🔽 **Screenshots:**

![DHCP Setup](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/DHCP%20configuration.png)  
![DNS Config](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/bind9%20restart%20and%20status.png)
![DNS Config](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Configure%20forward%20lookup%20zone%20phoenix.com.png)
![DNS Config](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/nslookup.png)

---

## 💾 Backup & Restore

Simulated a business disaster-recovery scenario.

- Used `rsync`, `tar`, and `crontab` for scheduled backups.
- Configured SSH and key-based auth for secure remote backups.
- Created disk images using `dd` and mounted them for validation.

> 🔽 **Screenshots:**

![SSH Setup](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/SSH%20to%20access%20server%20shell%20on%20client%20machine.png)  
![Rsync Backup](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/local%20backup%20rsync.png)  
![Cronjob Config](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Schedule%20rsync%20cron%20job.png)
![Cronjob Config](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/1%20minute%20file%20backup%20new-file.txt.png)

---

## 📊 Centralized Logging & Monitoring

Built a logging system to detect problems before they escalate.

- Configured `rsyslog`, `logrotate`, and `Logwatch` for log collection and summarization.
- Analyzed logs to identify anomalies and system misbehavior.

> 🔽 **Screenshots:**

![Logwatch Setup](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/server%20rsyslog%20configured.png)
![Logwatch Setup](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/logrotate%20syslog%20output.png)
![Logwatch Setup](https://github.com/InfoSec01/linux-administration/blob/main/screenshots/logwatch%20report%20mail.png)

---

## 🎯 Why This Matters for Your Business

This lab showcases **production-ready Linux administration skills** that allow organizations to:

- Harden systems against internal and external threats
- Reduce downtime through smart service management
- Ensure compliance and audit-readiness via access control and logging
- Enable disaster recovery with automated, verifiable backups

---

## 🚀 Let’s Work Together

I bring not only technical ability, but a deep understanding of operational impact. I build systems that work—securely, efficiently, and resiliently.

📬 **Contact me if your organization needs someone who can walk the talk in System, Linux, and Network Administration.**

---
