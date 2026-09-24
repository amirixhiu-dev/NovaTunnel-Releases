<div align="center">

<a href="https://nova-bot.de5.net/">
  <img src="novatunnel-logo.png" width="190" alt="NovaTunnel Logo">
</a>

# NovaTunnel

### Fast. Simple. Private.

**Official release & distribution repository for NovaTunnel VPN**

<p>
  <a href="https://nova-bot.de5.net/">
    <img alt="Website" src="https://img.shields.io/badge/Website-NovaTunnel-00C2FF?style=for-the-badge&logo=googlechrome&logoColor=white">
  </a>
  <a href="https://t.me/NovaTunnel_VPNBot">
    <img alt="Telegram Bot" src="https://img.shields.io/badge/Telegram-@NovaTunnel__VPNBot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
  <a href="../../releases">
    <img alt="GitHub Releases" src="https://img.shields.io/badge/Releases-GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

<p>
  <img alt="Android" src="https://img.shields.io/badge/Android-In%20Development-3DDC84?style=flat-square&logo=android&logoColor=white">
  <img alt="Windows" src="https://img.shields.io/badge/Windows-Planned-0078D4?style=flat-square&logo=windows11&logoColor=white">
  <img alt="iOS" src="https://img.shields.io/badge/iOS-Planned-black?style=flat-square&logo=apple&logoColor=white">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-Planned-black?style=flat-square&logo=apple&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-Planned-FCC624?style=flat-square&logo=linux&logoColor=black">
</p>

**Official downloads · Release notes · Checksums · Update information**

</div>

<br>

<p align="center">
  <a href="https://nova-bot.de5.net/">
    <img src="novatunnel-poster.jpg" width="100%" alt="NovaTunnel VPN Poster">
  </a>
</p>

---

## ✨ About NovaTunnel

**NovaTunnel** is a multi-platform VPN project focused on providing a clean, reliable, and easy-to-use connection experience.

This repository is the **official public distribution hub** for NovaTunnel release files, release notes, checksums, and update information.

> [!IMPORTANT]
> This repository contains **release artifacts only**.  
> The NovaTunnel application source code, backend services, infrastructure, deployment configuration, and internal development tooling are maintained separately and are not included here.

<p align="center">
  <img src="novatunnel-brand-card.png" width="680" alt="NovaTunnel Brand">
</p>

---

## 📦 Project Status

NovaTunnel is currently under active development.

### There are no public production releases yet.

Development, test, debug, instrumentation, unsigned, and internal builds must **not** be treated as production releases.

When the first public version is ready, it will be published through this repository's official **Releases** section.

### Platform Status

| Platform | Development Status | Public Release |
|:---:|:---:|:---:|
| 🤖 **Android** | 🟡 In Development | Not available yet |
| 🪟 **Windows** | ⚪ Planned | Not available yet |
| 🍎 **iOS** | ⚪ Planned | Not available yet |
| 💻 **macOS** | ⚪ Planned | Not available yet |
| 🐧 **Linux** | ⚪ Planned | Not available yet |

---

## 📥 Download NovaTunnel

<div align="center">

### 🚧 No production build is available yet

<a href="../../releases">
  <img src="https://img.shields.io/badge/OPEN_GITHUB_RELEASES-181717?style=for-the-badge&logo=github&logoColor=white" alt="Open GitHub Releases">
</a>

</div>

Once a production release becomes available, release assets will be published with information such as:

- Application version
- Build number
- Release date
- Changelog
- Target platform
- File name and size
- SHA-256 checksum when available
- Upgrade or migration notes when required
- Known issues when applicable

> [!WARNING]
> Do **not** install NovaTunnel builds downloaded from random websites, unofficial Telegram channels, file-sharing services, unofficial mirrors, or third-party repositories.

---

## 🔐 Official Download Policy

A file should only be considered an **official NovaTunnel release** when it can be traced to one of the official distribution channels documented in this repository.

### Primary release source

**GitHub Releases**

```text
https://github.com/amirxhiu-dev/NovaTunnel-Releases/releases
```

Additional official download methods may be announced through the NovaTunnel website or official Telegram bot.

If a build cannot be traced back to an official NovaTunnel channel, treat it as **untrusted**.

---

## 🌐 Official Channels

