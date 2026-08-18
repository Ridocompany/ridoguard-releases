# RidoGuard downloads

Public download host for [RidoGuard](https://ridoco.com), a Windows privacy and security tool
by Ridoco.

**[Get the latest version](../../releases/latest)**

RidoGuard turns off telemetry, blocks tracking domains at the firewall, hardens DNS and trims
background services. Every change is logged and reversible.

## Why this repository exists

This repo holds published builds only. The source is private, so downloads live here where they
can be fetched without an account, which is also what the winget package manifest points at.

Each release carries a `SHA256SUMS` file. Verify before running:

    certutil -hashfile RidoGuard-Portable-1.2.1.zip SHA256

## Signing

Builds are not code-signed yet, so Windows SmartScreen warns on first run. We would rather say
that here than have you meet the warning without explanation. Verify the checksum if you would
like certainty in the meantime.

## Issues and support

Report problems at [ridoco.com](https://ridoco.com). This repository does not track issues,
since it carries no source.

---

Copyright Ridoco. KVK 95439609. All rights reserved.
