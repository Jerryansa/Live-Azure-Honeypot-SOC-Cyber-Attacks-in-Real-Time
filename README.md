# Live Azure Honeypot & SOC: Cyber Attacks in Real Time(Lab)
 ![SIEM Topology](https://imgur.com/Ue5OzUS.png)<br>

## Project Overview

- Objective: Showcase the effectiveness of best security practices, incident response strategies, and enhancements to the environment.
- Methodology: Establishing a small-scale honeynet on Microsoft Azure.
- Attracting Threats: Intentionally deploying vulnerable virtual machines without internet safeguards to draw in real-world attackers globally.
- Data Gathering: Using Log Analytics Workspace for collecting pertinent logs.
- Analysis Tool: Employing Microsoft Sentinel to generate attack maps, alerts, and incidents.


## Tools used in Lab(Microsoft)

- Azure Virtual Network (VNet)
- Virtual Machines (Windows)
- Log Analytics Workspace with Kusto Query Language (KQL) Queries
- Azure Key Vault 
- Azure Storage Account 
- Microsoft Sentinel 
- Microsoft Defender for Cloud
- Powershell


## Walkthrough

 - In this lab, we intentionally designed it to draw attention from the public internet. The Virtual Machines had their built-in firewall settings turned off, allowing unrestricted access from any source. Furthermore, additional assets like storage accounts and databases were configured with public endpoints, exposing them to the internet without the implementation of Private Endpoints for enhanced security. The purpose of this lab is to extract security logs and generate an attack map based on those logs.
 <br />
 
 
 
![Windows RDP/SMB Auth Failures](https://i.imgur.com/Vo4cCCh.png)<br>

<b>This attack map shows RDP and SMB failures against the Window machine.</b>

 <br />
 <br />
 
 


## Conclusion
The Live Azure Honeypot & SOC lab underscored the importance of robust security practices. Deliberately exposing vulnerable virtual machines attracted real-world attackers, revealing insights via Microsoft Sentinel's attack map. The data emphasizes the need for proactive measures, including proper firewall configurations and endpoint protection. Lessons learned will enhance ongoing cybersecurity efforts, stressing continuous monitoring and adaptive responses to evolving threats. This project serves as a call to action for the adoption of cybersecurity best practices. The visualization of an attack map highlights unauthorized access attempts, providing valuable insights into potential vulnerabilities.
