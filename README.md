# ScamSathi-AI-Web-Platform

# 🛡️ ScamSathi AI

## 🚨 The Problem

In India, over **₹7,000 Crores** is stolen from ordinary citizens every year through digital financial fraud. Every single day, millions of people — especially **senior citizens, parents, and students** — receive terrifying messages:

- *"Your electricity will be disconnected tonight at 9:30 PM..."*
- *"Your bank account is blocked. Verify immediately..."*
- *"Congratulations! You won ₹50,000. Pay ₹999 processing fee to claim..."*

**Existing tools fail them** because:
- Traditional scanners are opaque black-boxes that say "safe" or "unsafe" with **zero explanation**.
- Cloud-based tools **upload private chats** to external servers, violating user confidentiality.
- Technical jargon makes tools inaccessible to the **1.4 billion people who need them most**.

---

## ✅ The Solution

**ScamSathi AI** is a free, explainable, privacy-first cybersecurity companion that:

- 🧠 Detects phishing messages with **contextual heuristics in under 10ms**
- 🔗 Inspects dangerous links **100% offline** — zero network calls, zero malware risk
- 📷 Educates citizens about **camera-permission phishing traps** through an interactive sandbox
- 🔒 **Never stores** personal chats, phone numbers, or sensitive user data
- 📞 Bridges users directly to India's **1930 Cyber Crime Helpline**

---

## ✨ Features

### 📩 Module 1 — AI Phishing Message Detector
- Analyzes SMS, WhatsApp forwards, and email alerts for **10 psychological manipulation vectors**
- Detects: Manufactured Urgency · Account Suspension Threats · OTP/Credential Harvesting · Prize Scams · Advance-Fee Fraud · Job Scams · Institutional Impersonation
- **Smart Negation Engine:** Correctly identifies legitimate bank security advisories ("Bank will NEVER ask for OTP") and suppresses false positives
- Returns color-coded risk gauge (0–100) with **highlighted evidence in plain English**

### 🔗 Module 2 — 100% Offline URL Analyzer
- Deconstructs suspicious links purely via **offline string heuristics** — zero network requests
- Detects: Raw IP hostnames · Brand typosquatting (SBI, HDFC, IndiaPost...) · Deceptive `@` user-info syntax · Disposable/abused TLDs · URL shorteners · **Free tunnel abuse (CamPhish, Ngrok, Cloudflare Tunnel)** · Heavy percent-encoding · Non-standard ports
- **Zero malware risk** — the hacker's server is never contacted, canary tokens never triggered

### 📷 Module 3 — Camera Phishing Awareness Simulator
- **100% safe educational sandbox** — zero `getUserMedia` or hardware API calls (verified by automated tests)
- Interactive 4-stage walkthrough: Lure → Fake Webpage → Risk Breakdown → Defense Checklist
- Teaches users how "Digital Arrest" and webcam extortion traps work in real life
- Branching outcomes: simulating "Allow" vs "Deny" shows real-world consequences

### 📊 Community Threat Radar
- Anonymous, aggregated threat telemetry displayed on the dashboard
- **Privacy Guarantee:** Only threat category, risk score, and domain fragment stored — never raw user messages
- Auto-fallback in-memory buffer if MongoDB is offline — **application never crashes**

---
