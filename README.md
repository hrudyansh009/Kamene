# Kamene

Kamene is a lightweight network experimentation and tooling framework built on top of **Scapy**.

It focuses on practical packet crafting, traffic inspection, and custom network tool development — without the overhead of a full framework.

> Status: Active development

---

## Purpose

Kamene is not a replacement for Scapy.  
It is a structured project layer that uses Scapy to build:

- Custom packet sniffers
- Targeted network scanners
- Protocol analyzers
- Packet manipulation utilities
- Security research experiments

The goal is to move from interactive testing to structured tooling.

---

## Why Kamene?

Scapy is powerful but raw.  
Kamene adds:

- Organized project structure
- Modular scripts
- Reusable components
- Clean experimentation workflow
- Tool-ready architecture

This makes it suitable for:
- Cybersecurity learning
- Network automation research
- Red team lab experimentation
- Protocol behavior analysis

---

## Requirements

- Python 3.10+
- Scapy
- Npcap (Windows) or libpcap (Linux)
- Administrator / root privileges (for packet injection & sniffing)

---

## Installation

### 1. Clone repository
```bash
git clone https://github.com/hrudyansh009/Kamene.git
cd Kamene
