# 🌍 Earth VM – Vulnerability Analysis using Nessus & Nmap

This is a basic vulnerability analysis of the **Earth: 1 VM** from VulnHub. The goal was to identify open services, scan for vulnerabilities using **Nessus**, and manually investigate using **Nmap**.

---

## 🔧 Tools Used

- **Nessus** – Vulnerability Scanner
- **Nmap** – Network & Port Scanner
- **Earth VM** – Test machine from VulnHub

---

## 🧾 What This Repo Contains

| File | Description |
|------|-------------|
| `nessus-earth-report.pdf` | Full Nessus scan |
| `nmap-results.docx` | Scan notes and screenshots |
| `screenshots/` | Separate saved images from the scans |

---

## 📌 Key Vulnerabilities Identified

| Vulnerability | Tool Detected | Severity |
|---------------|----------------|----------|
| Outdated SSH service | Nmap | Medium |
| Apache 2.2 with Directory Listing | Nessus | High |
| PHP version with known CVEs | Nessus | High |

*Note: These are examples — replace with your actual findings.*

---

## 🎯 Learning Outcome

- Practiced scanning a VM using Nessus
- Performed manual enumeration with Nmap
- Identified and interpreted real vulnerabilities
- Improved documentation using screenshots + reporting

---

## 👩‍💻 About Me

**Anisha Goel**  
Cybersecurity Intern @ KPMG | Exploring Offensive Security  
📧 anishagoel2007@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/anisha-goel-05april2007)

---

## 🔜 Next Steps

- Try running BurpSuite on Earth’s web port (if any)
- Explore exploiting low-hanging CVEs manually
- Document more VulnHub VMs in a similar format
