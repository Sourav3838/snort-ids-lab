# snort-ids-lab
Snort IDS custom rule lab for detecting ICMP and TCP SYN scan attacks in a controlled environment.

## Overview
This project demonstrates how custom Snort IDS rules were created and tested to detect common network attacks such as ICMP ping scans and TCP SYN scans.

## Lab Setup
IDS Host: Ubuntu with Snort running in IDS mode  
Attacker: Kali Linux  
Tool: Snort IDS  

## Procedure
Snort was installed and configured on Ubuntu in IDS mode.  
Custom Snort rules were created in the local.rules file to detect ICMP ping activity and TCP SYN scan attempts.  
Attack traffic was generated from Kali Linux using ping and nmap.  
Snort alerts were monitored in real time through the console to validate detection accuracy.

## Findings
ICMP ping activity successfully triggered Snort alerts.  
TCP SYN scan attempts were detected by the custom rule.  
Alerts confirmed correct rule logic and traffic matching.  
Snort effectively detected both attack patterns in real time.

## Skills Demonstrated
Snort IDS installation and configuration  
Custom IDS rule creation  
ICMP and TCP scan detection  
Network traffic analysis  
SOC-style alert monitoring

## Screenshots
All screenshots related to rule creation, attack simulation, and alert detection are included in the screenshots directory.

## Disclaimer
This project was conducted in a controlled lab environment for educational purposes only.
