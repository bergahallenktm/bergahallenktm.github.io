# bergahallenktm.github.io
[Android App](https://play.google.com) | [BergaHallenKTM Server](https://github.com/bergahallenktm/bergahallenktm-server) | [BergaHallenKTM Server Manager](https://github.com/bergahallenktm/bergahallenktm-server-installer) | [BergaHallenKTM](https://github.com/bergahallenktm/bergahallenktm)

---
# What is BergaHallen KTM?

BergaHallen KTM is a self-hosted/local-first companion system for playing and managing **Magic: The Gathering** games.

The project started as a family/kitchen-table match tracker and has grown into a suite containing:

- a local Server/Webapp;
- a Linux Installer/Manager;
- a native Android application;
- an on-device MTG card scanner called QuickScan.

## Product philosophy

The system is designed so that a household or play group can run its own server without handing player/game data to a BergaHallen-operated central cloud service.

There are two important Android usage models:

### Local Mode

The Android device can operate independently of a server for core local gameplay/data workflows.

Local data is stored on-device.

### Server Mode

The Android app connects to a user-selected, self-hosted BergaHallen KTM Server over HTTPS.

The server holds shared:

- accounts/players;
- decks;
- active matches;
- match history;
- statistics;
- synchronization state.

## Main user functionality

The current product supports, among other things:

- player/account registration and login;
- decks and decklists;
- deck ownership/loan use;
- active and simultaneous matches;
- life totals;
- poison counters;
- commander tax;
- commander damage;
- concede/elimination/winner state;
- undo/event history;
- turn order and seat order;
- server-backed timers;
- history/statistics;
- Swedish/English UI;
- offline/local play;
- QR-based secure Server pairing;
- admin/server management;
- self-service account deletion;
- on-device QuickScan card recognition.

## Match model

The match-format engine is broader than a simple Commander tracker.

Current Server logic includes:

- Commander;
- Oathbreaker;
- constructed formats;
- Kitchen Table/freeform;
- duel/FFA/teams;
- Two-Headed Giant;
- Emperor;
- Archenemy;
- Archenemy Commander;
- Attack Left / Defend Right;
- Kingdoms/Treachery-style hidden roles;
- Assassin/secret-target style play;
- Limited formats including Booster Draft, Sealed, Cube, Conspiracy Draft, Team Draft and Team Sealed;
- Planechase as a modifier/foundation.

Do not hard-code match behavior in a client without checking the Server match/rules contracts. The Server remains the shared source of truth for Server Mode rules/state.


[Privacy Policy](https://bergahallenktm.github.io/PRIVACY_POLICY.html) | [License](https://bergahallenktm.github.io/license.html) | [Account Deletion](https://bergahallenktm.github.io/ACCOUNT_DELETION.html) | [BergaHallenKTM](https://github.com/bergahallenktm/bergahallenktm)
