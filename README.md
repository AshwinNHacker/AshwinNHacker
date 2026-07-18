<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2200&pause=700&color=F85149&center=true&vCenter=true&multiline=true&repeat=true&width=920&height=150&lines=%5B!%5D+NEW+ALERT+-+SEVERITY%3A+CRITICAL;SOURCE%3A+github.com%2Fvisitor+%7C+DEST%3A+ashwin-n%2Freadme;ANALYST+ASHWIN+N+HAS+PICKED+UP+THIS+TICKET...;STATUS%3A+INVESTIGATING+%E2%86%92+SCROLL+TO+VIEW+CASE+FILE" alt="incident banner" />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:F85149&height=140&section=header&text=CASE%20FILE%20%23001%20-%20ASHWIN%20N&fontColor=E6EDF3&fontSize=34&fontAlignY=38&animation=twinkling&desc=Security%20Operations%20%7C%20Threat%20Detection%20%7C%20DFIR&descAlignY=58&descSize=16"/>

</div>

<br>

<table align="center">
<tr>
<td align="center"><b>ANALYST</b></td>
<td align="center"><b>ORG</b></td>
<td align="center"><b>ROLE</b></td>
<td align="center"><b>CLEARANCE</b></td>
<td align="center"><b>STATUS</b></td>
</tr>
<tr>
<td align="center">Ashwin N</td>
<td align="center">Zero Defence Security</td>
<td align="center">Information Security Officer</td>
<td align="center">SOC ANALYST</td>
<td align="center">🟢 ONLINE — MONITORING</td>
</tr>
</table>

<div align="center">
<img src="https://img.shields.io/badge/TryHackMe-Global_%231_(2025)-0D1117?style=for-the-badge&labelColor=161B22&color=F85149"/>
<img src="https://img.shields.io/badge/Field_Deployment-Bahrain-0D1117?style=for-the-badge&labelColor=161B22&color=58A6FF"/>
<img src="https://img.shields.io/badge/Incidents_Handled-Classified-0D1117?style=for-the-badge&labelColor=161B22&color=A371F7"/>
</div>

---

## `case_notes.log`

```diff
+ Builds detection pipelines by day, breaks them on purpose by night.
+ Believes a system isn't secure until someone has tried to make it lie.
+ Runs on coffee, packet captures, and the smell of a clean SIEM dashboard.
- Does not trust a control until it has personally failed to bypass it.
```

> *Every log line tells a story. Most of them are boring. I'm here for the ones that aren't.*

---

## `$ tail -f /var/log/kill-chain.log` — how the story goes

<div align="center">

```
 RECON              WEAPONIZE            EXPLOIT              ANALYZE              DEFEND
   │                    │                    │                    │                    │
   ▼                    ▼                    ▼                    ▼                    ▼
┌────────┐         ┌──────────┐        ┌──────────┐        ┌──────────┐        ┌──────────┐
│ OSINT  │  ────▶  │ Payload  │ ────▶  │  Live    │ ────▶  │  DFIR /  │ ────▶  │  Detect  │
│ recon  │         │  & tool  │        │ engage-  │        │ triage & │        │  engin-  │
│ Shodan │         │  crafting│        │  ment    │        │ forensics│        │  eering  │
│ crt.sh │         │ Metasploit│       │ Burp/ZAP │        │ Volatility│       │ Sigma/   │
│ Maltego│         │ Impacket │        │ Nmap/FFUF│        │ Ghidra   │        │ YARA/Wazuh│
└────────┘         └──────────┘        └──────────┘        └──────────┘        └──────────┘
   red team ───────────────────────────────────────▶  purple / intel  ───────────▶  blue team
```

</div>

I move both directions on this chain on purpose — the best detections I write are the ones I know how to defeat.

---

## `$ GET /tickets?status=open` — featured incidents (projects)

<table align="center" width="100%">
<tr><td width="12%" align="center"><b>ID</b></td><td width="30%" align="center"><b>Case</b></td><td width="13%" align="center"><b>Severity</b></td><td width="45%" align="center"><b>Summary</b></td></tr>
<tr>
<td align="center"><code>INC-001</code></td>
<td align="center"><b>SOC-X</b></td>
<td align="center">🟠 High</td>
<td>Modular Security Operations Centre framework built on Wazuh + Kibana — detection rules, alerting, and triage in one deployable stack.</td>
</tr>
<tr>
<td align="center"><code>INC-002</code></td>
<td align="center"><b>DeepView Forensics</b></td>
<td align="center">🔴 Critical</td>
<td>AI-assisted digital integrity validation suite — flags tampering and inconsistency in digital evidence before it reaches a courtroom or a report.</td>
</tr>
<tr>
<td align="center"><code>INC-003</code></td>
<td align="center"><b>Cloud-Native Firewall AD</b></td>
<td align="center">🟠 High</td>
<td>Anomaly detection layer for cloud firewall telemetry — learns baseline traffic, flags the deviations that matter.</td>
</tr>
<tr>
<td align="center"><code>INC-004</code></td>
<td align="center"><b>Detection Pipelines</b></td>
<td align="center">🟡 Medium</td>
<td>Log-source-to-alert engineering — Sigma/YARA rule authorship, tuning for signal over noise.</td>
</tr>
<tr>
<td align="center"><code>INC-005</code></td>
<td align="center"><b>SOC Automation Scripts</b></td>
<td align="center">🟡 Medium</td>
<td>Tooling that removes the repetitive parts of a SOC shift so analysts spend time on the alerts that actually matter.</td>
</tr>
</table>

