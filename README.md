# SOC-Home-Lab
This project is a SOC-focused home lab simulating an enterprise network perimeter using pfSense and Splunk Enterprise SIEM. The lab focuses on centralized firewall log ingestion, search-time field normalization, and detection engineering for reconnaissance and targeted attack behavior. The goal is to gain hands-on experience with realistic SOC workflows rather than tool-only exposure.

Components:
- pfSense: Perimeter firewall and traffic enforcement
- Splunk Enterprise (Free): Centeralized log ingestion, analysis, and alerting
- Windows Admin Client - SOC Analyst workstation for pfSense and Splunk GUI
- Ubuntu Server - Splunk Host
- Kali Linux - Attacker VM

Network Layout
- WAN -> pfSense -> LAN (10.10.10.0/24)
- pfSense forwards syslogs to Splunk over UDP (Port 5514)
- Analyst access via Splunk Web UI

Tools and Technologies
- pfSense
- Splunk Enterprise (Free)
- VirtualBox
- Ubuntu Server
- Windows 10/11
- Kali Linux

Key Takeaways
- Practical experience with firewall telemetry
- Detection engineering in Splunk
- Understanding of SOC alert lifecycles
- Separation of enforcement (firewall) vs detection (SIEM)



