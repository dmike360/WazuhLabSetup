#<h1>Wazuh SIEM Lab</h1>

<h2>Description</h2>
Project activities include setting up wazuh lab, Accessing the Dashboard, Deploying Agents on Endpoints, integrating IDS/IPS tools, Logs/Alerts Analysis, Familiarizing with rules syntax, Group Organization, simulating an SSH bruteforce attack on endpoints carrying agents and Setting up Active Response to drop or block the attack
<br />


<h2> Tools Used</h2>

- <b>Suricata</b> 
- <b>Virus Total</b>
- <b>Hydra</b>
- <b>NMAP</b>

<h2>Environments Used </h2>

- <b>Wazuh OVA</b>
- <b>Ubuntu</b>
- <b>Kali Linux</b>

<h2>Project Activities performed & Images of its walk-through:</h2>

- <b>Deployed and configured Wazuh SIEM, setting up agents on Windows, Kali Linux, and Ubuntu to collect and analyze security alerts </b>

- <b>Familiarised myself with the Wazuh interface, modules and Navigation.</b>

- <b>Understood Rules syntax & Decoders</b> 

- <b>Created custom correlation rules to detect system and security-related alerts, enhancing threat detection.</b>
  
- <b>Simulated the presence of a malware file by downloading a test file from EICAR and Integrating VirusTotal to the Wazuh SIEM for advanced threat intelligence and malware analysis</b>

- <b>Configured NIDS (Suricata) for real-time network intrusion detection and monitoring, And integrated it to the Wazuh SIEM to get and Analyze network based Alerts on Agents.</b>

- <b>After integrating Suricata IDS/IPS, i Performed an NMAP OS, Ports discovery & using Decoy IPs scan on Kali agent using my Ubuntu VM to generate alerts on the Dashboard & Events page of my Kali Agent on Wazuh .</b>

- <b>File integrity monitoring (FIM) on my Wazuh Agents (Kali & Ubuntu VMs) </b>

- <b>Vulnerability Detection </b> 

- <b>And Finally configured Active Response in the configuration file of the Wazuh server to the "firewall-drop" command which I used to respond to a simulated SSH Brute force attack I performed on my Wazuh Agents </b>

<p align="center">
Wazuh Dashboard Overview: <br/>
<img src="https://i.imgur.com/VGtwN8i.png" height="80%" width="80%" alt="Wazuh Dashboard"/>
<br />
<br />
Wazuh Agents Overview:  <br/>
<img src="https://i.imgur.com/mOq6zCq.png" height="80%" width="80%" alt=" Wazuh Agents Overview"/>
<br />
<br />
Threat Hunting Events: <br/>
<img src="https://i.imgur.com/mJoQhSP.png" height="80%" width="80%" alt="Threat Hunting Events"/>
<br />
<br />
Vulnerability Detection Dashboard:  <br/>
<img src="https://i.imgur.com/JH2oxPJ.png" height="80%" width="80%" alt="Vulnerability Detection Dashboard"/>
<br />
<br />
File Integrity Monitoring Alerts:  <br/>
<img src="https://i.imgur.com/Tz7TFz4.png" height="80%" width="80%" alt="File Integrity Monitoring Alerts"/>
<br />
<br />
Installing Suricata Emerging Threats Rules:  <br/>
<img src="https://i.imgur.com/LIJ5XFW.png" height="80%" width="80%" alt="Installing Suricata Emerging Threats Rules"/>
<br />
<br />
Status of Suricata & Wazuh Agent<br/>
<img src="https://i.imgur.com/OnPEdsS.png" height="80%" width="80%" alt="Status of Suricata & Wazuh Agent"/>
<br />
<br />
NMAP OS & Decoy Scan:  <br/>
<img src="https://i.imgur.com/O8XgBxI.png" height="80%" width="80%" alt="NMAP OS & Decoy Scan"/>
  <br />
<br />
NMAP Scan Alert on Wazuh-Manager:  <br/>
<img src="https://i.imgur.com/8yYHdgK.png" height="80%" width="80%" alt="NMAP Scan Alert on Wazuh-Manager"/>
  <br />
<br />
Alerts Analysis:  <br/>
<img src="https://i.imgur.com/JXQnvFt.png" height="80%" width="80%" alt=Alerts Analysis"/>
  <br />
<br />
Brute Force Attack Simulation Using Hydra:  <br/>
<img src="https://i.imgur.com/fGnPolx.png" height="80%" width="80%" alt="Brute Force Attack Simulation Using Hydra"/>
  <br />
<br />
Active Response Alerts:  <br/>
<img src="https://i.imgur.com/mL040CP.png" height="80%" width="80%" alt="Active Response Alerts"/>
</p>
