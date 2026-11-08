<h1 align="center">Álvaro Marçal de Araujo</h1>

<p align="center">
  <strong>Infrastructure | DevOps | Networking | AI Systems</strong>
</p>

<p align="center">
  Network & Communications Engineering Student @ UnB <br>
  Computer Science Student @ UniCEUB <br>
  Brasília, DF, Brazil
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alvaro-marcal-dearaujo/">LinkedIn</a> |
  <a href="mailto:alvaromra2@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/51616bfb-7184-4919-ab29-cc72a41219dd" alt="Banner" width="100%">
</p>

---

# 👨‍💻 About Me

I build and operate infrastructure and AI systems. At Heiliger, I **cut deployment time from 2 hours to 15 minutes** with CI/CD pipelines (Jenkins and Ansible) on Red Hat OpenShift. On the AI side, I build RAG systems on local LLMs and automation workflows with n8n, and my undergraduate thesis is on Large Language Models (LLMs).

I study Network & Communications Engineering at the University of Brasília (UnB) and Computer Science at UniCEUB, and I contribute to extension projects in AI and digital accessibility.

Interested in Infrastructure and Platform Engineering, DevOps, Networking, Applied AI and Cybersecurity (including CTFs).

---

# 🚀 Featured Projects

## 📄 DocsScanAI: Local Document Intelligence Platform

Document scanning and analysis that runs **100% locally**: text is extracted, indexed on your machine and answered by an offline LLM through Ollama. Nothing is sent to external services, so it can handle sensitive documents such as contracts and resumes.

