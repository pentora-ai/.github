# Pentora AI

Welcome to the official GitHub organization for **Pentora** — an open-source, high-performance security scanning platform built for modern, scalable infrastructure.

## 🚀 Our Vision

Pentora empowers security teams with fast, modular, and reliable tooling to discover vulnerabilities, analyze services, and automate network scanning across diverse environments — from cloud-native to bare-metal.

## 🧠 Projects

| Project | Description |
|--------|-------------|
| `pentora` | The core CLI-based security scanner. Detects open ports, gathers banners, and matches against CVEs. |
| `pentora-ui` *(WIP)* | A modern web-based interface for visualizing and managing Pentora scans. |
| `pentora-feed` *(upcoming)* | Plugin and vulnerability feed manager with signature verification support. |

## 🔧 Tech Stack

- **Go** for performance-critical components  
- **Modular architecture** for plugins and protocol support  
- **Kubernetes-ready**, container-friendly design  
- CLI-first, with upcoming API & web UI support

## 📦 Releasing

Stable binaries will be published to our release repo: [pentora-ai/pentora-releases](https://github.com/pentora-ai/pentora-releases).  
Docker images are available via [GHCR](https://ghcr.io/pentora-ai).

## 🛡️ Security

Pentora is security-first by design. All release artifacts are signed, and plugin integrity is verified via hashes and optional signatures.

## 💬 Community

We're just getting started! Feel free to follow the repo, submit issues, or contribute.  
Join discussions, propose ideas, and help us shape the future of intelligent network security tooling.

---

**Website:** [https://pentora.ai](https://pentora.ai)  
**License:** Apache-2.0  
