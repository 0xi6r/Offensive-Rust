# Offensive-Rust

# Why malware in Rust?
I guess to level your adversarial game

- **What is malware?**
 a malicious program
 Types: trojans, ransomware, rootkits, worms,  etc.
- **Malware goals:** Persistence, privilege escalation, lateral movement, data exfiltration
- **Windows Internals:** Registry, processes, services, APIs

#### 📚 Resources:
- Book: *The Art of Memory Forensics* – Lays foundational knowledge.
- Book: *Practical Malware Analysis* – Great for understanding static/dynamic analysis.
---

### 🧰 **Basic Malware Development**
Goal: Write basic malware functionality and understand detection and evasion techniques.

#### 💻 POC
  - Keylogger
  - Reverse shell
  - Persistence (registry, startup folder, services)
- Static vs dynamic evasion (packers, obfuscation)

#### 🧪 Practice:
- Build your own:
  - Dropper (downloads and executes payload)
  - Binder (binds malware to legit file)
  - C2 client/server using HTTP or DNS # actually don't reinvent the wheel, use sliver/adaptix
---

### 👾 ** Advanced Malware Development**
Goal: stealth, advanced delivery, and bypassing modern defenses.
