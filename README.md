![RidoGuard](banner.png)

# RidoGuard downloads

Public download host for [RidoGuard](https://ridoco.com/ridoit/ridoguard), a Windows
privacy and security tool by [Ridoco](https://ridoco.com).

## [Download the latest release](https://github.com/Ridocompany/ridoguard-releases/releases/latest)

That link always resolves to the newest version.

RidoGuard turns off telemetry, blocks tracking domains at the firewall, hardens DNS and trims
background services. Applying a profile, removing preinstalled apps and changing service presets
are written to an audit log and can be undone with the command line rollback.

## Why this repository exists

It holds published builds only. The source is private. Downloads live here so they can be fetched
without an account, and the winget package manifest points at this repository.

Every release ships a `SHA256SUMS` file. Verify before running, substituting the version you
downloaded:

    certutil -hashfile RidoGuard-Setup-<version>.exe SHA256

## Signing

Builds are not code-signed yet, so Windows SmartScreen warns on first run. Check the file against
the published SHA256 before you run it.

## Issues and support

Report problems through [ridoco.com](https://ridoco.com). This repository carries no source and
does not track issues.

---

Copyright Ridoco. KVK 95439609. All rights reserved.
