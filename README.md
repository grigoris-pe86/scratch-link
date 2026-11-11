# scratch-link
A Debian package that downloads and installs version 0.3.0b1 of **Scratch Link Bleak** (https://github.com/rril/scratch-link-bleak/) and provide a **wrapper script** for it.

***

**Quick Reference Guide**

1. Install scratch-link package **sudo dpkg -i scratch-link-0.1-0.3.0b1-sch-scripts_all.deb**
2. Run once **scratch-link --setup**
3. Run **scratch-link --start** to start scratch-link-bleak as background process
4. Run **scratch-link --stop** to terminate scratch-link-bleak process

***

**Available wrapper commands:**

| Command | Purpose |
|---|---|
| `scratch-link --install` | Interactive, safe-to-rerun desktop setup |
| `scratch-link --certificate-status` | Show expiry date and warning |
| `scratch-link --renew-certificate` | Renew when 30 days or fewer remain, with confirmation and Chrome trust update |
| `scratch-link --renew-certificate --force-renew` | Explicitly rotate a still-valid certificate |
| `scratch-link --install-service` | Opt in to service and weekly reminder timer |
| `scratch-link --remove-service` | Disable/remove our managed service and reminder only |
| `scratch-link --setup` | Legacy option: generate TLS files without importing browser trust |
| `scratch-link --status` | Check scratch-link-bleak status (running as a systemd service, as background process, neither) |
| `scratch-link --start` | Start scratch-link-bleak as background process |
| `scratch-link --stop` | Stop scratch-link-bleak (terminate process) |

***

For more information about **Scratch Link Bleak** please visit the project page: (https://github.com/rril/scratch-link-bleak/)
