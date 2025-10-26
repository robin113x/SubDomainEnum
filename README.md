# 🌐 DNS Subdomain OSINT Scanner

![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-blue?logo=github)

🔗 [SubDomainEnum](https://robin113x.github.io/SubDomainEnum/)
 
A lightweight, web-based **passive reconnaissance tool** designed to discover subdomains using **public and free OSINT sources** — without making active or intrusive requests.  
Perfect for **bug bounty hunters**, **pentesters**, and **security researchers** who want quick, passive intelligence gathering.

---

## 🚀 Features

- 🔍 **Passive Enumeration Only** — avoids direct contact with the target domain.
- 📚 **Integrates Multiple Free OSINT Sources** (crt.sh, VirusTotal, SecurityTrails, DNSDumpster, etc.)
- ⚡ **No API Key Required** for most lookups.
- 💾 **Export Results** to text.
- 🌈 **Clean, Lightweight UI** with light theme and instant results.
- 🔐 **Client-side scanning** — no data stored or sent to any server.

---

## 🕵️ OSINT Sources Used

| Source | Description |
|---------|-------------|
| [crt.sh](https://crt.sh/) | Enumerates subdomains from SSL certificate transparency logs |
| [DNSDumpster](https://dnsdumpster.com/) | Public DNS recon and mapping service |
| [VirusTotal](https://www.virustotal.com/) | Retrieves domain relations from malware and scans |
| [SecurityTrails](https://securitytrails.com/) | Historical DNS and domain intelligence |
| [ThreatCrowd](https://www.threatcrowd.org/) | Community-driven threat intelligence data |
| [Shodan](https://www.shodan.io/) | Internet-exposed device search engine |
| [Censys](https://censys.io/) | Internet-wide scanning and enumeration |
| [AlienVault OTX](https://otx.alienvault.com/) | Threat intelligence and passive DNS |
| [ViewDNS.info](https://viewdns.info/) | WHOIS and DNS record lookup |
| [RapidDNS](https://rapiddns.io/) | Fast passive subdomain lookup |
| [Riddler.io](https://riddler.io/) | Passive subdomain discovery database |
| [BuiltWith](https://builtwith.com/) | Tech stack and hosting fingerprinting |
| [Hunter.io](https://hunter.io/) | Email-based domain reconnaissance |

---

## 🧠 How It Works

1. User enters a **target domain** (e.g., `example.com`)
2. The tool queries multiple **passive OSINT sources** in the background.
3. Results are **merged and deduplicated** in the browser.
4. Displayed in a clean, copyable format — or exported for further analysis.

---

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **UI Framework:** Custom lightweight layout
- **Security:** No backend interaction — fully client-side
- **Output Formats:** Plain text, CSV, JSON

---
