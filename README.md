# ITECH1502 Cybersecurity Fundamentals - Final Project: Cybersecurity Portfolio

## Project Title
**Mastering Network Reconnaissance: An In-Depth Port and Service Discovery using Nmap**

---

## 🚀 Project Overview

This project serves as the capstone assessment for the Federation University ITECH1502 Cybersecurity Fundamentals unit, demonstrating my ability to apply theoretical knowledge and practical skills. This portfolio acts as a career-ready showcase to strengthen my professional profile for internships or entry-level cybersecurity roles.

**Training Platform:** TryHackMe
**Challenge Room:** Nmap
**Core Topic:** Network Reconnaissance & Fundamental Vulnerability Scanning

---

## 🎯 Project Goal/Objectives

By completing the TryHackMe challenge, the project aimed to achieve the following:

1.  **Master Advanced Nmap Usage:** Learn and successfully apply advanced Nmap scan types, such as the SYN scan (`-sS`), and understand port range specification.
2.  **Accurate Service Identification:** Utilize Nmap's version detection feature (`-sV`) to accurately identify the service names and version numbers running on the target host's open ports.
3.  **Consolidate Foundational Skills:** Translate classroom theory into real-world skills, strengthening the ability to utilize tools for information collection.

---

## 🛠️ Methodology

The practical activity strictly followed a systematic network reconnaissance process, primarily using the **Nmap** tool.

1.  **Target Setup & Connection:** Register using the FedUni email and connect to the TryHackMe virtual machine environment.
2.  **Port Discovery (Stealth Scan):**
    * **Tool:** Nmap
    * **Command Example:** `nmap -sS <Target_IP>`
    * **Objective:** Use the stealthy SYN scan (`-sS`)—a faster and more inconspicuous method than a full TCP connect scan—to identify open ports.
3.  **Service and Version Detection:**
    * **Tool:** Nmap
    * **Command Example:** `nmap -sV -p <Ports> <Target_IP>`
    * **Objective:** Use version detection (`-sV`) to acquire precise service names and version numbers running on open ports, a crucial step for vulnerability identification.
4.  **Evidence Collection & Analysis:** Carefully analyse the Nmap output to extract necessary information, and collect screenshots of the work, including the FedUni email for verification.

---

## 🔍 Outcomes & Key Findings

* **Skill Achievement:** Successfully applied Nmap's `-sS` and `-sV` parameters to accurately complete all network reconnaissance tasks on the target host.
* **Evidence:** 
* **Conclusion:** This practice activity successfully consolidated my understanding of the reconnaissance process and the application of basic security measures and tool utilization skills.

---

## 🧠 Reflection & Professional Growth

| Dimension | Reflection Summary | Unit Learning Outcomes (LO) |
| :--- | :--- | :--- |
| **Learning Outcomes** | Gained a deep understanding of Nmap's core parameters (`-sS`, `-sV`) and their role in discovery vs. version identification. This practical work provided intuitive insight into the underlying TCP/IP protocol behavior during scanning. | LO S2: Utilise tools for vulnerability scanning and basic penetration testing. |
| **Professional Growth** | **Blue Team Perspective:** Mastering Nmap helps me evaluate systems from an attacker's perspective, enabling me to better suggest mitigation strategies (A2) and apply basic security measures (A1). This experience strengthens my career-ready showcase. | LO A1 & A2: Apply cybersecurity measures to real-world scenarios and analyze case studies to suggest mitigation strategies. |
| **Future Improvements** | If repeated, I would integrate the Nmap Scripting Engine (`-sC`) to run automated checks against specific services (e.g., HTTP) to move beyond pure discovery into basic vulnerability assessment. | Addresses the reflection question on what would be done differently if the task were repeated. |

---

