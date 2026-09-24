<div align="center">

# 🛡️ NovaTunnel

### Fast. Simple. Private.

**Official release repository for NovaTunnel VPN**

[![Website](https://img.shields.io/badge/Website-nova--bot.de5.net-00BFFF?style=for-the-badge&logo=cloudflare&logoColor=white)](https://nova-bot.de5.net/)
[![Telegram](https://img.shields.io/badge/Telegram-@NovaTunnel__VPNBot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/NovaTunnel_VPNBot)
[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](#platform-status)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)](#project-status)

<br>

**Official downloads • Release notes • Checksums • Update information**

</div>

---

## ✨ About NovaTunnel

**NovaTunnel** is a multi-platform VPN project focused on delivering a clean, reliable, and easy-to-use connection experience.

This repository is the **official distribution hub** for NovaTunnel release files and release notes.

> [!IMPORTANT]
> This repository contains **release artifacts only**.  
> The NovaTunnel application source code and backend infrastructure are maintained separately and are not included in this repository.

---

## 📦 Project Status

NovaTunnel is currently under active development.

There are **no public production releases yet**.

Development, test, debug, instrumentation, unsigned, and internal builds must **not** be considered production releases.

When the first public version is ready, it will be published through the official GitHub **Releases** section.

### Platform status

| Platform | Status | Public Release |
|:---:|:---:|:---:|
| 🤖 **Android** | 🟡 In Development | Not available yet |
| 🪟 **Windows** | ⚪ Planned | Not available yet |
| 🍎 **iOS** | ⚪ Planned | Not available yet |
| 💻 **macOS** | ⚪ Planned | Not available yet |
| 🐧 **Linux** | ⚪ Planned | Not available yet |

---

## 📥 Download NovaTunnel

### 🚧 No production build is available yet

NovaTunnel has not reached its first public production release.

Once a production version is available, you will be able to download it from:

➡️ **[GitHub Releases](../../releases)**

Release assets will be published together with:

- Application version
- Build number
- Release date
- Changelog
- Platform information
- File size
- SHA-256 checksum when available
- Important upgrade notes when required

> [!WARNING]
> Do **not** install APKs or NovaTunnel builds downloaded from random websites, Telegram channels, file-sharing services, unofficial mirrors, or third-party repositories.

---

## 🔐 Official Download Policy

A file should only be considered an **official NovaTunnel release** when it is published through one of the official distribution channels documented in this repository.

The primary release source is:

### GitHub Releases

**NovaTunnel-Releases**

```text
https://github.com/amirxhiu-dev/NovaTunnel-Releases/releases
```

Additional official download methods may be announced through the NovaTunnel website or Telegram bot.

If a build cannot be traced back to an official NovaTunnel channel, treat it as **untrusted**.

---

## ✅ Verify Your Download

Some NovaTunnel releases may include a **SHA-256 checksum**.

A checksum lets you verify that the downloaded file has not been modified or corrupted.

### Windows

```powershell
Get-FileHash .\NovaTunnel.apk -Algorithm SHA256
```

or:

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

Compare the result with the SHA-256 value published in the corresponding GitHub Release.

Example:

```text
Expected:
4f8c...example...9a21

Calculated:
4f8c...example...9a21

MATCH ✅
```

> [!NOTE]
> A matching checksum confirms **file integrity**, but a checksum by itself does not establish who originally published a file.
>
> Always obtain the expected checksum and the release asset from an official NovaTunnel channel.

---

## 🚫 Builds That Are Not Public Releases

The following files are **not intended for public distribution** unless explicitly attached to an official GitHub Release:

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

Their presence anywhere does **not** mean that a new NovaTunnel version has been officially released.

---

## 🏷️ Release Channels

NovaTunnel may use different release stages during development.

| Channel | Purpose |
| --- | --- |
| 🟢 **Stable** | Recommended production release |
| 🟡 **Beta** | Public testing before stable release |
| 🧪 **Development / Internal** | Engineering and internal testing only |

Unless a release is explicitly marked otherwise, users should prefer the latest **Stable** release.

---

## 📝 Release Notes

Every production release will include a changelog describing relevant changes, such as:

```text
✨ New features
⚡ Performance improvements
🛡️ Security improvements
🌐 Connection improvements
🐛 Bug fixes
🎨 UI/UX improvements
🔧 Internal reliability changes
```

Breaking changes, migration requirements, or known issues will be clearly noted when applicable.

---

## 🔄 Updates

NovaTunnel's release infrastructure is designed so that version information can be distributed across the official NovaTunnel services.

When a new public release becomes available, information may also appear through:

- 🌐 NovaTunnel website
- 🤖 Telegram bot
- 🐙 GitHub Releases

Always verify that the version and download source correspond to an official NovaTunnel release.

---

## 🌐 Official Links

| Service | Official Link |
| --- | --- |
| 🌐 **Website** | [nova-bot.de5.net](https://nova-bot.de5.net/) |
| 🤖 **Telegram Bot** | [@NovaTunnel_VPNBot](https://t.me/NovaTunnel_VPNBot) |
| 💬 **Support** | [@USAkings](https://t.me/USAkings) |
| 📦 **GitHub Releases** | [NovaTunnel-Releases](../../releases) |

> [!CAUTION]
> Be careful with accounts, websites, channels, or repositories impersonating NovaTunnel.
>
> Never provide passwords, recovery codes, private keys, payment information, or other sensitive credentials to unofficial accounts.

---

## 🧩 Repository Purpose

This repository is intentionally focused on **distribution**.

Its purpose is to provide:

- Official release binaries
- Version history
- Release notes
- Integrity hashes
- Download information
- Public update metadata

It is **not** the primary source-code repository for NovaTunnel.

---

## 💻 Source Code

NovaTunnel's application source code, backend services, deployment configuration, infrastructure, internal tooling, and development environments are maintained separately.

Their absence from this repository should not be interpreted as missing release files.

This repository exists specifically as the public release and distribution endpoint.

---

## 🗺️ Roadmap

Current high-level direction:

```text
NovaTunnel
│
├── Android        🟡 In development
│
├── Windows        ⚪ Planned
│
├── iOS            ⚪ Planned
│
├── macOS          ⚪ Planned
│
└── Linux          ⚪ Planned
```

Platform availability and priorities may change as development progresses.

---

## 🛡️ Security

If you discover a security issue related to NovaTunnel, avoid publishing sensitive technical details, credentials, tokens, private endpoints, or exploit information in a public GitHub issue.

Contact the project through an official support channel instead:

**Telegram:** [@USAkings](https://t.me/USAkings)

---

## 🔁 Redistribution

NovaTunnel release files must not be redistributed, repackaged, re-uploaded, modified, or mirrored unless:

1. The corresponding release notes explicitly allow redistribution, or
2. Written permission has been provided by the NovaTunnel project.

This restriction helps reduce the risk of users receiving modified, outdated, or malicious builds presented as official NovaTunnel software.

---

## ❓ Frequently Asked Questions

<details>
<summary><b>Is NovaTunnel available for download?</b></summary>

Not yet. There is currently no public production release.

Official versions will appear in this repository's **Releases** section when ready.

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
<summary><b>How can I verify an APK?</b></summary>

When a SHA-256 checksum is published, calculate the hash of your downloaded file and compare it with the value listed in the corresponding GitHub Release.

</details>

<details>
<summary><b>Will NovaTunnel support platforms other than Android?</b></summary>

Yes. NovaTunnel is planned as a multi-platform project. Android is currently the active development target, while Windows, iOS, macOS, and Linux are planned.

</details>

---

<div align="center">

## 🛡️ NovaTunnel

**Secure connections. Simple experience.**

[Website](https://nova-bot.de5.net/) ·
[Telegram Bot](https://t.me/NovaTunnel_VPNBot) ·
[Support](https://t.me/USAkings) ·
[Releases](../../releases)

<br>

**Only download NovaTunnel from official sources.**

</div>
