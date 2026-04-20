# ELK Stack SIEM Home Lab

## Overview
Built a home SIEM lab using ELK Stack 9.1 to detect
and analyze security threats in real time.

## Tools Used
- Elasticsearch 9.1
- Kibana 9.1
- Filebeat 9.1
- Kali Linux
- VMware Workstation
- Hydra
- Nmap

## What I Built
1. Deployed ELK Stack on Kali Linux VM
2. Configured Filebeat to ship auth and system logs
3. Simulated SSH brute force attack using Hydra
4. Generated 7,326+ security events
5. Detected threats in real time using Kibana
6. Created custom Kibana dashboards and saved searches

## Attack Simulation
- Tool: Hydra
- Target: SSH localhost port 22
- Result: 7,326 failed login attempts detected
- Detection: Real time in Kibana Discover

## Screenshots
See screenshots folder for evidence

## Skills Demonstrated
- SIEM deployment and configuration
- Log analysis and threat detection
- Security monitoring and alerting
- Attack simulation and detection
- Linux administration
