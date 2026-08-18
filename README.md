# RidoGuard downloads

Public download host for [RidoGuard](https://ridoco.com/ridoit/ridoguard), a Windows
privacy and security tool by [Ridoco](https://ridoco.com).

## [Download the latest release](https://github.com/Ridocompany/ridoguard-releases/releases/latest)

That link always resolves to the newest version, so it never needs updating here.

RidoGuard turns off telemetry, blocks tracking domains at the firewall, hardens DNS and trims
background services. Every change is logged and reversible.

## Why this repository exists

It holds published builds only. The source is private, so downloads live here where they can be
fetched without an account, which is also what the winget package manifest points at.

Every release ships a `SHA256SUMS` file. Verify before running, substituting the version you
downloaded:

    certutil -hashfile RidoGuard-Setup-<version>.exe SHA256

## Signing

Builds are not code-signed yet, so Windows SmartScreen warns on first run. We would rather say
that here than have you meet the warning without explanation. Verify the checksum if you would
like certainty in the meantime.

## Issues and support

Report problems through [ridoco.com](https://ridoco.com). This repository carries no source, so
it does not track issues.

---

Copyright Ridoco. KVK 95439609. All rights reserved.
