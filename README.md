# 🦉 OIcingaX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OIcingaX** — Monitoring Configuration Hardening Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

Icinga 2 / Icinga Web 2 / Nagios / NRPE / NSClient++ configuration hardening auditor

---

## ✨ Features

- Stdlib Icinga 2 DSL / INI / Nagios cfg / htpasswd parsers
- Icinga 2 — ApiListener accept_config / accept_commands, ticket_salt, bind_host, TLS protocolmin / cipher_list, ApiUser passwords & '*' permissions, zones / endpoints, IDO / IcingaDB / writer TLS & passwords, constants.conf secrets, PKI key permissions, shell-command injection
- Icinga Web 2 — resources / authentication / roles
- Nagios Core — external commands, command pipe perms, cgi.cfg authorized_for_* = *, default_user_name, htpasswd
- NRPE — dont_blame_nrpe, bash substitution, allowed_hosts, SSL / ADH, nrpe_user root, command[] args & plugin perms
- NSClient++ — allowed hosts, arguments, nasty chars, TLS
- File ownership / permission checks; --root offline trees
- Export TXT / Markdown / JSON / CSV / SARIF 2.1.0
- Self-test --demo, CI gates --fail-on / --min-severity

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OIcingaX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
