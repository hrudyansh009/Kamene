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
2. Create virtual environment

Windows

python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip

Linux

python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
3. Install dependencies
pip install scapy

(Optional)

pip install matplotlib cryptography
Usage

Once your entry script is defined:

python main.py

Or run individual modules/scripts as needed.

Project Structure (Planned)
Kamene/
│
├── core/              # Core packet utilities
├── modules/           # Scanners / sniffers / tools
├── experiments/       # Lab experiments
├── docs/              # Notes and research logs
├── main.py            # Entry point
└── README.md
Ethical Notice

Kamene is intended strictly for:

Educational use

Authorized security testing

Research environments

You are responsible for lawful usage.

License

This project depends on Scapy (GPL v2).
Kamene code follows compatible licensing requirements.

Credits

Built using the Scapy packet manipulation library:
https://github.com/secdev/scapy


---

Now clean your repo properly:

1. Replace README.
2. Commit.
3. Push.

```powershell
git add README.md
git commit -m "Rewrite README for Kamene project"
git push

Do it.
