# 🐤 Rubber Ducky Payload: Stealth Payload Delivery & Execution

**Hackathon Submission by Team: Big Brain Coders**

This Rubber Ducky script demonstrates a proof-of-concept for stealthy payload delivery using PowerShell. It disables Windows Defender, downloads a payload from GitHub, and executes it silently — ideal for red teaming and cybersecurity demonstrations.

---

## 📌 Features

- ✅ Disables Windows Defender (Real-time Monitoring)
- ✅ Downloads `.exe` payload from a specified GitHub `raw` link
- ✅ Executes payload in stealth mode (`hidden` window)
- ✅ Minimal user interaction required
- ✅ Works on Windows targets with PowerShell enabled

---

## 📄 Ducky Script Flow

```plaintext
1. Open Run dialog
2. Launch elevated PowerShell
3. Disable Windows Defender
4. Download payload from GitHub to %TEMP%
5. Execute it silently


🚨 Disclaimer
This project is strictly for educational and ethical testing purposes (e.g., hackathons, red team simulations, and CTFs).
Do NOT use on unauthorized systems.


🧠 Team Members
Team Name: Big Brain Coders

Saubhagya Upadhyay
Yadu Bhatia
Tanishika Thakur
Vedansh Mishra


🛠️ Tools Used
Rubber Ducky

PowerShell

GitHub (for payload hosting)

Metasploit (for payload generation, optional)



🔐 Future Improvements
Memory-only payload execution (no file drop)

Real-time encrypted reverse shell

GUI obfuscation using trusted binaries (LOLBAS)**
