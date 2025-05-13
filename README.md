# SearXNG Automated Setup Script

This Bash script provides an automated and customizable way to install, update, uninstall, and configure [SearXNG](https://github.com/searxng/searxng), a privacy-respecting metasearch engine. It also supports optional configuration of the Firefox browser with privacy settings and integration with the Tor network.

## ⚙️ Features

- Automated installation of SearXNG via Docker
- System and dependency updates
- Browser configuration with privacy tweaks
- Tor service setup and usage
- Easy updating and uninstalling
- Clean and interactive logging

---

## 📦 Requirements

- Ubuntu/Debian-based Linux distribution
- `curl`, `git`, `docker`, and `docker-compose` installed
- Root or sudo privileges

---

## 🚀 Usage

```bash
chmod +x setup.sh
./setup.sh [OPTION]

