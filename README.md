&lt;div align="center"&gt;

# 🔐 CyberSec Lab

**Browser-Based Interactive Cybersecurity Training Simulator**

[![Showcase](https://img.shields.io/badge/3MTT-NextGEN%20Knowledge%20Showcase%202.0-1a7f37?style=for-the-badge)](https://3mtt.nitda.gov.ng/)
[![Fellow](https://img.shields.io/badge/Fellow-FE%2F26%2F4246539238-0969da?style=for-the-badge)](https://3mtt.nitda.gov.ng/)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Site-ea4aaa?style=for-the-badge)](https://adamanuhu-star.github.io/cybersec-lab/)
[![License](https://img.shields.io/badge/License-MIT-d29922?style=for-the-badge)](LICENSE)

&lt;/div&gt;

---

## 🎯 What is CyberSec Lab?

**CyberSec Lab** is a lightweight, interactive cybersecurity training simulator that transforms theoretical curriculum concepts into hands-on browser-based demonstrations. It was built as a **personal educational project** to bridge the gap between classroom theory and real-world practice.

Built as a **single HTML file** with zero dependencies, it requires **no installation**, **no internet** (after first load), and runs on **any device** with a modern web browser — making cybersecurity education accessible even in low-connectivity environments.

&gt; **Curriculum Attribution:** The theoretical concepts explored in this lab are derived from the *3MTT NextGEN Cybersecurity Curriculum* (Federal Ministry of Communications, Innovation & Digital Economy, Nigeria). This project represents my own independent practical implementation and interpretation of those learning objectives.
&gt;
&gt; ⚠️ *Disclaimer: This is an independent student portfolio project. It is not affiliated with or endorsed by 3MTT, NITDA, or the Federal Ministry of Communications, Innovation & Digital Economy.*

---

## ✨ Why This Matters

| Challenge | How CyberSec Lab Solves It |
|---|---|
| 🚫 **Expensive lab software** | Runs entirely in the browser — completely free |
| 🐢 **Low connectivity** | Single-file, offline-capable after first load |
| 💻 **No access to VMs** | No virtual machines or installations required |
| 📵 **Limited devices** | Works on phones, tablets, and low-spec laptops |
| ⚠️ **Risk of breaking real systems** | 100% simulated — zero risk to real networks |

---

## 🧪 Lab Modules

The lab covers **5 interactive domains** mapped to the 3MTT Cybersecurity Curriculum:

### 1. 🔒 Cryptography *(Module 4)*
- **Hash Generator** — Real-time SHA-256 (Web Crypto API) and MD5 hashing with avalanche effect demonstration
- **Caesar Cipher** — Interactive symmetric encryption with adjustable shift key
- **Password Entropy Checker** — Live strength scoring with improvement suggestions

### 2. 🌐 Network Scan *(Modules 2, 6, 7)*
- **Simulated Port Scanner** — Nmap-style reconnaissance with realistic results and color-coded risk levels
- **Protocol Analyzer** — Side-by-side comparison of secure vs. insecure protocols (HTTP/HTTPS, Telnet/SSH, FTP/SFTP)

### 3. 👤 Access Control *(Module 5)*
- **RBAC Matrix** — Visual permission table demonstrating the Principle of Least Privilege
- **MFA Flow** — Interactive three-factor authentication simulation (something you know, have, and are)

### 4. 🐛 Vulnerabilities *(Modules 6–7)*
- **OWASP Top 10** — Expandable guide with real-world descriptions and mitigation strategies
- **Risk Calculator** — Likelihood × Impact matrix for vulnerability severity assessment

### 5. 🚨 Incident Response *(Module 8)*
- **Phishing Playbook** — Step-by-step NIST SP 800-61 decision tree with scoring
- **CIA Triad Explorer** — Interactive breakdown of Confidentiality, Integrity, Availability, and Non-repudiation

---

## 🚀 Try It Now

### Option 1: Live Demo
👉 **[Open CyberSec Lab](https://adamanuhu-star.github.io/cybersec-lab/)**

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/adamanuhu-star/cybersec-lab.git

# Navigate to the folder
cd cybersec-lab

# Open in browser (or use Live Server)
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
