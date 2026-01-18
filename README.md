# OS-Security-Fundamentals
Operating System Security Fundamentals (Linux & Windows)



<img width="840" height="250" alt="Image" src="https://github.com/user-attachments/assets/21f5bb5c-87b0-4838-bf95-9c1e1cd1fa27" />






This project demonstrates Operating System Security Fundamentals for both Linux and Windows systems. It is designed as a hands-on cybersecurity project suitable






🎯 Objectives

Secure Linux and Windows operating systems

Apply least privilege principles

Reduce attack surface

Understand real-world OS hardening practices









🧰 Tools & Technologies

Ubuntu Linux (Virtual Machine)

Windows Defender Security

VirtualBox / VMware

Kali Linux (optional)



**🐧 Linux Security Implementation***


    1 Disabled direct root login

Used sudo for administrative tasks

    sudo adduser analyst
    sudo usermod -aG sudo analyst

**File Permissions**

    ls -l
    chmod 640 secure.conf
    chown root:root secure.conf
    
**Firewall (UFW)**

    sudo ufw enable
    sudo ufw allow ssh
    sudo ufw status
    
**Services & Processes**

    ps aux
    top
    systemctl list-units --type=service

**Logging**

   use  cat  to read 

    /var/log/auth.log
    /var/log/syslog


______________________________________________________________________________




**🪟 Windows Security Implementation
User Accounts***


Used standard user accounts

    Restricted administrator access

NTFS Permissions

    Removed unnecessary user permissions

Applied least privilege

    Windows Defender Firewall

Enabled firewall for all profiles

    Configured inbound and outbound rules

Services

    Disabled unnecessary startup services

Logging

    Event Viewer → Security Logs





