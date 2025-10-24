# Defending the Network from a Simulated Attack

**Author:** John Tucker  
**Category:** Network Security | Incident Response | Penetration Testing  
**Date Completed:** July 2022  

---

## Project Overview
This project demonstrates a full incident response workflow using a simulated cyberattack environment. The objective was to identify, exploit, defend, and patch vulnerable systems using real-world tools such as Infection Monkey and Metasploit, followed by antivirus remediation and perimeter hardening.

The exercise focused on understanding how an attacker gains access to a network, how infections propagate, and how defenders can contain, remove, and prevent further compromise.

---

## Objectives
- Perform a simulated attack on a vulnerable web server using Infection Monkey.  
- Analyze exploit results and identify system weaknesses.  
- Use antivirus software to remove malicious files and restore system integrity.  
- Recreate a targeted exploit using Metasploit to simulate post-exploitation activities.  
- Patch and verify the vulnerability fix.  
- Harden the firewall to reduce attack surface.  
- Confirm mitigation success through additional exploit attempts and antivirus scans.

---

## Tools & Technologies
| Tool / Technology | Purpose |
|-------------------|----------|
| Infection Monkey | Simulated attack platform for testing network resilience |
| Metasploit Framework | Used to perform and verify exploitation on a vulnerable Linux target |
| pfSense Firewall | Hardened network perimeter after exploitation |
| Windows Defender / Antivirus | Detected and removed EICAR and simulated malware |
| Virtual Lab Environment | Controlled setup for simulation, analysis, and patch testing |

---

## Repository Contents
| File | Description |
|------|-------------|
| Defending the Network from a Simulated Attack.pdf | Full lab documentation, screenshots, and analysis |
| README.md | Project overview and summary for portfolio use |
| *(Optional)* /screenshots/ | Attack, defense, and patch verification captures |

---

## Procedure Summary

### 1. Simulated Attack
- Deployed Infection Monkey from MonkeyIsland to scan and exploit a web server (corporationtechs.com).
- Observed infection spread, confirmed the compromise, and reviewed the tool’s mitigation recommendations.

### 2. Malware Containment and Removal
- Identified infected files within the VIRUS directory.  
- Executed antivirus scans to isolate and delete malicious payloads.  
- Verified system health post-remediation.

### 3. Exploitation with Metasploit
- Configured and executed a targeted exploit on a Linux web server.  
- Achieved a remote shell session, confirming successful exploitation.  
- Captured exploit details and post-exploitation activities.

### 4. Patch and Verification
- Checked Bash version before and after patching.  
- Attempted the exploit again after the update and verified that it failed, confirming successful mitigation.

### 5. Perimeter Hardening
- Reviewed and updated firewall rules on the DMZ interface within pfSense.  
- Performed an antivirus scan on the workstation using Windows Defender, confirming detection of test malware (EICAR file).

---

## Skills Demonstrated
- Network defense and intrusion response  
- Penetration testing methodology  
- Patch management and vulnerability mitigation  
- Antivirus detection and malware removal  
- Firewall configuration and access control  
- Threat analysis and incident reporting  

---

## Results Summary
- Successfully simulated and analyzed multiple stages of a cyberattack.  
- Verified effectiveness of antivirus and firewall controls.  
- Patched exploited systems and confirmed they were no longer vulnerable.  
- Strengthened the network perimeter through updated firewall rules.  

---

## Key Takeaways
- Simulated attacks help validate the effectiveness of defense mechanisms.  
- Patching and layered security are critical for long-term protection.  
- Continuous monitoring and testing are essential for maintaining resilience.  

---

## License
This project is provided for educational and professional portfolio purposes.  
All simulations were performed in a controlled lab environment and did not involve live production systems.

---

