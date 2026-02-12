# SOC-Home-Lab

Project Overview
- Designed and implemented a virtual SOC environment to simulate real-world network attacks and devlop detection capabilities using pfSense and Splunk.


Lab Architecture
- pfSense (Firewall and Logging)
- Kali Linux (Attacker)
- Ubuntu Server (Splunk Enterprise Host/Target)
- Windows 10 Machine (Admin machine)

Attack Simulations
1. Nmap Port Scan
   - Simulated reconnaisance
   - Observed multi-port scanning behavior
   - Created detection login in Splunk
2. SSH Brute Force
   - Enabled SSH on Ubuntu (Admin usage purposes)
   - Executed brute force attempts from Kali
   - Created brute force detection alert

Detection Engineering
- Provided in the Github repository is screenshots of my SPL used for the port scan detection and SSH Brute force attempts.

Skills Demonstrated
- Log ingestion, data parsing, and field extraction
- SPL Querying and correlation
- Firewall rule configuration
- Attack simulation
- Detection engineering fundamentals
- SOC Investigation workflow

Future Improvements
- Add DNS Monitoring
- Add Sysmon logs
- Create MITRE ATT&CK mapping
- Automate alert reporting
- Simulate a full incident response life-cycle

