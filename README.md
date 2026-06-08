# 🔍 OSINT Tool — Cybersecurity Edition

> **For authorized security testing and educational purposes only.**

## Features

- 🌐 **WHOIS Lookup** — Registrar, owner info, dates, emails
- 📡 **DNS Records** — A, AAAA, MX, NS, TXT, CNAME, SOA
- 🖥️ **HTTP Headers** — Server, tech stack, security headers
- 🤖 **Tech Detection** — WordPress, React, Vue, Shopify...
- 👤 **Personal Info Extraction** — Emails, phones, names, social media
- 🔑 **Password Generator** — OSINT-based wordlist generation

## Installation

```bash
git clone <repo-url>
cd osint-tool
pip install -r requirements.txt
```

## Usage

```bash
python osint.py https://example.com
# or interactive:
python osint.py
```

## Output

Generates a JSON report: `osint_<domain>_<timestamp>.json`

## Disclaimer

This tool is intended **only** for:
- Authorized penetration testing
- Security research on systems you own or have permission to test
- Educational purposes

Unauthorized use is illegal and unethical.
