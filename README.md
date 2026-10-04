# BergaHallen KTM 

Welcome to the official documentation **BergaHallen KTM**.

[Android App](https://play.google.com) | [BergaHallenKTM Server](https://github.com/bergahallenktm/bergahallenktm-server) | [BergaHallenKTM Server Manager](https://github.com/bergahallenktm/bergahallenktm-server-installer) | [BergaHallenKTM](https://github.com/bergahallenktm/bergahallenktm)

An offline-first Magic: The Gathering match companion with an optional self-hosted server.**

BergaHallen KTM is built for players who want a simple way to run and track Magic: The Gathering games while keeping their data under their own control.

The Android app is designed to work locally. A BergaHallen KTM Server is optional and can be added when you want shared players, decks, match history, statistics and synchronization between devices on your local network.

> **Development Preview**  
> BergaHallen KTM is under active development. Public preview releases may change between versions.

**[Get Started](#get-started)** · **[Install Server](#install-server)** · **[Downloads](#downloads)** · **[Documentation](https://github.com/bergahallenktm/bergahallenktm)** · **[GitHub](https://github.com/bergahallenktm)**

---

## What can BergaHallen KTM do?

- Track life totals during Magic games.
- Track Commander damage, poison and Commander tax.
- Manage players and decks.
- Support multiple match formats and multiplayer layouts.
- Keep core match functionality available without a server.
- Connect to a self-hosted server for shared data, history and statistics.
- Keep the server on your own local network.

---

<a id="get-started"></a>

## Get Started

### I only want to play locally

You do **not** need a server for the core local/offline experience.

The Android app can run matches locally and is designed around offline-first operation.

> Public Android distribution is still being prepared. Download information will be added here when the public Android release is ready.

### I want shared players, decks and match history

Install the optional BergaHallen KTM Server.

For most users, the recommended method is **BergaHallen KTM Installer & Manager**. It guides the server installation and provides a web interface for ongoing server administration.

**[Install BergaHallen KTM Server →](https://github.com/bergahallenktm/bergahallenktm-server-installer/releases)**

---

<a id="install-server"></a>

## Install the Server

### Recommended: Installer & Manager

Use this route if you are installing BergaHallen KTM for the first time.

1. Prepare a supported Ubuntu Server system.
2. Download the latest Installer & Manager `.deb` package.
3. Install the package.
4. Open Manager Web.
5. Let Manager guide you through the BergaHallen KTM Server installation.

**[Download Installer Download latest Installer & Manager Manager →](https://github.com/bergahallenktm/bergahallenktm-server-installer/releases)**

Official server targets are a physical Linux server or a full virtual machine. Container-within-container environments such as LXC/CT are not part of the supported installation path.

### Manual / advanced installation

If you specifically want the standalone server distribution instead of the Installer & Manager workflow, use the Server repository.

**[Open Server downloads →](https://github.com/bergahallenktm/bergahallenktm-server/releases)**

---

<a id="downloads"></a>

## Downloads

| Component | Recommended for | Download |
| --- | --- | --- |
| **Installer & Manager** | New server installations | [Release downloads](https://github.com/bergahallenktm/bergahallenktm-server-installer/releases) |
| **Server** | Manual / advanced installation | [Release downloads](https://github.com/bergahallenktm/bergahallenktm-server/releases) |
| **Android App** | Local/offline match companion | Public release coming later |

Preview versions are published as GitHub **Pre-releases**. Always read the release notes before upgrading an existing installation.

---

## Local Mode or Server Mode?

| I want to… | Server required? |
| --- | --- |
| Run a match on one Android device | No  |
| Use core match tracking offline | No  |
| Keep shared players and decks on a server | Yes |
| Synchronize supported data between devices | Yes |
| Keep centralized match history and statistics | Yes |
| Manage the self-hosted installation in a browser | Yes, through Manager Web |

---

## Server philosophy

BergaHallen KTM Server is designed to be **self-hosted and local-first**. It is intended to run on infrastructure you control rather than requiring a public cloud service.

The supported installation flow is designed for users who may have limited Linux command-line experience. Installer & Manager handles the normal installation and management path, while the standalone server package remains available for advanced/manual use.

---

## Documentation

- **[Project overview and documentation](https://github.com/bergahallenktm/bergahallenktm)**
- **[Installer & Manager](https://github.com/bergahallenktm/bergahallenktm-server-installer)**
- **[Server](https://github.com/bergahallenktm/bergahallenktm-server)**
- **[GitHub organization](https://github.com/bergahallenktm)**

Privacy, account deletion and licensing information are maintained in the main project repository.

---

## Need help?

Start by checking the README and release notes for the component you installed. When reporting a problem, include:

- the BergaHallen KTM version,
- your operating system,
- whether you used Installer & Manager or a manual server package,
- the exact error message,
- relevant diagnostic output with passwords, tokens and other secrets removed.

---

## Project status

BergaHallen KTM is a personal/community project under active development. Some components are intentionally not published yet while development and release preparation continue.

BergaHallen KTM is an independent fan-made project and is not affiliated with or endorsed by Wizards of the Coast.

[Privacy Policy](https://bergahallenktm.github.io/PRIVACY_POLICY.html) | [License](https://bergahallenktm.github.io/license.html) | [Account Deletion](https://bergahallenktm.github.io/ACCOUNT_DELETION.html) | [BergaHallenKTM](https://github.com/bergahallenktm/bergahallenktm)
