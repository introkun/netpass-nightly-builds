# 🎮 NetPass — Unofficial 3DS Nightly Builds

Unofficial nightly builds of the [NetPass 3DS Homebrew](https://gitlab.com/3ds-netpass/netpass) project.  
Built automatically every night at 3:00 AM UTC using [GitHub Actions](.github/workflows/build.yml) and Docker.

> ⚠️ This project is **not affiliated** with the official NetPass authors.

---

## ✅ Build Status

[![Nightly Build Status](https://github.com/introkun/netpass-nightly-builds/actions/workflows/build.yml/badge.svg)](https://github.com/introkun/netpass-nightly-builds/actions)
![Total Downloads](https://img.shields.io/github/downloads/introkun/netpass-nightly-builds/total)

_Last build: [see logs](https://github.com/introkun/netpass-nightly-builds/actions/workflows/build.yml)_

---

## 📦 Latest Build

📱 Scan to install the latest nightly netpass.cia on 3DS:
![Install with FBI](https://github.com/introkun/netpass-nightly-builds/raw/main/qr/latest.png)

You can find the latest builds under:

🔗 [**Latest Release →**](https://github.com/introkun/netpass-nightly-builds/releases/latest)

### Included files:
- `netpass.3dsx`
- `netpass.cia`

---

## 🔄 Automation

This repo builds:
- **Nightly** at 3:00 AM UTC
- **On-demand** via GitHub Actions

The workflow:
- Clones the NetPass [GitLab repo](https://gitlab.com/3ds-netpass/netpass)
- Builds it using [`ghcr.io/introkun/netpass-builder`](https://github.com/introkun/netpass-docker-builder)
- Uploads binaries as GitHub Release assets

---

## 📦 Official NetPass

This project builds unofficial nightly versions of [**NetPass**](https://gitlab.com/3ds-netpass/netpass), a homebrew 3DS application.

- 🔗 **Official Source Code**: [gitlab.com/3ds-netpass/netpass](https://gitlab.com/3ds-netpass/netpass)
- 🛠 **Official Release (Universal-DB)**: [Universal-DB NetPass Page](https://db.universal-team.net/3ds/netpass)

---

## 🙏 Credits

- 📦 **Docker-based build system**:  
  [netpass-docker-builder](https://github.com/DanteyPL/netpass-docker-builder)  
  Created by [@DanteyPL](https://github.com/DanteyPL)  
  Used to automate building of this project inside GitHub Actions.

---

## 📜 License

This repository only provides automation and **does not modify** the source.  
See [original NetPass license](https://gitlab.com/3ds-netpass/netpass/-/blob/main/LICENSE) for terms.

---
