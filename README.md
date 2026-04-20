## Tools Used
- Elasticsearch 9.1
- Kibana 9.1
- Logstash 9.1
- Filebeat 9.1
- Kali Linux (VMware)
- Metasploitable2 (Victim VM)
- Hydra (Brute Force)
- Nmap (Network Recon)
- VMware Workstation

## What I Built

### Phase 1 - SIEM Deployment
- Deployed ELK Stack 9.1 on Kali Linux VM
- Configured Filebeat to ship auth and syslog to Elasticsearch
- Set up SSL authentication between Filebeat and Elasticsearch

### Phase 2 - Attack Simulation
- Simulated SSH brute force attack using Hydra
- Generated 7,326+ failed login attempts
- Performed network reconnaissance using Nmap on Metasploitable2
- Identified 22 open ports and critical vulnerabilities
- Exploited bindshell vulnerability gaining root access on Metasploitable2

### Phase 3 - Detection & Monitoring
- Detected attacks in real time using Kibana Discover
- Created custom dashboards showing attack timeline
- Built saved searches for failed login detection
- Monitored 98+ syslog events in real time

### Phase 4 - Automated Alerting
- Configured Kibana detection rule "SSH Brute Force Alert"
- Rule triggers when failed logins exceed 5 in 5 minutes
- Alert actively triggered with 197 failed attempts detected
- Rule runs every 1 minute for continuous monitoring

## Key Results
| Metric | Value |
|--------|-------|
| Total security events captured | 7,326+ |
| Failed login attempts detected | 197 in 5 mins |
| Open ports discovered on victim | 22 ports |
| Detection rule response time | 1 minute |
| Alert status | Active & Triggered |
## Tools Used
- Elasticsearch 9.1
- Kibana 9.1
- Logstash 9.1
- Filebeat 9.1
- Kali Linux (VMware)
- Metasploitable2 (Victim VM)
- Hydra (Brute Force)
- Nmap (Network Recon)
- VMware Workstation

## What I Built

### Phase 1 - SIEM Deployment
- Deployed ELK Stack 9.1 on Kali Linux VM
- Configured Filebeat to ship auth and syslog to Elasticsearch
- Set up SSL authentication between Filebeat and Elasticsearch

### Phase 2 - Attack Simulation
- Simulated SSH brute force attack using Hydra
- Generated 7,326+ failed login attempts
- Performed network reconnaissance using Nmap on Metasploitable2
- Identified 22 open ports and critical vulnerabilities
- Exploited bindshell vulnerability gaining root access on Metasploitable2

### Phase 3 - Detection & Monitoring
- Detected attacks in real time using Kibana Discover
- Created custom dashboards showing attack timeline
- Built saved searches for failed login detection
- Monitored 98+ syslog events in real time

### Phase 4 - Automated Alerting
- Configured Kibana detection rule "SSH Brute Force Alert"
- Rule triggers when failed logins exceed 5 in 5 minutes
- Alert actively triggered with 197 failed attempts detected
- Rule runs every 1 minute for continuous monitoring

## Key Results
| Metric | Value |
|--------|-------|
| Total security events captured | 7,326+ |
| Failed login attempts detected | 197 in 5 mins |
| Open ports discovered on victim | 22 ports |
| Detection rule response time | 1 minute |
| Alert status | Active & Triggered |

## Screenshots
| Screenshot | Description |
|------------|-------------|
| ELK_1 | Kibana Discover showing failed logins |
| ELK_2 | Hydra brute force attack running |
| ELK_3 | Kibana dashboard with attack timeline |
| ELK_4 | SSH Brute Force Alert rule triggered |
| ELK_5 | Nmap scan results on Metasploitable2 |

## Skills Demonstrated
- SIEM deployment and configuration
- Log shipping and management
- Real time threat detection
- Attack simulation and penetration testing
- Network reconnaissance
- Automated alerting and rule creation
- Linux system administration
- VMware virtualization

## Resume Statement
Built enterprise-grade SIEM home lab using ELK Stack 9.1,
simulated real attacks including SSH brute force and network 
scanning, detected 7,326+ security events and configured 
automated Kibana alerting rules that actively triggered 
when attack thresholds were exceeded.
