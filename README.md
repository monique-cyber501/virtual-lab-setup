
# Virtual Home Lab Setup (Defensive Security Focus)

This project documents my first hands-on milestone in building a home lab tailored for blue team cybersecurity training. From configuring a Windows 10 virtual machine to setting isolated networking and a static IP, every step here reflects both technical learning and practical implementation.

---

##  Tools Used
- **VirtualBox** (host machine: Windows 11)
- **Windows 10 ISO** (manually downloaded via Microsoft official site)
- **Command Prompt / PowerShell**
- **Windows Network Settings GUI**

---

##  Key Accomplishments

### 1. Created a Local Virtualization Environment  
- Installed and configured **Oracle VirtualBox** on my Windows 11 laptop.  
- Tuned system settings to optimize VM performance for log analysis and packet capture in future simulations.

### 2. Installed Windows 10 as a Virtual Machine  
- Downloaded a clean **Windows 10 ISO image** directly from Microsoft.  
- Created and mounted a virtual hard disk and completed the OS installation from scratch.  
- Captured key installation steps.

### 3. Isolated the VM from Host Network (Security-Oriented)  
- Configured **internal network mode** in VirtualBox to keep the VM separated from my personal laptop and the public internet.  
- This isolation ensures safer malware-free analysis environments and follows blue team best practices for sandboxing.

### 4. Set a Static IP Address  
- Manually configured a static IP address on the Windows 10 guest machine for reliable identification during future log and packet capture simulations.  
- Used `ipconfig`, network adapter settings, and custom DNS setup.

---

## 📸 Screenshots


![Screenshot 2025-07-07 213901](https://github.com/user-attachments/assets/ce950b8e-0f79-40fd-9a2c-e44f6c567da4)
![Screenshot 2025-07-07 214949](https://github.com/user-attachments/assets/828c3303-a6f8-415f-86ae-643108db584c)
![Screenshot 2025-07-07 230913](https://github.com/user-attachments/assets/9ae7e849-f86e-4fd4-b7a3-71bf26127eca)
![edit](https://github.com/user-attachments/assets/12531ee6-df5b-48f1-933d-d4a460c64e4f)


---

##  Learning Reflections

Setting up this virtual machine was more than just an installation task — it required decision-making around security isolation, performance tuning, and future scalability.  
This environment is the base for continued hands-on labs in:
- Log analysis (Splunk)
- Network forensics (Wireshark)
- Threat simulation (Safe & educational environments only)

I’ll continue documenting each lab and milestone as I work toward becoming a skilled SOC Analyst with a focus on cloud and fintech security environments.

---

##  Next Steps
- Install and configure Splunk on Ubuntu (coming next).
- Create a snapshot of the clean Windows image for backup.
- Connect a second VM (Ubuntu) to simulate event logging.

