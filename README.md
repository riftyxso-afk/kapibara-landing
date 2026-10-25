<div align="center">
  <img src="./assets/logo.png" alt="Kapibara Mascot" width="120" style="border-radius: 28px; box-shadow: 0 12px 36px rgba(0,0,0,0.2);" />
  <h1>Kapibara</h1>
  <p><strong>Your AI can act. Kapibara checks before it does.</strong></p>
  <p>Verification, policy enforcement, and 6-factor risk-checking layer for autonomous coding agents.</p>

  <p>
    <a href="https://github.com/riftyxso-afk/kapibara-landing/actions/workflows/deploy.yml"><img src="https://github.com/riftyxso-afk/kapibara-landing/actions/workflows/deploy.yml/badge.svg" alt="Deploy to GitHub Pages" /></a>
    <img src="https://img.shields.io/badge/license-MIT-orange.svg" alt="License MIT" />
    <img src="https://img.shields.io/badge/status-active-brightgreen.svg" alt="Status" />
  </p>
</div>

---

## 🌟 Overview

**Kapibara** is a developer-first preflight policy engine and MCP server designed to inspect, score, and sanitize autonomous agent actions before execution. 

This repository contains the interactive **Kapibara Landing Page**, adapted from high-craft product design principles ([terms.so](https://terms.so/)) and polished with Emil Kowalski-inspired motion design, squircle geometry, and client-side deterministic evaluation.

### Key Highlights

- **Interactive Agent Setup Popover**: Tabbed multi-agent configurations for Claude Desktop, Cursor, OpenAI Codex, OpenCode, Goose, and Cline with copy-to-clipboard configs and verification checks.
- **6-Factor Risk Matrix**: Visual score breakdown for Action Blast Radius, Sensitive Paths, Irreversibility, Network Scope, Data Exfiltration, and Prompt Injection risk.
- **Interactive Live Playground**: Test agent preflight commands (`git push --force`, `rm -rf`, AWS creds leaks, prompt injections) with real-time risk scores and deterministic simulation fallback.
- **Design Craft**: Handcrafted font stacks (ABC Diatype + Geist Mono), squircle SVG clipping, subtle scanlines, dynamic pill-rail hover physics, and full dark-mode palette.

---

## 🚀 Quick Start (Local Run)

You can serve this landing page locally using any static web server:

```bash
# Using npx serve
npx serve .

# Or using Python built-in server
python3 -m http.server 4173
```

Open `http://localhost:4173` in your browser.

---

## 📂 Repository Structure

```
kapibara-landing/
├── index.html               # Main landing page markup
├── styles.css               # Design system, tokens, responsive typography & animations
├── app.js                   # Interactive timeline, typewriter, squircle engine & simulator
├── assets/
│   ├── logo.png             # 3D Capybara Mascot Logo
│   ├── favicon.png          # 128x128 Favicon
│   ├── icon.svg             # SVG Squircle Icon
│   ├── ABCDiatype-*.otf     # Brand Typography
│   └── GeistMono-*.woff2    # Monospace Typography
├── .github/
│   └── workflows/
│       └── deploy.yml       # Automated GitHub Pages Deployment
└── package.json
```

---

## 🌐 Deploy to GitHub Pages

This repository includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically builds and publishes the landing page to GitHub Pages:

1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, select **GitHub Actions**.
3. Push to `main` branch to trigger an automatic deploy!

---

## 📄 License

MIT © [riftyxso](https://github.com/riftyxso-afk)
