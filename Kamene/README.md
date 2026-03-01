# Kamene

Packet crafting + sniffing playground built on top of **Scapy**.  
Goal: a clean, hackable lab repo for learning and building small network tools (scanner, ARP spoof, DNS sniff, etc.) without drowning in boilerplate.

> Status: early-stage. Repo structure is being stabilized.

---

## What this is
- A project wrapper around **Scapy** to build:
  - packet sniffers
  - packet builders / fuzzers
  - small network utilities (LAN discovery, port scan helpers, protocol probes)
- A learning + experimentation repo: readable code > “framework”.

---

## Requirements
- Python 3.10+ (recommended)
- Npcap (Windows) / libpcap (Linux)
- Admin privileges for sniffing/injection

---

## Setup

### 1) Create venv
**Windows (PowerShell)**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
