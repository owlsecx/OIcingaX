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

OIcingaX — Monitoring Configuration Hardening Auditor. It provides stdlib Icinga 2 DSL / INI / Nagios cfg / htpasswd parsers. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib Icinga 2 DSL / INI / Nagios cfg / htpasswd parsers
- Icinga 2 — ApiListener accept_config / accept_commands, ticket_salt, bind_host, TLS protocolmin / cipher_list, ApiUser passwords & '*' permissions, zones / endpoints, IDO / IcingaDB / writer TLS & passwords, constants.co
- Icinga Web 2 — resources / authentication / roles
- Nagios Core — external commands, command pipe perms, cgi.cfg authorized_for_* = *, default_user_name, htpasswd
- NRPE — dont_blame_nrpe, bash substitution, allowed_hosts, SSL / ADH, nrpe_user root, command[] args & plugin perms
- NSClient++ — allowed hosts, arguments, nasty chars, TLS

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OIcingaX                                     # interactive menu
./OIcingaX --scan -r /path/to/root
./OIcingaX --demo
./OIcingaX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