| Service | Official Link |
| --- | --- |
| 🌐 **Website** | [nova-bot.de5.net](https://nova-bot.de5.net/) |
| 🤖 **Telegram Bot** | [@NovaTunnel_VPNBot](https://t.me/NovaTunnel_VPNBot) |
| 💬 **Support** | [@USAkings](https://t.me/USAkings) |
| 📦 **GitHub Releases** | [NovaTunnel-Releases](../../releases) |

> [!CAUTION]
> Be careful with websites, channels, accounts, repositories, or files impersonating NovaTunnel.
>
> Never provide passwords, recovery codes, private keys, payment credentials, or other sensitive information to unofficial accounts.

---

## ✅ Verify Your Download

Some NovaTunnel releases may include a **SHA-256 checksum**.

SHA-256 can be used to verify that the downloaded file matches the file published with the release.

### Windows — PowerShell

```powershell
Get-FileHash .\NovaTunnel.apk -Algorithm SHA256
```

### Windows — Command Prompt

```cmd
certutil -hashfile NovaTunnel.apk SHA256
```

### Linux

```bash
sha256sum NovaTunnel.apk
```

### macOS

```bash
shasum -a 256 NovaTunnel.apk
```

Compare the calculated value with the SHA-256 checksum published in the corresponding GitHub Release.

> [!NOTE]
> A matching checksum confirms **file integrity**.
>
> A checksum alone does not prove who originally published a file. Always obtain both the release asset and the expected checksum from an official NovaTunnel source.

---

## 🚫 Builds That Are Not Public Releases

The following types of files are **not intended for public distribution** unless explicitly attached to an official GitHub Release:

```text
app-debug.apk
app-debug-androidTest.apk
*-debug.apk
*-unsigned.apk
instrumentation builds
internal test builds
development snapshots
temporary CI artifacts
```

Their presence anywhere does **not** mean that a new NovaTunnel production version has been released.

---

## 🏷️ Release Channels

NovaTunnel may use different release stages during development.

| Channel | Purpose |
| --- | --- |
| 🟢 **Stable** | Production release intended for normal users |
| 🟡 **Beta** | Public testing before stable release |
| 🧪 **Development / Internal** | Engineering and internal testing only |

Unless a release is explicitly marked otherwise, users should prefer the latest **Stable** release.

---

## 📝 Release Notes

Production releases may include information such as:

```text
✨ New features
⚡ Performance improvements
🛡️ Security improvements
🌐 Connection improvements
🐛 Bug fixes
🎨 UI/UX improvements
🔧 Reliability improvements
```

Breaking changes, migration requirements, compatibility notes, or known issues will be documented when applicable.

---

## 🔄 Update Distribution

NovaTunnel's release infrastructure is designed so that public version information can be distributed across official NovaTunnel services.

When a new public release becomes available, information may also appear through:

- 🌐 NovaTunnel website
- 🤖 NovaTunnel Telegram bot
- 🐙 GitHub Releases

Always verify that the version number, file name, and download source correspond to an official NovaTunnel release.

---

## 🧩 Repository Purpose

This repository is intentionally focused on **release distribution**.

It may contain:

- Official release binaries
- Version history
- Release notes
- Integrity hashes
- Download information
- Public update metadata

It is **not** the primary source-code repository for NovaTunnel.

---

## 💻 Source Code

NovaTunnel's application source code and internal infrastructure are maintained separately.

This includes components such as:

- Application source code
- Backend services
- Deployment configuration
- Infrastructure
- Internal automation
- Development tooling

Their absence from this repository does not indicate missing release files.

This repository exists specifically as the public release and distribution endpoint.

---

## 🗺️ Roadmap

Current high-level platform direction:

```text
NovaTunnel
│
├── Android        🟡 In development
├── Windows        ⚪ Planned
├── iOS            ⚪ Planned
├── macOS          ⚪ Planned
└── Linux          ⚪ Planned
```

Platform availability and priorities may change as development progresses.

---

## 🛡️ Security

If you discover a security issue related to NovaTunnel, avoid publishing credentials, access tokens, private endpoints, private keys, exploit details, or other sensitive information in a public GitHub issue.

Please contact the project through an official support channel:

**Telegram:** [@USAkings](https://t.me/USAkings)

---

## 🔁 Redistribution

NovaTunnel release files must not be redistributed, repackaged, modified, re-uploaded, or mirrored unless:

1. The corresponding release notes explicitly allow redistribution, or
2. Written permission has been provided by the NovaTunnel project.

This policy is intended to reduce the risk of modified, outdated, or malicious builds being presented as official NovaTunnel software.

---

## ❓ Frequently Asked Questions

<details>
<summary><b>Is NovaTunnel available for download?</b></summary>

Not yet. There is currently no public production release.

Official versions will appear in this repository's **Releases** section when they are ready.

</details>

<details>
<summary><b>I found a NovaTunnel APK somewhere else. Is it official?</b></summary>

Do not assume that it is official.

Only trust builds distributed through the official NovaTunnel channels documented in this repository.

</details>

<details>
<summary><b>Why are there no application source files in this repository?</b></summary>

This repository is dedicated to release distribution.

The application source code and internal infrastructure are maintained separately.

</details>

<details>
<summary><b>How can I verify a downloaded file?</b></summary>

When a SHA-256 checksum is published, calculate the hash of your downloaded file and compare it with the value listed in the corresponding GitHub Release.

</details>

<details>
<summary><b>Will NovaTunnel support platforms other than Android?</b></summary>

Yes. NovaTunnel is planned as a multi-platform project.

Android is currently the active development target, while Windows, iOS, macOS, and Linux are planned.

</details>

---

<div align="center">

<img src="novatunnel-logo.png" width="96" alt="NovaTunnel Logo">

## NovaTunnel

**Secure connections. Simple experience.**

[Website](https://nova-bot.de5.net/) ·
[Telegram Bot](https://t.me/NovaTunnel_VPNBot) ·
[Support](https://t.me/USAkings) ·
[Releases](../../releases)

<br>

**Only download NovaTunnel from official sources.**

</div>