<div align="center"><sub>full case archive → pinned repositories below</sub></div>

---

## `$ nmap -sV --script=coverage-map arsenal/`

<sub>coloured by the role security teams actually use it for</sub>

<div align="center">

<img src="https://img.shields.io/badge/●-F85149?style=flat-square&labelColor=0D1117"/> Red Team &nbsp;&nbsp;
<img src="https://img.shields.io/badge/●-58A6FF?style=flat-square&labelColor=0D1117"/> Blue Team &nbsp;&nbsp;
<img src="https://img.shields.io/badge/●-A371F7?style=flat-square&labelColor=0D1117"/> Purple / Intel &nbsp;&nbsp;
<img src="https://img.shields.io/badge/●-D29922?style=flat-square&labelColor=0D1117"/> Cloud / Infra

<br><br>

![Burp Suite](https://img.shields.io/badge/Burp_Suite-161B22?style=for-the-badge&logo=burpsuite&logoColor=F85149&labelColor=0D1117)
![Metasploit](https://img.shields.io/badge/Metasploit-161B22?style=for-the-badge&logo=metasploit&logoColor=F85149&labelColor=0D1117)
![Nmap](https://img.shields.io/badge/Nmap-161B22?style=for-the-badge&logo=nmap&logoColor=F85149&labelColor=0D1117)
![BloodHound](https://img.shields.io/badge/BloodHound-161B22?style=for-the-badge&logoColor=F85149&labelColor=0D1117)
![Mimikatz](https://img.shields.io/badge/Mimikatz-161B22?style=for-the-badge&logoColor=F85149&labelColor=0D1117)
![Hashcat](https://img.shields.io/badge/Hashcat-161B22?style=for-the-badge&logo=hashcat&logoColor=F85149&labelColor=0D1117)

<br>

![Wazuh](https://img.shields.io/badge/Wazuh-161B22?style=for-the-badge&logo=wazuh&logoColor=58A6FF&labelColor=0D1117)
![Splunk](https://img.shields.io/badge/Splunk-161B22?style=for-the-badge&logo=splunk&logoColor=58A6FF&labelColor=0D1117)
![Elastic](https://img.shields.io/badge/Elastic_Stack-161B22?style=for-the-badge&logo=elastic&logoColor=58A6FF&labelColor=0D1117)
![Sysmon](https://img.shields.io/badge/Sysmon-161B22?style=for-the-badge&logoColor=58A6FF&labelColor=0D1117)
![Velociraptor](https://img.shields.io/badge/Velociraptor-161B22?style=for-the-badge&logoColor=58A6FF&labelColor=0D1117)
![Volatility](https://img.shields.io/badge/Volatility-161B22?style=for-the-badge&logoColor=58A6FF&labelColor=0D1117)
![Ghidra](https://img.shields.io/badge/Ghidra-161B22?style=for-the-badge&logoColor=58A6FF&labelColor=0D1117)

<br>

![Shodan](https://img.shields.io/badge/Shodan-161B22?style=for-the-badge&logo=shodan&logoColor=A371F7&labelColor=0D1117)
![Maltego](https://img.shields.io/badge/Maltego-161B22?style=for-the-badge&logoColor=A371F7&labelColor=0D1117)
![VirusTotal](https://img.shields.io/badge/VirusTotal-161B22?style=for-the-badge&logo=virustotal&logoColor=A371F7&labelColor=0D1117)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-161B22?style=for-the-badge&logoColor=A371F7&labelColor=0D1117)
![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-161B22?style=for-the-badge&logo=owasp&logoColor=A371F7&labelColor=0D1117)

<br>

![AWS](https://img.shields.io/badge/AWS-161B22?style=for-the-badge&logo=amazonaws&logoColor=D29922&labelColor=0D1117)
![Azure](https://img.shields.io/badge/Azure-161B22?style=for-the-badge&logo=microsoftazure&logoColor=D29922&labelColor=0D1117)
![Docker](https://img.shields.io/badge/Docker-161B22?style=for-the-badge&logo=docker&logoColor=D29922&labelColor=0D1117)
![Kubernetes](https://img.shields.io/badge/Kubernetes-161B22?style=for-the-badge&logo=kubernetes&logoColor=D29922&labelColor=0D1117)
![Terraform](https://img.shields.io/badge/Terraform-161B22?style=for-the-badge&logo=terraform&logoColor=D29922&labelColor=0D1117)

<br>

![Python](https://img.shields.io/badge/Python-161B22?style=for-the-badge&logo=python&logoColor=E6EDF3&labelColor=0D1117)
![Bash](https://img.shields.io/badge/Bash-161B22?style=for-the-badge&logo=gnubash&logoColor=E6EDF3&labelColor=0D1117)
![PowerShell](https://img.shields.io/badge/PowerShell-161B22?style=for-the-badge&logo=powershell&logoColor=E6EDF3&labelColor=0D1117)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-161B22?style=for-the-badge&logo=kalilinux&logoColor=E6EDF3&labelColor=0D1117)

</div>

---

## `$ cat active_investigations.txt`

<table align="center">
<tr>
<td width="50%" valign="top">

**Open**
- Cloud Security Architecture
- AI-Assisted Threat Detection
- Detection Engineering (Sigma/YARA)
- Threat Hunting Methodology

</td>
<td width="50%" valign="top">

**Open**
- Security Automation
- Digital Forensics & Incident Response
- Purple Teaming
- Open Source Security Tooling

</td>
</tr>
</table>

---

## `$ gpg --verify clearance.sig`

<div align="center">

![ISC2](https://img.shields.io/badge/ISC²-161B22?style=for-the-badge&labelColor=0D1117&color=8B949E)
![EC-Council](https://img.shields.io/badge/EC--Council-161B22?style=for-the-badge&labelColor=0D1117&color=8B949E)
![Cisco](https://img.shields.io/badge/Cisco_Networking_Academy-161B22?style=for-the-badge&logo=cisco&logoColor=8B949E&labelColor=0D1117)
![IBM SkillsBuild](https://img.shields.io/badge/IBM_SkillsBuild-161B22?style=for-the-badge&logo=ibm&logoColor=8B949E&labelColor=0D1117)
![Microsoft Learn](https://img.shields.io/badge/Microsoft_Learn-161B22?style=for-the-badge&logo=microsoft&logoColor=8B949E&labelColor=0D1117)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-161B22?style=for-the-badge&logo=googlecloud&logoColor=8B949E&labelColor=0D1117)
![AWS](https://img.shields.io/badge/AWS-161B22?style=for-the-badge&logo=amazonaws&logoColor=8B949E&labelColor=0D1117)
![Harvard CS50](https://img.shields.io/badge/Harvard_CS50-161B22?style=for-the-badge&labelColor=0D1117&color=8B949E)
![TCM Security](https://img.shields.io/badge/TCM_Security-161B22?style=for-the-badge&labelColor=0D1117&color=8B949E)
![MeitY](https://img.shields.io/badge/MeitY_Govt._of_India-161B22?style=for-the-badge&labelColor=0D1117&color=8B949E)
![NHRC India](https://img.shields.io/badge/NHRC_India-161B22?style=for-the-badge&labelColor=0D1117&color=8B949E)

</div>

---

## `$ curl -s ranks.tryhackme.com/AshwinN | jq`

<div align="center">

| Platform | Standing |
|:--|:--|
| **TryHackMe** | 🥇 **Global Rank #1 — 2025** |
| Hack The Box | Active |
| PortSwigger Web Security Academy | Active |
| Let's Defend | Active |
| Hackviser Core | Active |
| PicoCTF / OverTheWire / Root Me / VulnHub / PentesterLab | Active |

</div>

---

## `$ GET /telemetry/github --live`

<div align="center">

<img width="80%" src="https://streak-stats.demolab.com?user=AshwinNHacker&hide_border=true&background=0D1117&ring=F85149&fire=58A6FF&currStreakLabel=F85149&sideLabels=8B949E&currStreakNum=E6EDF3&sideNums=E6EDF3&dates=8B949E"/>

<br><br>

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=AshwinNHacker&show_icons=true&hide_border=true&bg_color=0D1117&title_color=F85149&icon_color=58A6FF&text_color=E6EDF3"/>
<img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=AshwinNHacker&hide_border=true&bg_color=0D1117&color=8B949E&line=F85149&point=58A6FF"/>

<br><br>

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AshwinNHacker&layout=compact&hide_border=true&bg_color=0D1117&title_color=F85149&text_color=E6EDF3"/>

</div>

---

<div align="center">

<!-- easter egg for anyone reading raw markdown -->
<!-- TODO: rotate this API key before merging -->
<!-- (there is no key. nice try.) -->

## `$ nc -lvnp 443` — open a secure channel

[![LinkedIn](https://img.shields.io/badge/LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=58A6FF&labelColor=0D1117)](https://linkedin.com/in/ashwin-n-1-1-1-/)
[![Email](https://img.shields.io/badge/Email-161B22?style=for-the-badge&logo=gmail&logoColor=F85149&labelColor=0D1117)](mailto:ashwinnadaraj111@gmail.com)

<br>

```
> connection closed. session logged. ticket #001 → resolved.
> 0 alerts missed. 0 secrets leaked. see you at the next incident.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F85149,100:0D1117&height=90&section=footer"/>

</div>
