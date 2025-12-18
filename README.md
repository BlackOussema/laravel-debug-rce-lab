# laravel-debug-rce-lab
Hands-on penetration testing lab exploiting a Laravel Debug RCE vulnerability in a controlled environment.
# Laravel Debug RCE – Penetration Testing Lab

## Overview
This repository documents a hands-on penetration testing lab where a
Remote Code Execution (RCE) vulnerability was exploited in a Laravel
application with debug mode enabled.

This project was conducted in a controlled and legal training environment.

---

## Environment
- Attacker Machine: Kali Linux
- Target: Vulnerable Laravel Application (Lab)
- Virtualization: VirtualBox
- Tool: Metasploit Framework

---

## Vulnerability
- Type: Remote Code Execution (RCE)
- Component: Laravel Debug / Ignition
- Impact: Command execution as web server user (www-data)

---

## Exploitation Summary
- Identified exposed Laravel debug endpoint
- Used Metasploit module:
  multi/php/ignition_laravel_debug_rce
- Obtained shell access with www-data privileges
- Performed basic post-exploitation enumeration

---

## Screenshot
![Exploitation Shell](screenshots/exploitation-shell.png)
![Exploitation Shell](screenshots/exploitation-shell.png2)

---

## Skills Practiced
- Web Application Security
- Metasploit Exploitation
- Linux Enumeration
- Ethical Hacking Methodology

---

## Disclaimer
This project is for educational purposes only.
No real-world systems were targeted.
