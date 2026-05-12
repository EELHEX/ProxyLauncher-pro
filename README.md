# ProxyLaunch Pro v1.4.2

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/PyQt6-6.4.0-darkblue?style=for-the-badge&logo=qt" alt="PyQt6">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows" alt="Platform">
</div>

<br />

ProxyLaunch Pro is a professional-grade proxy management and browser isolation tool. It allows you to launch multiple Google Chrome instances with unique proxy configurations, ensuring high session isolation and security.

##  Key Features

| Feature | Description |
| :--- | :--- |
| **Protocol Support** | Full support for HTTP, HTTPS, and SOCKS5 proxies. |
| **Browser Isolation** | Automatically creates unique `SessionWorkspace` directories for every session. |
| **Profile Management** | Save your most used proxies as profiles for instant one-click deployment. |
| **Bulk Import** | Integrated TXT importer for migrating large proxy lists. |
| **Heartbeat Monitor** | Automatically checks connection health every 15 seconds. |
| **Auto-Reconnect** | detected drops trigger a silent reconnection attempt. |

## 🛠 Technical Overview

1.  **Launcher**: Utilizes Python's `subprocess` engine to trigger clean Chrome instances with custom flags.
2.  **Arguments**: Injects `--proxy-server` and unique `--user-data-dir` configurations per instance.
3.  **Monitoring**: Real-time `QTimer` background polling for browser state and exit-node health.
4.  **Security**: Local encryption for profile persistence in `%LOCALAPPDATA%`.


##  Preview
*<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/61f715ab-d123-4dc4-abc4-b1b51e1cdd19" />
*

---

##  Security Notice
This tool is designed for professional account management.

##  Support & Contact
For assistance or professional inquiries, reach out to: **@bp1q on Discord**

---
<div align="center">
  <sub>Built with ❤️ for Privacy Enthusiasts</sub>
</div>

