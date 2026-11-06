# CineOrbe

**Windows & Android · Official downloads / Downloads oficiais**

[Português brasileiro](README.md) · English

CineOrbe is an app for browsing a movie and series catalogue and playing available content. This repository distributes the Windows application and Android APK; it does not contain the application source code or internal licensing tools.

## Downloads

| Platform | Version | Download |
| --- | --- | --- |
| Windows x64 — installer | 1.5.14 | [Download setup.exe](https://github.com/IstefaniOrbe/CineOrbe/releases/download/windows-v1.5.14/CineOrbe-1.5.14-setup.exe) |
| Windows x64 — portable | 1.5.14 | [Download portable.exe](https://github.com/IstefaniOrbe/CineOrbe/releases/download/windows-v1.5.14/CineOrbe-1.5.14-portable.exe) |
| Android 8.0+ — APK | 1.5.17 | [Download APK](https://github.com/IstefaniOrbe/CineOrbe/releases/download/android-v1.5.17/CineOrbe-Android-1.5.17.apk) |

All versions and SHA-256 checksums are available on the [Releases page](https://github.com/IstefaniOrbe/CineOrbe/releases). Windows and Android use independent version numbers.

## Installation

### Windows

1. Download the **installer** for a standard installation, or the **portable** executable to run without the installer.
2. Check the SHA-256 checksum against the file attached to that release.
3. Run the downloaded executable.

**The Windows files are not digitally signed.** Windows SmartScreen may display a warning. Do not disable Windows security protections; proceed only if you trust the source and have verified the download.

### Android

1. Use Android **8.0 or later** and keep **Android System WebView** up to date.
2. Download the APK from the Android release and verify its checksum.
3. If Android requests it, allow installation from the specific browser or file manager you used, then open the APK.
4. Revoke that installation permission afterwards if you do not need it.

This APK is installed manually; it is not a Google Play link. Back up important local data before updating. Update compatibility has not been newly tested as part of this publication.

## Catalogue and optional support

The catalogue is not restricted by supporter status. Support is optional; a valid supporter licence removes ads during its validity. Playback depends on content availability and network connectivity. Only access content you are authorised to watch.

## Download verification

Each release includes `SHA256SUMS.txt`. On Windows PowerShell:

```powershell
Get-FileHash .\CineOrbe-1.5.14-setup.exe -Algorithm SHA256
Get-FileHash .\CineOrbe-Android-1.5.17.apk -Algorithm SHA256
```

Compare the result with the checksum in the matching release. A matching checksum verifies file integrity, not code signing or a security audit.

## Feedback

Report bugs using [Issues](https://github.com/IstefaniOrbe/CineOrbe/issues). Include your platform, app version, and steps to reproduce. Do not post activation keys, payment details, personal data, or private credentials.

## Repository scope

This is a **downloads-only repository**, not an open-source publication. Executables are attached to GitHub Releases rather than committed to Git. Signing keys, key generators, internal tools, and server configuration are not published here. No new open-source licence is granted by this repository.
