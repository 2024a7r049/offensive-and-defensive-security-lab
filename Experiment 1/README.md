# Attack Simulation Using Nessus and Nmap

## Overview

This experiment demonstrates the use of **Nmap** and **Nessus** for network reconnaissance and vulnerability assessment in a controlled laboratory environment. Nmap is used to discover hosts, open ports, and running services, while Nessus is used to identify and analyze potential vulnerabilities.

## Objectives

* Perform network reconnaissance using Nmap.
* Identify open ports and running services.
* Perform vulnerability scanning using Nessus.
* Analyze vulnerabilities detected during the scan.
* Understand how attackers can use reconnaissance and vulnerability information.
* Understand defensive measures for reducing security risks.

## Tools Used

* **Nmap** – Network discovery and port scanning
* **Nessus** – Vulnerability assessment and scanning
* **Kali Linux** – Security testing environment
* **Metasploitable** – Intentionally vulnerable target machine

## Methodology

### 1. Network Scanning with Nmap

Nmap is used to discover the target system and identify its open ports and services.

Example:

```bash
nmap -sV <target-ip>
```

The scan provides information about:

* Open ports
* Running services
* Service versions
* Potential attack surface

### 2. Vulnerability Scanning with Nessus

The target system is added to Nessus as an authorized scan target. A vulnerability scan is then performed to identify known security weaknesses.

The results can include:

* Critical vulnerabilities
* High-risk vulnerabilities
* Medium-risk vulnerabilities
* Low-risk vulnerabilities
* Informational findings

 3. Attack Simulation

The information obtained from Nmap and Nessus can be used to understand how an attacker might identify and target vulnerable services.

The simulation is performed only against an intentionally vulnerable machine in the laboratory environment.

 4. Defensive Analysis

The identified vulnerabilities are analyzed and appropriate security measures are considered, such as:

* Disabling unnecessary services
* Updating vulnerable software
* Closing unnecessary ports
* Applying security patches
* Using firewalls
* Monitoring network activity

 Results

Nmap successfully identifies the target's exposed ports and services, while Nessus provides a detailed vulnerability assessment of the target system. The combined results demonstrate how reconnaissance and vulnerability assessment contribute to both offensive security testing and defensive security planning.

 Conclusion

This experiment provides practical understanding of how **Nmap and Nessus** can be used together for security assessment. It demonstrates the importance of identifying exposed services and vulnerabilities so that appropriate defensive measures can be implemented.
