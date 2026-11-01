# Hi, I'm Vladislav Guliakin

**Aspiring SOC Tier 1 analyst** in Miami, currently an AV Technical Specialist at the Miami-Dade County Courts. I investigate malware traffic in packet captures, enrich indicators with threat intelligence, and write up each case the way a SOC ticket should read: evidence first, every claim backed by a filter and a frame number.

**Certifications:** CompTIA Security+ · Cisco CCNA · Microsoft SC-200 (in progress)

**Languages:** English, Russian

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vguliakin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vguliakin/)
[![Website](https://img.shields.io/badge/Website-vguliakin.dev-222222?logo=googlechrome&logoColor=white)](https://vguliakin.dev)

## Featured work

| Project | What it is |
|---|---|
| [**malware-traffic-analysis**](https://github.com/dancemonk/malware-traffic-analysis) | Network forensics writeups. First case: a FormBook/XLoader infection, with 15 C2 domains (9 missed by the IDS), likely data exfiltration, defanged IOCs and MITRE ATT&CK mapping. |
| [**ioc-enrich**](https://github.com/dancemonk/ioc-enrich) | Lookup-only IOC enrichment for SOC triage. Paste the indicators from an alert, see what public threat-intel sources report, export to CSV. Python, no dependencies. |
| [**vulnbrief**](https://github.com/dancemonk/vulnbrief) | One-command CVE briefing from NVD, CISA KEV and FIRST EPSS, cached in SQLite. Python, tested in CI. |

## Skills and tools

- **Network analysis:** Wireshark, tshark, PCAP triage, HTTP/DNS/Kerberos/SMB/DHCP analysis
- **Threat intelligence:** VirusTotal, abuse.ch (ThreatFox, URLhaus, MalwareBazaar), whois/RDAP, IOC defanging
- **Frameworks:** MITRE ATT&CK, incident triage and response
- **Hunting:** pivoting on behavior (User-Agent, URI patterns), not only on alerts
- **Code:** Python, Bash, Git
- **Lab:** isolated Ubuntu VM for malware traffic, nothing run on the host

## Currently

- Working through [malware-traffic-analysis.net](https://www.malware-traffic-analysis.net/) exercises, one full writeup per case
- Open to **SOC Analyst (Tier 1)** roles
