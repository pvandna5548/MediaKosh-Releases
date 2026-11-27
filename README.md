# MediaKosh (मीडियाकोष)

**MediaKosh** is a privacy-first, 100% offline Windows media and PDF studio. Files are processed locally on your device: **zero uploads, zero trackers**.

## Downloads

- **Windows x64 Installer:** [MediaKosh-Setup-x64.exe](https://github.com/pvandna5548/MediaKosh-Releases/releases/latest/download/MediaKosh-Setup-x64.exe)
- **SHA-256 Checksums:** [SHA256SUMS.txt](https://github.com/pvandna5548/MediaKosh-Releases/releases/latest/download/SHA256SUMS.txt)
- **Web PWA:** [mediakosh-web.pages.dev](https://mediakosh-web.pages.dev/)

## Windows installation and verification

If Windows SmartScreen displays **Windows protected your PC**, new or unsigned indie apps may have limited reputation. If you have verified the release source and checksum and choose to proceed, click **More info → Run anyway**.

To verify the downloaded installer in PowerShell (from its download folder):

```powershell
Get-FileHash MediaKosh-Setup-x64.exe -Algorithm SHA256
```

Compare the SHA-256 result with the published checksum file.

## Platforms and privacy

- Windows 10/11, x64: installer (.exe) only.
- Android and iOS: coming soon.
- No macOS (.dmg) release.
- Zero trackers and zero uploads. Media processing is designed to remain on-device.

---
