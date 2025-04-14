# soc-home-lab-project
Hands-on SOC Analyst Home Lab: Threat simulation, detection engineering, and endpoint telemetry using Sliver C2, Sysmon, and LimaCharlie.

# 🛡️ SOC Analyst Cybersecurity Home Lab

This project is a full-fledged cybersecurity lab designed to simulate a real-world Security Operations Center (SOC) environment. Inspired by Eric Capuano's SOC Analyst Home Lab, this setup focuses on hands-on adversary emulation, endpoint telemetry, and detection engineering.

---

## 🔧 Lab Setup

- **Host System:** macOS (VMware Fusion)
- **Virtual Machines:**  
  - **Ubuntu Server 22.04** - Attacker VM  
  - **Windows 11** - Victim VM (Defender disabled)

---

## ⚔️ Key Components

### ▶️ Attack Simulation
- Used **Sliver C2 Framework** to generate and deploy custom malware payloads.
- Simulated attacker behavior: system enumeration, privilege checking, LSASS memory dumping.
- Delivered payloads using Python-based temporary web server.

### ▶️ Endpoint Telemetry
- Installed and configured **Sysmon** on the Windows VM.
- Integrated with **LimaCharlie** EDR for event collection and analysis.

### ▶️ Detection & Response Engineering
- Created custom **Detection & Response (D&R) rules**:
  - Detect LSASS access attempts
  - Alert on volume shadow copy deletion (common ransomware indicator)
  - Block malicious processes
- Utilized **YARA signatures** for malware identification in memory and on disk.

---

## 📊 Skills Demonstrated

- EDR & Telemetry Analysis
- Threat Hunting
- Malware Analysis
- Detection Rule Development
- YARA Signature Crafting
- Hands-on Adversary Simulation

---

## 📅 Project Timeline

- **Lab Build & VM Setup**
- **Telemetry Collection Configuration**
- **Adversary Emulation with Sliver C2**
- **Detection Rule Implementation**
- **YARA Rule Deployment & Testing**

---

## 🔍 Screenshots & Output

*(not-available)*

---

## 📂 Resources & Inspiration

- Eric Capuano's Home Lab Guide: [Link](https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro)
- Sliver C2: https://github.com/BishopFox/sliver
- Sysmon by Sysinternals
- LimaCharlie EDR Platform

---

## 📗 License

This project is intended for **educational and research purposes** only.

---

## 🚀 Connect With Me

**Nasarul Naseer**  
Cybersecurity Enthusiast | SOC Analyst in Training  
[Github](github.com/nasarul10)
[LinkedIn](linkedin.com/in/nasarulnaseer)

