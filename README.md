# TimeTab

Official downloads for **TimeTab**.

## Download

<!-- LATEST:START -->
**Latest: 1.0.0-beta** (2026-11-26), a beta (pre-release) version

| Platform | File | Size |
|---|---|---|
| Windows (x64), installer | [Timetab_1.0.0_x64-setup.exe](releases/1.0.0-beta/Timetab_1.0.0_x64-setup.exe) | 10.0 MB |
| Windows (x64), MSI package | [Timetab_1.0.0_x64_en-US.msi](releases/1.0.0-beta/Timetab_1.0.0_x64_en-US.msi) | 11.8 MB |
| Linux (x64), Debian / Ubuntu package | [dugt-app_1.0.0_amd64.deb](releases/1.0.0-beta/dugt-app_1.0.0_amd64.deb) | 12.5 MB |
| Linux (x64), AppImage (other distributions) | [dugt-app_1.0.0_x86_64.AppImage](releases/1.0.0-beta/dugt-app_1.0.0_x86_64.AppImage) | 12.4 MB |

The macOS build of 1.0.0-beta isn't available yet. Until then, use the [0.9.0-alpha macOS disk image](releases/0.9.0-alpha/Timetab_0.9.0_universal.dmg).

Linux requirements: the `.deb` needs Ubuntu 22.04 or Debian 12 or later (glibc 2.35+). The AppImage needs FUSE 2; make it executable with `chmod +x`, or run it with `--appimage-extract-and-run` if FUSE 2 isn't installed. The Linux builds are not signed.

macOS: open the `.dmg` and drag Timetab into Applications. The app is not signed with an Apple Developer ID or notarized, so macOS blocks it the first time you open it. To allow it, go to System Settings → Privacy & Security and click **Open Anyway**. If macOS says the app is damaged, run `xattr -dr com.apple.quarantine /Applications/Timetab.app` in Terminal, then open it again.
<!-- LATEST:END -->

## All versions

<!-- VERSIONS:START -->
| Version | Date | Platforms |
|---|---|---|
| [1.0.0-beta](releases/1.0.0-beta/) | 2026-11-26 | Windows (x64), Linux (x64) |
| [0.9.0-alpha](releases/0.9.0-alpha/) | 2026-11-21 | Windows (x64), Linux (x64), macOS (universal) |
<!-- VERSIONS:END -->

## Verify your download (optional)

Each version folder contains a `SHA256SUMS.txt` file.

```sh
# Linux / macOS (run inside the folder with the downloaded file)
sha256sum -c SHA256SUMS.txt --ignore-missing

# Windows (PowerShell): compare the output with SHA256SUMS.txt
Get-FileHash .\<file> -Algorithm SHA256
```

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