🔗 **Repository:** [github.com/Alvaromra/DocsScanAI](https://github.com/Alvaromra/DocsScanAI)

### Features
- Text extraction from PDF, DOCX, CSV, XLSX, TXT, JSON, HTML and logs
- Pattern detection (emails, CPF, CNPJ, phones, URLs, dates and monetary values)
- Language and entity recognition with spaCy (Portuguese and English)
- RAG question answering over your documents (lemma and character n-gram search, TF-IDF index, context sent to a local LLM)
- Export to CSV, XLSX, JSON, TXT, PDF and DOCX
- Custom model training pipeline with LoRA and GGUF conversion
- Flask web app with chat, FastAPI + PostgreSQL API and Docker Compose deployment

### Technologies
`Python` `FastAPI` `Flask` `PostgreSQL` `Docker` `Ollama` `RAG` `spaCy`

---

## 🔐 Facial Recognition Access Control (IoT)

Smart access control system using facial recognition and a distributed IoT architecture with edge computing.

> Repository coming soon.
<!-- TODO: publish the repository and add the link here -->

### Features
- Face recognition with DeepFace running at the edge
- ESP32-CAM image capture
- Smart lock control through the Tuya Cloud API (Intelbras IFR 7001)
- Flask web dashboard for monitoring, model training and device management

### Technologies
`Python` `DeepFace` `ESP32-CAM` `Flask` `Tuya Cloud API` `Edge Computing` `IoT`

---

## 🎵 Spotify PiP Lyrics: Real-Time Floating Lyrics Overlay

Desktop application that displays synchronized Spotify lyrics in a floating Picture-in-Picture (PiP) window, providing a lightweight and distraction-free music experience.

🔗 **Repository:** [github.com/Alvaromra/spotify-pip-lyrics](https://github.com/Alvaromra/spotify-pip-lyrics)

### Features
- Real-time Spotify playback detection
- Automatic lyrics synchronization
- Floating always-on-top PiP overlay
- Spotify OAuth authentication
- Cross-platform architecture (Windows, Linux and macOS)
- Electron-based desktop application
- Responsive and minimalist interface
- Automatic track change detection
- Local secure token management
- Multi-monitor support

### Technologies
`Electron` `Node.js` `JavaScript` `Spotify Web API` `OAuth 2.0` `HTML` `CSS`

---

## 🛡️ AlvSafe: Antivirus and Endpoint Protection

Antivirus and endpoint protection in Python, with a command line and a graphical interface. Educational and research project in defensive security, not a replacement for a commercial antivirus.

🔗 **Repository:** [github.com/Alvaromra/AlvSafe](https://github.com/Alvaromra/AlvSafe)

### Features
- On-demand file and folder scanning that combines known SHA-256 hashes, heuristics, YARA rules, entropy and optional VirusTotal into a threat score
- Real-time protection on monitored folders
- Ransomware behavior detection (write bursts and suspicious extensions)
- Neutralized quarantine with restore and integrity check
- Process and network connection monitors (alert only)
- Environment diagnostics with `alvsafe doctor`
- Linux and macOS support (Windows planned)

### Technologies
`Python` `YARA` `Watchdog` `VirusTotal API` `GitHub Actions`

---

## ♿ Exata Falada: AI & Digital Accessibility Platform

Academic extension project at UnB focused on making educational materials more accessible through Artificial Intelligence and assistive technologies.

**My role:** volunteer contributor, validating and testing the platform, including the accuracy of mathematical expression parsing and the structured HTML output used by assistive technologies.

### Features
- OCR-based document processing
- Accessible HTML generation
- Screen reader optimization
- ARIA implementation
- Text-to-Speech integration
- Mathematical content accessibility
- Accessibility validation workflows
- Educational inclusion support

### Technologies
`HTML` `CSS` `JavaScript` `OCR` `AI` `ARIA` `Accessibility`

---

## 🚌 Smart Bus Tracking System (Research Project)

Research concept focused on intelligent public transportation monitoring using emerging communication technologies and Artificial Intelligence.

### Features
- Real-time vehicle tracking
- GPS-based positioning
- Predictive arrival estimation
- Intelligent route analysis
- Smart city integration
- Future 6G connectivity support
- AI-assisted transportation analytics

### Technologies
`Python` `GPS` `AI` `Networking` `IoT` `6G`

---

# 🧰 Technical Skills

## Infrastructure & DevOps
- Linux
- Docker
- Docker Compose
- Kubernetes
- Ansible
- GitLab CI/CD
- Jenkins
- OpenShift
- Nginx
- Apache
- Git
- Bash

## AI & Automation
- Python
- LLMs and LLM architectures (Transformers, self-attention, embeddings, encoder and decoder models)
- Ollama
- RAG
- n8n
- TF-IDF
- GGUF
- LoRA
- Prompt Engineering

## Backend & Databases
- FastAPI
- Flask
- REST APIs
- GraphQL
- WSO2
- PostgreSQL
- SQLite
- MySQL
- JSON
- YAML

## Networking
- TCP/IP
- VLAN
- OSPF
- BGP
- DNS
- VPN
- Reverse proxies
- Firewalls (pfSense, iptables)
- Routing & Switching

## Security & Monitoring
- CTF (Capture the Flag)
- Kali Linux, Nmap, John the Ripper, Hashcat
- Wireshark, tcpdump
- Zabbix, Prometheus, Grafana

## Operating Systems
- Linux
- Ubuntu
- Debian
- Rocky Linux
- Windows Server

---

# 🏢 Experience

## Infrastructure, Networking & DevOps Intern
**Heiliger Tecnologia e Software**  
*Apr 2025 to Mar 2026*

- Cut deployment time from 2 hours to 15 minutes with CI/CD pipelines (Jenkins and Ansible), deploying on Red Hat OpenShift
- Automated provisioning of VPCs, VPNs, DNS and reverse proxies; supported Nginx, Apache, MySQL and JFrog environments
- Linux server administration, containerized services support and troubleshooting
- REST API integrations and WSO2 platform support
- Technical documentation

---

## AI Workflow Automation
**Pipefy** (remote)  
*Oct 2025*

- Built automation workflows and AI-integrated chatbots with n8n
- Customer Success chatbot using Google Sheets as the knowledge base
- Integrated Python scripts with GraphQL APIs

---

## Volunteer: Exata Falada Project (AI & Digital Accessibility)
**Universidade de Brasília (UnB)**  
*Apr 2026 to Present*

- Accessible HTML validation and accessibility testing
- OCR and AI-assisted workflows
- Semantic HTML and ARIA support
- Educational material adaptation

---

## Teaching Assistant: Computer Network Fundamentals
**Universidade de Brasília (UnB)**  
*Mar 2024 to Aug 2024 | Mar 2026 to Present*

- Created exercises and teaching materials
- Supported TCP/IP and network infrastructure classes, labs and review sessions

---

# 🎓 Education

## Universidade de Brasília (UnB)

**Bachelor's Degree in Network & Communications Engineering**

Expected Graduation: December 2027 | Undergraduate thesis on Large Language Models (LLMs)

---

## UniCEUB

**Bachelor's Degree in Computer Science**

Expected Graduation: 2028

---

# 📊 GitHub Statistics

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Alvaromra&show_icons=true&theme=tokyonight&count_private=true"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alvaromra&layout=compact&theme=tokyonight"/>
</p>

---

# 📚 Currently Learning

- Cloud Infrastructure
- AI Infrastructure
- Distributed Systems
- Platform Engineering
- MLOps
- Cloud-Native Architectures

---

# 🎯 Areas of Interest

- Infrastructure Engineering
- Platform Engineering
- DevOps
- Artificial Intelligence
- Networking
- Cybersecurity
- Cloud Computing
- Accessibility Technologies

---

# 📫 Contact

📧 alvaromra2@gmail.com

🔗 LinkedIn:
https://www.linkedin.com/in/alvaro-marcal-dearaujo/

💻 GitHub:
https://github.com/Alvaromra
