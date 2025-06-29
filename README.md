# 🛡️ Cyber Security Learnings: Reconnaissance

Welcome to this educational repository about **Reconnaissance in Cyber Security**.

This repo is designed to help beginners understand **what reconnaissance is, why it matters, and how it is performed**.

---

## 🎯 What is Reconnaissance?

Reconnaissance (or **recon**) is the first phase of any penetration test or hacking activity.

**In simple terms:**
> Gathering information about a target before attempting any exploit.

---

## 🔍 Why is Reconnaissance Important?

✅ Discover **what systems are in scope**<br>
✅ Find **open ports and services**<br>
✅ Identify **potential vulnerabilities**<br>
✅ Plan your attack **efficiently**<br>
✅ Avoid **wasting time on blind attempts**

Also known as:
- **Information Gathering**
- **Footprinting**

---

## 🛠️ Types of Reconnaissance

### 1. Passive Reconnaissance
Gathering information **without directly interacting** with the target.

**Examples:**
- WHOIS lookups
- DNS enumeration
- Google dorking

### 2. Active Reconnaissance
**Directly probing the target system** to discover vulnerabilities.

**Examples:**
- Port scanning (e.g., with nmap)
- Banner grabbing
- OS fingerprinting

---

## 🧠 Common Tools for Recon

| Tool          | Purpose                            |
|---------------|------------------------------------|
| `nmap`        | Port scanning, service detection   |
| `netcat`      | Banner grabbing                    |
| `whois`       | Domain ownership info              |
| `theHarvester`| Email and subdomain collection     |
| `recon-ng`    | Modular reconnaissance framework   |

---

## ⚡ Example Recon Flow

1. **Identify live hosts** (e.g., `ping`, `nmap -sn`)
2. **Scan for open ports/services** (e.g., `nmap -sV`)
3. **Perform banner grabbing** (e.g., `netcat`, `telnet`)
4. **Search for domain and DNS info** (e.g., `whois`, `dig`)
5. **Gather emails/subdomains** (e.g., `theHarvester`)
6. **Organize and analyze** gathered intelligence

---

## ⚠️ Legal Disclaimer

This information is provided for **educational purposes only**.  
Do not attempt any reconnaissance without **explicit authorization**.

---

## 📚 Related Repositories

🔗 [SimpleReconScanner Tool](https://github.com/Stanley-blik/SimpleReconScanner)

---
