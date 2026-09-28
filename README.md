# Adobe Installer

A one-stop download and update channel for **Adobe Installer** — install and manage extensions, scripts, presets, and plug-ins for Adobe apps, including After Effects and Premiere Pro.

## Download

Choose your download from [Releases](https://github.com/iboyshanto/Adobe-Installer/releases/latest):

- **Windows x64:** [Download the 1.3.0 installer (.exe)](https://github.com/iboyshanto/Adobe-Installer/releases/download/v1.3.0/Adobe-Installer-win32-x64-1.3.0.exe). Run Setup and choose the installation folder. The installer provides Start menu and Desktop shortcuts.
- **Apple Silicon macOS:** [Download the 1.3.0 app (.zip)](https://github.com/iboyshanto/Adobe-Installer/releases/download/v1.3.0/Adobe-Installer-darwin-arm64-1.3.0.zip).

The Windows installer is not Authenticode code-signed. Automated and package integrity checks passed; native Windows installation and update testing is still pending. Intel Mac and native Windows ARM64 packages are not currently provided.

For macOS, unzip the download and move **Adobe Installer.app** into Applications. The Mac package supports Apple Silicon Macs. The app is ad-hoc signed, not Apple-notarized.

## Features

- Install supported Adobe assets from files, folders, or ZIP archives.
- Discover existing installed assets, search by name, and filter by type.
- Review changes before uninstalling or replacing assets.
- Check for app updates, download inside the app, and restart to install.

## Updates

Open **Updates** in the app footer to check manually. The app also checks automatically. When an update is available, choose **Download update**, then **Restart & install** when you are ready. Active install/uninstall operations must finish first. Downloads are checked against a signed manifest and SHA-256 checksum before installation.

Older versions without the Updates button need a one-time manual installation of the latest release.

## Repository contents

This repository contains **public downloads, update metadata, and documentation only**. Application source code, build scripts, credentials, and release signing keys are not published here. GitHub's automatically generated “Source code” archives contain only this repository's documentation, not the application source.

Report issues through [GitHub Issues](https://github.com/iboyshanto/Adobe-Installer/issues).

Adobe Installer is an independent utility by Mograph School. Adobe product names identify supported applications; this is not an official Adobe product.
