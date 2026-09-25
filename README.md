# SignStrike

**SignStrike detects kernel modifications by malicious programs on Windows and reports them.**

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Language](https://img.shields.io/badge/language-C-A8B9CC.svg)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6.svg)](https://www.microsoft.com/windows)
[![Status](https://img.shields.io/badge/status-early%20development-orange.svg)]()
[![GitHub stars](https://img.shields.io/github/stars/Staatsrat/sign_strike?style=social)](https://github.com/Staatsrat/sign_strike/stargazers)

---

## What it does

SignStrike watches critical kernel structures on Windows callback tables, loaded drivers, and system service tables for unauthorized changes. When something modifies them, SignStrike logs the change and raises an alert.

It is a **defensive security tool**.

---

## Why

Malware and EDR-evasion tools often disable security monitoring by removing kernel callbacks or loading vulnerable drivers (BYOVD). SignStrike watches for exactly these modifications.

---

## Status

Early development. Nothing usable yet.
