# 🌍 Vulnerability Analysis of "Earth: 1" VM – VulnHub

This repository documents a complete vulnerability assessment of the **"Earth: 1"** virtual machine, downloaded from [VulnHub](https://www.vulnhub.com/).

I scanned, analyzed, and reported vulnerabilities using industry-standard tools like **Nessus**, **Nmap**, and **BurpSuite**, followed by documentation with remediation steps.

---

## 🛠 Tools Used

- 🔎 **Nessus** – Vulnerability scanning
- 📡 **Nmap** – Port and service enumeration
- 🧪 **BurpSuite** – Web app vulnerability testing (optional)
- 🖥 **Earth VM** – From VulnHub (local virtual environment)

---

## 🗂 Files in This Repo

| File | Description |
|------|-------------|
| `nessus-earth-report.pdf` | Nessus scan output |
| `nmap-earth-scan.txt` | Raw Nmap output |
| `earth-analysis.pdf` | Final report with screenshots and vulnerability summary |
| `screenshots/` | All scan & testing screenshots |

---

## 📊 Summary of Findings

| Vulnerability | CVE ID | Severity | Suggested Fix |
|---------------|--------|----------|----------------|
| Apache Path Disclosure | CVE-XXXX-XXXX | Medium | Disable directory listing |
| SSH Weak Cipher | CVE-YYYY-YYYY | Low | Update SSH config |
| Outdated PHP Version | CVE-ZZZZ-ZZZZ | High | Upgrade PHP |

*(Actual CVEs based on your findings)*

---

## 📌 Learning Outcome

- Practiced professional scanning and enumeration
- Interpreted and validated vulnerability scan results
- Proposed real remediation steps
- Learned to combine Nessus + Nmap with analysis docs

---

## 👩‍💻 Author

**Anisha Goel**  
Cybersecurity Intern at KPMG | BTech IT Student  
📧 anishagoel2007@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/anisha-goel-05april2007)

---

## 🔜 Future Plans

- Analyze other VulnHub VMs (e.g., Mercury, Basic Pentesting)
- Explore Metasploit-based exploitation
- Create a beginner guide on running Nessus + Nmap
