# SearXNG Automated Setup Script

This Bash script provides an automated and customizable way to install, configure, update, and manage [SearXNG](https://github.com/searxng/searxng), a privacy-respecting metasearch engine. The script also supports Tor integration and domain configuration.

## ⚙️ Features

- Automated installation of SearXNG via Docker
- System and dependency updates
- Domain name configuration
- Tor service setup and integration
- Easy updating and uninstallation
- Clean and interactive logging
- Public and private IP detection
- Custom browser integration

---

## 📦 Requirements

- Ubuntu/Debian-based Linux distribution
- `curl`, `git`, `docker`, and `docker-compose` installed
- Root or sudo privileges
- Tor installation (optional for Tor support)

---

## 🚀 Usage

```bash
chmod +x searxng.sh
sudo ./searxng.sh [OPTION]

## Available Options
- --help, -h: Show help menu and exit
- --install, -i: Install SearXNG with full setup
- --domain, -d: Set up domain name for SearXNG
- --update, -up: Update SearXNG to the latest version
- --uninstall, -un: Uninstall SearXNG and remove configuration
- --tor, -t: Start and configure Tor service
- --browser, -b: Add custom browser integration
- --reset: Reset SearXNG to default settings

## Examples

```bash
sudo ./setup.sh --install            # Install SearXNG with full setup
sudo ./setup.sh --domain            # Configure domain name
sudo ./setup.sh --update            # Update SearXNG
sudo ./setup.sh --uninstall         # Uninstall SearXNG
sudo ./setup.sh --tor               # Configure Tor service
sudo ./setup.sh --browser          # Add browser integration
sudo ./setup.sh --reset             # Reset SearXNG to default settings
```

## 📝 Notes
- The script should be run as root or with sudo privileges
- Make sure Docker and Docker Compose are installed before running
- Tor must be installed and reachable for Tor support
- The script uses default ports and configurations that can be modified
- Public IP detection is automatic but can be overridden
- Private IP detection is used for internal networking