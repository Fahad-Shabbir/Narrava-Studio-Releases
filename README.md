# Narrava Studio

Official Windows downloads and updates for **Narrava Studio** — a desktop app for long-form AI voiceovers.

**Workflow:** Script → Voice → Review → Export

## Download

Go to the [**Releases**](../../releases/latest) page and download the latest `NarravaStudio-Setup-*.msi` file under **Assets**.

## Install

1. Download the `.msi` file.
2. Double-click it and follow the installer.
3. Open **Narrava Studio** from the Start menu or desktop shortcut.

Windows may show a "Windows protected your PC" (SmartScreen) warning because the installer is not yet code-signed. If you downloaded it from this page, click **More info → Run anyway**.

## Requirements

- 64-bit Windows (x64)
- Internet connection for AI voice generation

## Updating

To update, download the newest installer from Releases and run it. It upgrades your existing installation in place. In-app update checking is planned for a future version.

## Verify your download (optional)

Each release includes a `SHA256SUMS.txt` file. In PowerShell:

```powershell
Get-FileHash .\NarravaStudio-Setup-v1_7_1.msi -Algorithm SHA256
```

The result should match the value in `SHA256SUMS.txt`.

## Support

Open an [issue](../../issues) to report a problem.

---
This repository contains release downloads only, not the application's source code.
