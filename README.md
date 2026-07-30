<div align="center">
🔐 CyberSec Lab
Browser-Based Interactive Cybersecurity Training Simulator
https://3mtt.nitda.gov.ng/
https://3mtt.nitda.gov.ng/
https://adamanuhu-star.github.io/cybersec-lab/
LICENSE
</div>
🎯 What is CyberSec Lab?
CyberSec Lab is a lightweight, interactive cybersecurity training simulator that transforms theoretical curriculum concepts into hands-on browser-based demonstrations. It was built as a personal educational project to bridge the gap between classroom theory and real-world practice.
Built as a single HTML file with zero dependencies, it requires no installation, no internet (after first load), and runs on any device with a modern web browser — making cybersecurity education accessible even in low-connectivity environments.
Curriculum Attribution: The theoretical concepts explored in this lab are derived from the 3MTT NextGEN Cybersecurity Curriculum (Federal Ministry of Communications, Innovation & Digital Economy, Nigeria). This project represents my own independent practical implementation and interpretation of those learning objectives.
⚠️ Disclaimer: This is an independent student portfolio project. It is not affiliated with or endorsed by 3MTT, NITDA, or the Federal Ministry of Communications, Innovation & Digital Economy.
✨ Why This Matters
Table
Challenge	How CyberSec Lab Solves It
🚫 Expensive lab software	Runs entirely in the browser — completely free
🐢 Low connectivity	Single-file, offline-capable after first load
💻 No access to VMs	No virtual machines or installations required
📵 Limited devices	Works on phones, tablets, and low-spec laptops
⚠️ Risk of breaking real systems	100% simulated — zero risk to real networks
🧪 Lab Modules
The lab covers 5 interactive domains mapped to the 3MTT Cybersecurity Curriculum:
1. 🔒 Cryptography (Module 4)
Hash Generator — Real-time SHA-256 (Web Crypto API) and MD5 hashing with avalanche effect demonstration
Caesar Cipher — Interactive symmetric encryption with adjustable shift key
Password Entropy Checker — Live strength scoring with improvement suggestions
2. 🌐 Network Scan (Modules 2, 6, 7)
Simulated Port Scanner — Nmap-style reconnaissance with realistic results and color-coded risk levels
Protocol Analyzer — Side-by-side comparison of secure vs. insecure protocols (HTTP/HTTPS, Telnet/SSH, FTP/SFTP)
3. 👤 Access Control (Module 5)
RBAC Matrix — Visual permission table demonstrating the Principle of Least Privilege
MFA Flow — Interactive three-factor authentication simulation (something you know, have, and are)
4. 🐛 Vulnerabilities (Modules 6–7)
OWASP Top 10 — Expandable guide with real-world descriptions and mitigation strategies
Risk Calculator — Likelihood × Impact matrix for vulnerability severity assessment
5. 🚨 Incident Response (Module 8)
Phishing Playbook — Step-by-step NIST SP 800-61 decision tree with scoring
CIA Triad Explorer — Interactive breakdown of Confidentiality, Integrity, Availability, and Non-repudiation
🚀 Try It Now
Option 1: Live Demo
👉 Open CyberSec Lab
Option 2: Run Locally
bash
# Clone the repository
git clone https://github.com/adamanuhu-star/cybersec-lab.git

# Navigate to the folder
cd cybersec-lab

# Open in browser (or use Live Server)
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
Option 3: Share Offline
Since it is a single file, you can:
Send via WhatsApp
Share via Bluetooth
Copy to a USB drive
Email as an attachment
🛠️ Tech Stack
Table
Layer	Technology
Structure	HTML5
Styling	CSS3 with CSS Variables (dark/light mode)
Logic	Vanilla JavaScript (zero frameworks)
Cryptography	Web Crypto API (SHA-256) + Custom MD5 implementation
Deployment	GitHub Pages
Key Technical Decisions:
Single-file architecture — Maximum portability and zero build steps
CSS Variables — Automatic dark/light mode theming
Web Crypto API — Native browser support for secure hashing
No external dependencies — Works completely offline
📸 Screenshots
Screenshots coming soon. The lab features a clean, responsive interface with tabbed navigation across all 5 modules.
plain
screenshots/
├── cryptography-tab.png
├── network-scan-tab.png
├── access-control-tab.png
├── vulnerabilities-tab.png
└── incident-response-tab.png
🌍 Deployment
GitHub Pages (Recommended)
Push this repository to GitHub
Go to Settings → Pages
Source: Deploy from a branch → main → / (root)
Click Save
Live at: https://adamanuhu-star.github.io/cybersec-lab/
Netlify / Vercel / Cloudflare Pages
Drag and drop index.html into any static hosting platform.
🤝 Contributing
This project is open for contributions. If you would like to add new modules or improve existing simulations:
Fork the repository
Create a feature branch: git checkout -b feature/new-module
Commit your changes: git commit -m 'Add: new simulation module'
Push to the branch: git push origin feature/new-module
Open a Pull Request
📄 License
This project is licensed under the MIT License — see the LICENSE file for details.
All simulations are safe and run entirely within the browser. No real networks, systems, or data are accessed.
👤 Author
Adama Nuhu
🎓 3MTT NextGEN Cybersecurity Fellow
🆔 Fellow ID: FE/26/4246539238
💻 GitHub: @adamanuhu-star
💼 LinkedIn: Adama Nuhu
🙏 Acknowledgments
3MTT Nigeria — Federal Ministry of Communications, Innovation & Digital Economy for the NextGEN Cybersecurity Curriculum that provided the theoretical foundation for this learning journey.
NIST — Cybersecurity Framework and SP 800-61 Incident Handling Guide
OWASP Foundation — OWASP Top 10 vulnerability classification
<div align="center">
Built for the 3MTT NextGEN Knowledge Showcase 2.0
<p><sub>Adama Nuhu · 3MTT NextGEN Fellow · ID: FE/26/4246539238</sub></p>
<p><sub>Independent educational project · Not affiliated with or endorsed by 3MTT/NITDA</sub></p>
<p><sub>Curriculum content © 3MTT Nigeria · Practical implementation © Adama Nuhu</sub></p>
</div>
