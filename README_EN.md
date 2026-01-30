# 🚀 GMSSH Public Image Mirror: Breaking Boundaries for Developers

<p align="left">
  <a href="./README.md">简体中文</a> | <strong简体中文</strong>
</p>

[![](https://img.shields.io/badge/Status-Online-brightgreen)](#) 
[![](https://img.shields.io/badge/Powered%20By-GMSSH-blue)](#)
[![](https://img.shields.io/badge/License-GPL--3.0-lightgrey)](#)

## 📖 Our Story: Why We Do This

As developers, we've all been there: 
You type `docker pull` late at night, and instead of a fast progress bar, you're met with endless `Context canceled` or `Connection refused`.

Network instability and inaccessible official registries are quietly eroding our passion for creation. What should take seconds can often ruin an entire afternoon. **Technology should have no borders, and tools should never be an obstacle.**

As the team behind **GMSSH**, deep-rooted in server management tools, we understand this pain. To bring back a "smooth" experience for the developer community, we've dedicated our server resources to maintain this **purely public, unrestricted** Docker image mirror.

**This isn't a grand business plan—it's simply a tribute from the GMSSH community to developers everywhere.**

---

## ⚡ Quick Start

### Recommended: One-Click Configuration (Supports Ubuntu, CentOS, Debian, etc.)
Use GMSSH-Docker Manager Automatically detect your system and configure the `https://docker.gmssh.com` accelerator:

<img width="2386" height="1344" alt="image" src="https://github.com/user-attachments/assets/0a56505a-9fa6-4ab5-9873-71cd47992ddc" />


### Manual Configuration

Edit `/etc/docker/daemon.json` and add the following:

```json
{
  "registry-mirrors": ["[https://docker.gmssh.com](https://docker.gmssh.com)"]
}

```

*After saving, please run `systemctl restart docker` to apply changes.*

---

## 🌐 Maintenance Plan

| Resource | Official Registry | GMSSH Mirror Address | Status |
| --- | --- | --- | --- |
| **Docker Hub** | `docker.io` | `https://docker.gmssh.com` | ✅ High Speed |
| **GHCR** | `ghcr.io` | `https://ghcr.gmssh.com` | ✅ Active |
| **K8s Registry** | `registry.k8s.io` | `https://k8s.gmssh.com` | ✅ Active |

---

## 🛠 On-Demand Sync (Issue Trigger)

If the image you need is missing from our mirror:

1. **[Open a Sync Issue](https://www.google.com/search?q=https://github.com/GMSSH/mirror/issues/new%3Flabels%3Dsync-request%26title%3DSync:Image_Name)**
2. Our automation bot will pull, sync, and reply with the accelerated path within 5 minutes.

---

## 📱 About GMSSH Terminal

This mirror is proudly powered by the **GMSSH** team.
GMSSH is a **Desktop-level AI Ops Terminal** designed for the AI era.

* **Visual Source Switching**: Built-in global mirrors, switch with one click without memorizing commands.
* **AI Copilot**: Automatically diagnose terminal errors and fix Linux environment issues instantly.
* **Completely Free**: We are committed to providing the purest and most efficient Ops experience for developers.

👉 [Visit GMSSH Website](https://gmssh.com) | [Join Community](https://www.google.com/search?q=%23)

---

<p align="center">
<b>May the world of code be free of barriers. Made with ❤️ by GMSSH Team.</b>
</p>
