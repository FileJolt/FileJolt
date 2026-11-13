<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/FileJolt-Logo-Dark-Mode.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/FileJolt-Logo-Light-Mode.png">
  <img src="assets/FileJolt-Logo-Dark-Mode.png" alt="FileJolt official logo" width="420">
</picture>

**One installer. Two independent Windows applications.**

Install **NexLoad** and **ReelShift** together or separately with one offline Windows setup application.

[**Download FileJolt**](https://github.com/FileJolt/FileJolt/releases/latest) · [**Version 1.0.0 release**](https://github.com/FileJolt/FileJolt/releases/tag/v1.0.0) · [**Report an issue**](https://github.com/FileJolt/FileJolt/issues)

</div>

---

## What is FileJolt?

**FileJolt** is a Windows x64 software installer that bundles two independent portable applications into one streamlined setup experience. Choose the software you want, select where it goes, and decide whether to create Desktop and Start Menu shortcuts—without downloading extra installers.

The installer uses FileJolt's **Professional Monochrome** interface with dedicated installation and removal flows.

## Included software

| Application | Version | What it does |
| --- | --- | --- |
| **[NexLoad](https://github.com/SleepyKevy/NexLoad)** | **1.0.0** | Windows media downloader built around yt-dlp and supporting tools such as FFmpeg, FFprobe, and Deno. |
| **[ReelShift](https://github.com/SleepyKevy/ReelShift)** | **1.1.0** | Renames and organizes movie, TV show, and subtitle files. |

You can install **NexLoad only**, **ReelShift only**, or **both** in one operation.

## Features

- **One offline installer** with both application packages included.
- **Flexible selection:** install either application or both.
- **Custom installation directory** for portable application folders.
- **Optional shortcuts** for the Desktop and Start Menu.
- **Custom FileJolt interface** for installation and removal.
- **Independent uninstallation:** remove one application or both together.
- **Shortcut cleanup** when removing applications.
- **User-data preservation:** removal is designed to leave personal application data intact.
- **No build tools required** for people installing the software.

## Download and install

1. Open the **[latest FileJolt release](https://github.com/FileJolt/FileJolt/releases/latest)**.
2. Under **Assets**, download **`FileJolt-Setup.exe`**.
3. Launch the installer, select NexLoad, ReelShift, or both, and choose your installation directory.
4. Choose your shortcut options and select **Install**.

> **System requirements:** Windows 11 x64 is the tested platform. The applications also require their normal Windows runtime components. Administrator privileges may be required for protected installation locations.

## Uninstalling

Open **Windows Settings → Apps → Installed apps** and use FileJolt's uninstall entry, or run **`FileJolt-Uninstall.exe`** from the installation location.

Choose the application or applications to remove. The custom uninstaller supports removing **both together**. The separate `FileJolt-UninstallEngine.exe` file is an internal component; do not launch it directly.

## Portable applications

FileJolt installs each selected application into its own folder. The **applications** retain their portable, folder-based design; the **installer** creates Windows integration such as shortcuts and uninstall entries.

Moving an application folder to another Windows PC may still require compatible system runtime components. Avoid protected directories if the applications need to write data beside their executable files.

## Release integrity

**File:** `FileJolt-Setup.exe`  
**Version:** `1.0.0`  
**SHA-256 (approved Windows build):**

```text
8A72619F6813F13137554044FEB03374B7B6430F770E37E2F6E32B8494E36418
```

To verify the downloaded installer, open PowerShell in the download directory and run:

```powershell
Get-FileHash .\FileJolt-Setup.exe -Algorithm SHA256
```

Compare the full result with the checksum above. If it does not match, **do not run the file**. The checksum applies to the approved `v1.0.0` installer and will change when the executable is rebuilt.

## Windows security notice

FileJolt 1.0.0 is **not digitally code-signed**. Windows SmartScreen may display an **Unknown Publisher** or reputation warning. A warning alone does not establish that a file is malicious or safe. Download only from the official release, check the SHA-256 checksum, and use your normal security precautions.

---

<div align="center">

**FileJolt 1.0.0** · Windows x64 · NexLoad + ReelShift

</div>
