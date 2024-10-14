<h1>File Integrity Monitor (FIM) and Hashing Algorithms</h1>


 ### [For a detailed guide, check out the full Medium article.](https://medium.com/@lmb.walid/integriy-monitor-file-fim-and-hashing-algorithms-6eda8b77dce6)


<h2>Description</h2>
<b>This project implements a File Integrity Monitoring (FIM) system using hashing algorithms to ensure data integrity. The system monitors files by comparing their hash values to a previously recorded baseline. Any changes (creation, modification, or deletion) are detected and flagged, helping to prevent unauthorized access or corruption.</b>
<br />
Features:
Baseline Creation: Generates SHA-512 hashes for target files and stores them in baseline.txt.
File Monitoring: Continuously monitors files and alerts when changes are detected.
Notifications: Alerts if a file is created, modified, or deleted.


<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

<p align="center">
<img src="https://cdn-images-1.medium.com/max/800/1*hiFPocbSDgYouHA--PcC0g.png" height="85%" width="85%" alt="FIM Architecture Diagram"/>
</p>


