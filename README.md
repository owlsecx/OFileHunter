# 🦉 OFileHunter

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-OForensics%20%2F%20File%20Analysis-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-tkinter%20(stdlib)-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OFileHunter** is a powerful forensic file and directory scanner. It performs byte-level pattern search (literal + regex), magic-number identification, MD5/SHA1/SHA256 hashing, hex-dump preview, and exports reports in JSON, CSV, HTML, or TXT.

---

## 📌 Overview

OFileHunter is a modern GUI forensic tool for hunting sensitive data inside files and directories. It supports full-text search, regex, magic signature detection, context preview, and detailed reporting with hashing.

**GUI built with tkinter** — works on Linux and Windows.

---

## 🖥️ Features

- **Byte-level Search** — Literal and Regex pattern matching
- **Magic-Number Detection** — 25+ file signatures (JPEG, PNG, PDF, ZIP, ELF, PE, SQLite, MP4, etc.)
- **Hashing** — MD5, SHA1, SHA256 for every scanned file
- **Hex Dump** — Context-aware hex + ASCII preview
- **Advanced Filters**:
  - Extension filter
  - Magic keyword filter
  - Min/Max file size
  - Text-like / Binary mode
- **Export Formats** — JSON, CSV, HTML, TXT
- **External Hex Viewer** — Launch ghex, bless, hexedit, etc.
- **Dark / Light Theme** — Toggle between themes
- **Progress Bar** — Real-time scanning feedback

---

## ⚙️ Requirements

- **Linux or Windows**
- **tkinter** (included with standard Python)
- **No additional pip packages required**

---

## 🚀 Usage

```bash
./OFileHunter

📁 Output

Live Matches View — Real-time findings with offset, context, and hex dump
Full Log View — Complete forensic audit trail with timestamps
File Reports — Hash values, signature, size, MACB timestamps
Export Reports — Structured JSON/CSV/HTML or human-readable TXT


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.

AUTHORISED FORENSIC FILE ANALYSIS USE ONLY
