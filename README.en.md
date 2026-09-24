<div align="center">

<img src="images/logo.png" alt="Powfus" width="120" />

# Powfus Launcher

**The multi-account Dofus launcher — simple, and respectful of your credentials.**

[![Download](https://img.shields.io/badge/Download-Powfus_1.4.1-e83fb0?style=for-the-badge)](../../releases/latest)
[![Version](https://img.shields.io/badge/version-1.4.1-b56cff?style=for-the-badge)](../../releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-2f9ee8?style=for-the-badge&logo=windows)](../../releases/latest)
[![Buy me a coffee](https://img.shields.io/badge/☕-Buy_me_a_coffee-ffb454?style=for-the-badge)](https://buymeacoffee.com/jyanis95c)

[🇫🇷 Français](README.md) · **🇬🇧 English**

</div>

---

> ⚠️ **Third-party tool, not affiliated with Ankama.** Multi-accounting and client instrumentation may
> breach the terms of service of the games involved. Strictly **personal** use, on **your own accounts**,
> at your own risk.

## What is it?

**Powfus** is a launcher that lets you start and manage **several Dofus accounts** in parallel, from a
single clear window. It replaces the official launcher for multi-accounting, with:

- ▶️ **one-click launch**, one or several accounts at a time;
- 🖼️ **windows positioned** the way you want (fullscreen, chosen monitor, size, multi-monitor);
- 🌐 **a dedicated IP or proxy per account** (essential on Dofus Retro, 1 account per IP);
- ⭐ **favorites, tags, search**, subscription tracking (“X days left”) and character info;
- ⌨️ **keyboard shortcuts** to switch between windows;
- 🎨 **5 themes** and a no-nonsense interface;
- 🌍 **interface in 5 languages**: French, English, Spanish, German, Portuguese.

<div align="center"><img src="images/apercu-liste.png" alt="Account list" width="820" /><br><em>The account list: launch, organize, monitor.</em></div>

## 🔒 Your credentials stay with you

This is the most important point, so let's be clear:

| Question | Answer |
| --- | --- |
| **Is my password stored?** | **No, never.** You sign in on Ankama's **official page**; Powfus never reads or stores your password. Only an **access key** is kept. |
| **Is that key in plain text?** | **No.** It is encrypted at rest with **AES-256-GCM**, using a key **derived from your machine** and never saved. A data folder copied to another PC **won't decrypt**. |
| **Does Powfus contact a server of yours?** | **No.** No remote server, no cloud, no online license, **no telemetry**. Powfus only talks to Ankama's **official services**, exactly as the official launcher would. |
| **Could it steal a token?** | **No.** Nothing leaves your machine toward a third party. The interface runs **locally** (`127.0.0.1`) and rejects any foreign origin. |
| **Can I check?** | Yes: the launcher includes a **diagnostic report** that shows exactly what it uses, with no secrets. |

> In short: **Powfus behaves like the official launcher** toward Ankama, plus the convenience of
> multi-accounting. It adds **no middleman** between you and Ankama.

## 📥 Installation

1. **Download** the `Powfus-1.4.1.msi` file from the [releases page](../../releases/latest).
2. **Double-click** it. Windows may show a blue **“Windows protected your PC”** screen (SmartScreen):
   this is normal for a recent app that is **not signed by a large vendor** — it is not a sign of a
   virus. Click **“More info”**, then **“Run anyway”**.
3. Follow the wizard (welcome → license → folder → install).
4. Launch **Powfus** from the **Start menu** or the **Desktop shortcut**.

### First run

- **Import your accounts** from the Ankama launcher (fastest), **or**
- **Add an account manually**: Powfus opens Ankama's **official** login page, you sign in, and that's it.

### Requirements

- **Windows 10 / 11 (64-bit)**
- **Dofus installed** via the Ankama launcher
- A **Chromium** browser (Chrome, Edge, Brave…) for the app window and the Ankama login

## ⚙️ Settings at a glance

The settings panel is organized into sections:

| Section | What it does |
| --- | --- |
| **Application** | Theme, language, local port, start with Windows, data folder |
| **Launch** | Default display (fullscreen, monitor, size…), delay between launches, game paths |
| **Network** | Default SOCKS5 proxy, detected local IPs (for the per-account dedicated IP) |
| **Accounts & keys** | Access-key status (informational) and on-demand check |
| **Instrumentation** | Advanced settings (injection mode, fingerprint) — with warnings |
| **Interface** | Visible columns, sorting, density, confirmations |
| **Logs & diagnostics** | Log level, logs folder, diagnostic report |

<div align="center"><img src="images/apercu-reglages.png" alt="Settings" width="820" /><br><em>Clear settings, with safe defaults.</em></div>

## ❓ FAQ

**Is it a bot / a cheat?**
No. Powfus launches the **official client** and helps you manage several windows. It does not play for
you and does not modify gameplay.

**Will I get banned?**
Multi-accounting and instrumentation may breach the terms of service depending on the server (especially
single-account ones like Dofus Retro). That's a choice and a risk **you take on**, on your own accounts.

**Does my data go anywhere?**
No. Everything stays local on your machine. See the [🔒 security](#-your-credentials-stay-with-you) section.

## ☕ Support the project

Powfus is developed in my free time, for free. If the tool is useful to you:

<div align="center">

[![Buy me a coffee](https://img.shields.io/badge/☕-Buy_me_a_coffee-ffb454?style=for-the-badge)](https://buymeacoffee.com/jyanis95c)

</div>

---

<div align="center">
<sub>Powfus is not affiliated with Ankama Games. Dofus is a trademark of Ankama.
Personal-use project, provided “as is”, without warranty.</sub>
</div>
