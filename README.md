<div align="center">

# 🛡️ AstraCRS

**An AI-Powered Cyber Reasoning System for Autonomous Vulnerability Discovery, Patching & Verification**

Built for [AI Kavach 2026](https://aikavach.in) — A Data-Centric Innovation Challenge for Defence & National Security

---

![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Runs%20On-Single%20Laptop-blueviolet?style=flat-square)
![Internet](https://img.shields.io/badge/Internet-Not%20Required-critical?style=flat-square)

</div>

---

## 📌 What Is This?

Military and defence software must be bulletproof. A single undetected vulnerability can become an open door for cyber adversaries — leading to data theft, system disruption, or worse.

**AstraCRS** is an AI-powered security assistant that automates the entire vulnerability lifecycle:

> **Find the bug → Fix the bug → Prove the fix works**
> 
> All on its own. All on a single laptop. No internet required.

It combines proven security testing tools with modern AI code understanding to deliver a system that is practical, trustworthy, and field-deployable in sensitive defence environments.

---

## ⚙️ How It Works

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│   SOFTWARE   │────▶│  CODE SCAN   │────▶│ STRESS TEST  │────▶│   AI FIX     │────▶│   VERIFY     │
│   SOURCE     │     │ Flag risky   │     │ Find real    │     │ Write a      │     │ Prove fix    │
│   CODE       │     │ code areas   │     │ crashes      │     │ targeted     │     │ works, no    │
│              │     │              │     │              │     │ repair       │     │ regressions  │
└──────────────┘     └──────────────┘     └──────────────┘     └──────────────┘     └──────┬───────┘
                                                                                          │
                                                                                          ▼
                                                                                   ✅ SECURED
                                                                                   SOFTWARE
```

| Step | What Happens | In Simple Terms |
|:----:|--------------|-----------------|
| **1. Scan** | Reads source code and flags areas that look risky | Like a spell-checker, but for security flaws |
| **2. Stress-Test** | Throws thousands of inputs at risky areas to find real crashes | Like crash-testing a car to find weak points |
| **3. AI Fix** | AI model analyses the crash, understands the root cause, writes a precise repair | Like a mechanic diagnosing the issue and writing a repair order |
| **4. Verify** | Replays the exact attack to confirm it's fixed, runs all tests to check nothing else broke | Like re-crash-testing the car after repair + full safety inspection |

**Key principle:** The system only reports *confirmed, reproducible* crashes. Zero guesswork. Zero false alarms.

---

## 🎯 What Makes AstraCRS Different

Most approaches to this problem stop at "find the bug" or "suggest a fix." AstraCRS goes further:

### 🔴 Danger-Level Triage
Not all bugs are equally dangerous. AstraCRS automatically ranks each vulnerability by real-world exploitability:

| Level | Meaning |
|-------|---------|
| 🔴 **Critical** | Reachable remotely over a network — could allow system takeover |
| 🟠 **High** | Crashes when processing external data — denial-of-service risk |
| 🟡 **Medium/Low** | Requires local access or unlikely conditions to trigger |

Decision-makers get a **prioritised action list**, not an unsorted wall of technical jargon.

### 📋 Officer-Readable Reports
For every vulnerability found and fixed, the system generates a **plain-language threat summary** that any commanding officer can read and act on — no software background needed.

```
╔══════════════════════════════════════════════════════════════╗
║  ⚑ AstraCRS — Vulnerability Report                         ║
╠══════════════════════════════════════════════════════════════╣
║  Module:        Message handling subsystem                  ║
║  Finding:       Crafted network message crashes the system  ║
║  Danger Level:  🔴 CRITICAL — remotely exploitable          ║
║  Fix Applied:   Input size validation added to parser       ║
║  Verification:  ✅ Attack replayed — crash resolved.        ║
║                 ✅ All system tests pass.                   ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🛠️ Tech Stack

| Component | Tool | Purpose |
|-----------|------|---------|
| Code Scanning | Semgrep, Tree-sitter | Open-source security scanners |
| Stress Testing | AFL++, AddressSanitizer | Automated crash-finding |
| AI Code Understanding | Ollama + Open-source Models | Runs entirely offline on laptop GPU |
| Verification | Crash Replay + Test Harness | Automated pass/fail validation |
| Orchestration | Python | Connects all components |
| Deployment | Docker | Packages system into one portable unit |

**Hardware needed:** A standard laptop with a mid-range GPU. No servers. No cloud. No internet.

---

## 🗺️ Roadmap

| Feature | Status |
|---------|--------|
| Core scan → fix → verify pipeline | 🔧 In development |
| Danger-level triage | 🔧 In development |
| Officer-readable threat reports | 🔧 In development |
| Fix re-stress-testing (attack the repair itself) | 📋 Planned |
| Binary analysis (no source code needed) | 📋 Planned |
| Pattern learning across projects | 📋 Planned |
| Web dashboard for real-time monitoring | 📋 Planned |

---

## 📄 Documentation

- [Project Abstract (PDF)](AstraCRS%20%E2%80%94%20Project%20Abstract%20_%20AI%20Kavach%202026.pdf) — Detailed project overview and methodology

---

## 👥 Team

> Team details will be updated here.

<!--
- **Team Lead:** [Name] — [Role]
- **Member 2:** [Name] — [Role]
- **Member 3:** [Name] — [Role]
-->

---



<div align="center">

**Built for AI Kavach 2026 🇮🇳**

*A Data-Centric Innovation Challenge for Defence & National Security*

</div>
