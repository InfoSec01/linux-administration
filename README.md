<div align="center">
<h1># 🛡️ Linux Administration: Real-World Skills for Secure & Reliable Systems</h1>
</div>

Welcome to the **Linux Administration** lab — a professionally built and documented guide through core system administration tasks that ensure security, reliability, and performance in any production environment.

This project isn't just academic—it's designed to demonstrate how I apply real-world Linux knowledge to protect business assets, optimize infrastructure, and support mission-critical operations.

---

## 📁 Contents

1. [👥 User & Group Management]
2. [📂 Filesystem Permissions]
3. [🔧 Services & Processes]
4. [🌐 Network Services]
5. [💾 Backup & Restore]
6. [📊 Centralized Logging & Monitoring]

---

## 👥 User & Group Management

Creating and managing users and groups ensures fine-grained access control to system resources.

- Set up multiple users and groups for secure role-based access.
- Assigned proper permissions using `usermod`, `groupadd`, and `chmod`.

> 🔽 **Screenshots:**

<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Users%20and%20Groups.png" width="50%"/>

---

## 📂 Filesystem Permissions

Controlled access to sensitive files and directories using Linux's robust permission system.

- Used `chown`, `chmod`, and `umask` to restrict access.
- Ensured only authorized users could modify or view specific files.

> 🔽 **Screenshots:**

<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Filesystem%20Access%20Control.png" width="50%"/>

---

## 🔧 Services & Processes

Managed and troubleshooted services to ensure high system uptime and performance.

- Monitored and restarted services using `systemctl`, `top`, and `ps`.
- Diagnosed memory and CPU usage by rogue processes.

> 🔽 **Screenshots:**

<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/apache2%20active%20status.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/firewalld%20active%20status.png" width="50%">
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/top%20CPU-consuming%20process.png" width="50%"/>  
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/htop%20PID%20743%20user%20student%20CPU%20100%25.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/kill%20%E2%80%939%20743%20PID%20743%20stopped.png" width="50%"/>

---

## 🌐 Network Services

Configured critical services like DHCP, DNS, and Apache.

- Set up DHCP and DNS for automated IP and domain resolution.
- Installed and configured Apache for web services.

> 🔽 **Screenshots:**

<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/DHCP%20configuration.png" width="50%"/> 
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/bind9%20restart%20and%20status.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Configure%20forward%20lookup%20zone%20phoenix.com.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/nslookup.png" width="50%"/>

---

## 💾 Backup & Restore

Simulated a business disaster-recovery scenario.

- Used `rsync`, `tar`, and `crontab` for scheduled backups.
- Configured SSH and key-based auth for secure remote backups.
- Created disk images using `dd` and mounted them for validation.

> 🔽 **Screenshots:**

<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Available%20Disk.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/copy%20of%20disk.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/backup%20img%20mounted%20to%20disk.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/compressed%20file%20created.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/file%20extracted%20in%20new%20directory%20.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Schedule%20rsync%20cron%20job.png" width="50%">
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/1%20minute%20file%20backup%20new-file.txt.png" width="50%">
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Backup%20folder%20created%20in%20server.png" width="50%">
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Templates%20folder%20backup%20actioned%20in%20client.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Templates%20folder%20backed%20up%20in%20server.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Create%20key%20pair%20on%20client%20machine.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Authorize%20key%20pair%20on%20server.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/Password-less%20SSH%20Auth.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/SSH%20to%20access%20server%20shell%20on%20client%20machine.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/local%20backup%20rsync.png" width="50%"/>

---

## 📊 Centralized Logging & Monitoring

Built a logging system to detect problems before they escalate.

- Configured `rsyslog`, `logrotate`, and `Logwatch` for log collection and summarization.
- Analyzed logs to identify anomalies and system misbehavior.

> 🔽 **Screenshots:**

<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/rsyslog%20installed%20status.png" width="50%"/> 
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/rsyslog%20config%20on%20server.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/client%20rsyslog%20configured.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/server%20rsyslog%20configured.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/log%20rotation%20config%20on%20server.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/log%20sent%20from%20client.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/log%20received%20on%20server.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/logrotate%20syslog%20output.png" width="50%"/>
<img src="https://github.com/InfoSec01/linux-administration/blob/main/screenshots/logwatch%20report%20mail.png" width="50%"/>

---

## 🎯 Why This Matters for Your Business

This lab showcases **production-ready Linux administration skills** that allow organizations to:

- Harden systems against internal and external threats
- Reduce downtime through smart service management
- Ensure compliance and audit-readiness via access control and logging
- Enable disaster recovery with automated, verifiable backups

---

## 🚀 Let’s Work Together

I bring not only technical ability, but understanding of operational impact. I continue to learn on building systems that work—securely, efficiently, and resiliently.

📬 **Contact**
- baratulkhan@gmail.com

---
