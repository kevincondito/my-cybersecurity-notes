# My Cybersecurity Notes 🚀

Welcome to my repository! I am a 17-year-old aspiring **Penetration Tester**, and this space serves as my digital logs. Here, I document simplified notes, useful commands, and cheat sheets based on my learning journey through **Hack The Box Academy**.

My goal is to document my technical growth step-by-step and build a solid, organized, and quick-to-reference knowledge base.

---

## 📌 Modules & Notes Index

*   **[Module 1: SSH Fundamentals & Remote Connections](./01-ssh-fundamentals.md)**
    *   *Description:* Simplified explanation of SSH, key-based authentication, and shell stability versus reverse shells.
*   **[Module 2: VPN & Project Organization](./02-vpn-and-organization.md)**
    *   *Description:* How to securely connect to HTB labs using OpenVPN and set up organized folder structures for assessments.
*   **[Module 3: Networking, Ports, and OWASP Top 10](./03-networks-and-owasp.md)**
    *   *Description:* Core concepts of TCP/UDP ports, shell types (Reverse, Bind, Web), and an introduction to web vulnerabilities.

---

## 🛠️ Quick Cheat Sheet (Frequent Commands)

### Connecting to the VPN
```bash
sudo openvpn username.ovpn
```

### Remote Access via SSH
```bash
ssh username@TARGET_IP
```

### Initial Port Scanning (Nmap)
```bash
nmap -sV -sC -p- TARGET_IP
```
