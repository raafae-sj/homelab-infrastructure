### What I noticed
- **Hostname, not IP:** after the certificate was issued I still got a browser warning, because I was opening Proxmox by its IP address. The certificate only matches the hostname, so I switched to `https://pve.example.com:8006`.
- **DNS challenge delay:** Proxmox adds a temporary TXT record in Cloudflare and waits about 30 seconds for it to propagate before Let's Encrypt checks it.
- **Skipped staging:** I ordered against the production Let's Encrypt directory straight away. It worked first time, but staging is safer when you expect failures, because production has rate limits.
