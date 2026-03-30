<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/banner.svg">
  <source media="(prefers-color-scheme: light)" srcset=".github/banner-light.svg">
  <img alt="SkyzFallin" src=".github/banner.svg" width="100%">
</picture>

**Cybersecurity + Stock Market**

---

## What I Build

### Offensive Security Tooling
- **[ShellChain](https://github.com/SkyzFallin/ShellChain)** — Expect-based SSH + su chaining for non-interactive shells. Handles TTY simulation where standard tools fail. Built for pentesting lateral movement, MCP automation, and CI/CD pipelines.
- **[Web-App-Lab-Setup-er](https://github.com/SkyzFallin/Web-App-Lab-Setup-er)** — One-command setup for a full web app pentesting lab. Deploys DVWA and OWASP Juice Shop in Docker, installs sqlmap/ffuf/gobuster/nikto/nuclei, and pulls SecLists — all from a single script.
- **[ResponderSluiceBoxCleaner](https://github.com/SkyzFallin/ResponderSluiceBoxCleaner)** — Like panning for gold. Sifts through Responder hash captures, deduplicates by username + hash type, archives originals, and outputs a single clean file ready for Hashcat or John.
- **[1-1-LinerToRuleThemAll](https://github.com/SkyzFallin/1-1-LinerToRuleThemAll)** — Interactive Python CLI for 40+ weaponized pentest one-liners organized by category. Set target once, browse, search, and copy ready-to-fire commands. Includes recon, auth attacks, injection, SSRF, evasion, and full exploit chains.
- **[YesNoVNC](https://github.com/SkyzFallin/YesNoVNC)** — One-command noVNC setup for Kali Linux that actually works. Sets up TightVNC + noVNC with the blank-screen fix baked in. Browser-based remote desktop in one shot.
- **[CivicPlusPlus](https://github.com/SkyzFallin/CivicPlusPlus)** *(work in progress)* — OSINT tool for discovering city/county websites running the Civic Plus platform and extracting IT staff contact info. Useful for phishing simulations and authorized social engineering engagements.

### Trading
- **[DegenDetector](https://github.com/SkyzFallin/DegenDetector)** — Real-time insider activity detection dashboard for prediction markets. Monitors Polymarket and Kalshi for volume anomalies using a multi-signal suspicion score (0-100): spike suddenness, robust Z-score, directional conviction, price flip detection, leak probability by category, off-hours activity, and on-chain wallet intelligence. Fires alerts when signals converge.
- **[SPYderScalp](https://github.com/SkyzFallin/SPYderScalp)** — Real-time SPY intraday options signal monitor with a 12-indicator quality score (0-100), multi-timeframe confirmation, prediction tracking, economic calendar, options value scanner, and DTE recommender. Built for 0-2 DTE scalping.
- **[SKYZ-SPY-Scalper](https://github.com/SkyzFallin/SKYZ-SPY-Scalper)** — 1-minute SPY scalping indicator for Webull. Combines EMA trend alignment, pullback continuation entries, RSI/volume filters, and an ATR-based risk framework with three configurable hold profiles.
- **[Webot](https://github.com/SkyzFallin/Webot)** — Fully autonomous Webull trading bot for stocks and options. Momentum-based EMA/SMA + RSI strategy with stop-loss, take-profit, and trailing stops. YAML + .env configuration. Paper and live trading modes.

### AI + Automation
- **[Claude-Desktop-Kali-Setup](https://github.com/SkyzFallin/Claude-Desktop-Kali-Setup)** — One-command installer for Claude Desktop and MCP servers on Kali Linux, Debian, and Ubuntu. Handles APT repo setup, GPG keys, and MCP server integration automatically.

---

## Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/CF_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

> All offensive security tools are intended for authorized use only on systems you own or have explicit written permission to test.
>
> Trading tools are for educational and informational purposes only — not financial advice. Past performance does not guarantee future results. Trade at your own risk.
