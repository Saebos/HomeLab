# 🧪 Cybersecurity HomeLab  
**Hands-on practice with real-world attacks and detection**

##  Why I Built This?
I wanted a safe and practical way to learn cybersecurity — not just through theory, but by doing. This HomeLab gives me the space to test real attack scenarios, watch how systems react, and learn how to detect and defend against them using tools like Splunk, Sysmon, and Metasploit. It’s helping me grow both red and blue team skills.

---

##  What I'm Learning

- **Virtualization & Networking**
  - Spinning up Kali Linux, Windows 10, and Ubuntu VMs in VirtualBox
  - Creating NAT networks for safe, isolated communication

- **Threat Simulation**
  - Crafting payloads with `msfvenom`
  - Delivering them via HTTP and gaining reverse shells using Metasploit

- **Detection & Analysis**
  - Installing Sysmon on Windows to collect logs
  - Using Splunk or Wazuh on Ubuntu to visualize and analyze security events

- **Troubleshooting & Debugging**
  - Fixing common issues like bad payloads, incorrect IPs, and blocked ports
  - Learning by solving real problems

---

##  How I Set It Up

1. **Virtual Machines**
   -  Kali Linux – Attacker machine  
   -  Windows 10 – Victim machine  
   -  Ubuntu – Log server running Splunk or Wazuh

2. **Logging & Visibility**
   - Installed **Sysmon** on Windows to monitor system activity
   - Forwarded logs to the SIEM for central monitoring

3. **Simulating an Attack**
   - Generated a malicious `.exe` using `msfvenom`
   - Delivered it via a Python HTTP server
   - Established a reverse shell with Metasploit’s handler

4. **Analyzing in the SIEM**
   - Searched for Indicators of Compromise (IOCs)
   - Looked for suspicious process creation, RDP access, and network traffic

5. **Lessons Learned**
   - Every mistake (and there were quite alot!) helped me understand more about networking, detection, and how real attackers operate in real situations.

---
