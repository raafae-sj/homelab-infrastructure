# Homelab Infrastructure

Documentation for my personal homelab: a Dell OptiPlex 3060 Micro running Proxmox VE, used to learn Linux, networking and virtualisation and to run my own automation.

## Hardware
- Dell OptiPlex 3060 Micro (Intel Core i5-8500T, 8 GB RAM)
- TP-Link TL-SG108E managed switch
- External storage

## What runs on it
| Service | Purpose |
|---|---|
| Proxmox VE | Hypervisor for VMs and containers |
| Tailscale | Private remote access |
| n8n | Workflow automation |
| Docker | Containerised services |
| Jellyfin | Media server |
| Glances | Host monitoring on a dedicated display |

## Documentation
- [Trusted HTTPS for Proxmox](docs/trusted-https.md): Let's Encrypt certificate using Cloudflare DNS
- [Proxmox web interface troubleshooting](https://github.com/raafae-sj/proxmox-web-interface-troubleshooting): monitoring VM, Glances and systemd case study
- [RFX homelab](https://github.com/raafae-sj/rfx-homelab): AI assistant built on Proxmox and n8n

## Progress
- [x] Proxmox installed
- [x] Trusted HTTPS certificate
- [ ] NAS storage
- [ ] Automated backups

## Goals
Learn Linux and server administration, networking and virtualisation through practical projects, and build my own monitoring and automation setup.

## Planned
Automated backups, NAS storage, and hardening of remote access.
