# Ubunex Desktop releases

Installers and update files for Ubunex Desktop. This repository holds release files only; the
app is built from a private repository, and the files here are attached to each release by its
CI.

Download the latest version from the [Releases](../../releases/latest) page.

Each release lists its files' SHA-256 checksums. Windows and macOS installers are code-signed once
signing is configured; the update files (`.sig`) are signed with the app's update key, and the
app refuses an update whose signature does not match.

© Ubunex. All rights reserved. The installers include open-source components; their notices are
listed at https://ubunex.com/legal/third-party, and the desktop shell's in `THIRD-PARTY.md`
attached to each release.
