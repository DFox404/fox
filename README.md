<p align="center">
  <img src="https://img.shields.io/badge/KURAMA-v5.0-red?style=for-the-badge&logo=skull" alt="KURAMA v5.0">
</p>

<h1 align="center">🔥 KURAMA ENGINE</h1>
<p align="center"><b>Advanced HTTP Flood & DDoS Engine</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Flask-3.0-black?logo=flask" alt="Flask">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Termux-Supported-brightgreen" alt="Termux">
</p>

---

## ⚡ About

**KURAMA ENGINE** is a high-performance, multi-threaded HTTP flood engine designed for stress testing and server load analysis. Built with Python `asyncio` + `aiohttp`, it delivers maximum concurrent request throughput with minimal resource usage.

## 🛠 Features

- ⚡ **AsyncIO Engine** — Thousands of concurrent requests per second
- 🌐 **Multi-threaded** — 1-128 configurable worker threads
- 📊 **Real-time Dashboard** — Web UI with live stats & response feed
- 🎯 **Custom Payloads** — JSON, XML, form-data support
- 🔄 **Proxy Support** — HTTP/S proxy rotation
- 🧩 **Multiple Methods** — GET, POST, PUT, PATCH, DELETE
- ⏱️ **Rate Limiting** — Request delay, duration limit, request cap
- 🔒 **SSL Control** — Toggle verification on/off

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/your-username/kurama-engine.git
cd kurama-engine

# Install dependencies
pip install flask flask-socketio aiohttp requests

# Run engine
python server.py
```

Open browser: http://localhost:5000

📸 Screenshot

<p align="center">
  <i>Dark-themed dashboard with real-time attack monitoring</i>
</p>

⚙️ Configuration

Option Default Description
method POST HTTP method
threads 8 Worker threads
concurrency 1500 Concurrent connections
timeout 2.0s Request timeout
duration_limit 0 (∞) Max attack duration
request_limit 0 (∞) Max request count

⚠️ Legal Disclaimer

This tool is for educational and authorized testing only.
Do not use against systems you do not own or have written permission to test.
Misuse of this tool may result in legal consequences under applicable laws.

📜 License

 © 2026 DFox404 — For educational purposes only.

---

<p align="center">
  <sub>⚡ Powered by Python • AsyncIO • aiohttp</sub>
</p>
