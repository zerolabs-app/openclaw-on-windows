![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Installer](https://img.shields.io/badge/install-guided-blueviolet)

# OpenClaw on Windows

Run powerful AI workflows locally — without the setup headaches.

[![Mission Control](https://raw.githubusercontent.com/zerolabs-app/openclaw-on-windows/main/mission-control.png)](https://openclawonwindows.com)

---

## 🚀 What This Is

OpenClaw on Windows is a beginner-friendly setup and management layer for OpenClaw.

It removes the friction of installing and running local AI workflows by guiding users step-by-step and providing a visual dashboard.

---

## ⚙️ What You Get

- Guided setup (even if you’ve never used a terminal)
- Mission Control dashboard for managing workflows
- Stable version tracking built into the installer
- Structured workspace for consistent outputs
- Built-in troubleshooting and reset flow

---

## 📦 Install

Install the latest stable version:

```bash
VERSION=$(curl -fsSL https://raw.githubusercontent.com/zerolabs-app/openclaw-version-control/main/version.txt) && npm uninstall -g openclaw && npm cache clean --force && npm install -g "openclaw@$VERSION" && openclaw --version
