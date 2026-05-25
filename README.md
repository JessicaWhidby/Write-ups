# CTF-Write-ups
OBJECTIVE -
I've been learning a lot through the use of online red and blue team labs, as well as setting up and using my own home lab. My goal is to learn new tools, deepen my understanding of others, and generally learn investigations.

TOOLS USED -</br>
Online gamified learning platforms</br>
Wazuh</br>
Volatility</br>
KQL/Azure Data Explorer</br>
Splunk</br>
Wireshark</br>
Zenmap</br>
Autopsy</br>
VirusTotal</br>
Linux command line</br>
Ubuntu, Kali, Windows Server, and Windows 10 VMs


Through Blue Team Labs Online (BTLO), I've learned to develop my defensive and investigative skills. I've learned how to explore VirusTotal to get a closer look at potential malware and brush up on open source intelligence (OSINT) digging. I've also learned to explore metadata, how to utilize Wireshark in new and different ways, how to analyze a phishing attempt via email header information, and dabbled in reading log files via Linux command line. Finally (so far), I learned how to read reports and parse for important information.

With CyberDefenders, I have learned a LOT about using Volatility. I walked through finding and investigating malware from a Windows machine using Volatility commands. I also ran through another PCAP/Wireshark investigation, this time focusing on revealing and piecing together an SQL injection (SQLi) attack.

KC7 has been one of my favorite platforms, as the gameification walks you through what could really have happened in an attack step-by-step. This platform, however, focuses on KQL querying to gather the information. I've run through phishing investigations, how to interpret PowerShell scripts being used maliciously, VirusTotal investigations, ransomware, how to recognize C2 beaconing, ICS compromise, and recognizing and investigating insider threats (including lateral movement).

LetsDefend also showed me more about phishing emails, and I'd like to explore the platform even further.

TryHackMe is one of the more popular platforms I have used. I also did an introduction to phishing there, this time using Splunk SIEM and triaging alerts as they came in. I also ran through a forensic investigation with Autopsy. Finally (thus far), I went through their Juicy Details CTF. This required lots of log analysis with a basic text editor to open the logs.

Finally, I'll discuss my home lab setup and practice. I have Kali, Ubuntu, Windows Server, and Windows 10 installed. I have them all on 1 virtual network, and Server is acting as an AD domain controller and DNS/DHCP/Remote access server. I added everything else to the AD domain and was able to sign in with the AD credentials. Once my network was going, I went to Kali and created a network map with Zenmap. Then, I set up Ubuntu as a Wazuh server and am in the process of running vulnerability scans on each host and remediating findings.
