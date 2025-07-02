# WinScript - Windows Optimization and Setup Script

This script is a comprehensive batch file designed to optimize, customize, and configure a Windows system. It includes system tweaks, UI changes, software installations, and privacy enhancements.

## 🛡️ Privilege Check
Ensures the script is run with administrator privileges. If not, it exits with a message.

## 💾 System Restore Point
Creates a restore point named `RestorePoint1` using PowerShell to allow rollback in case of issues.

## 🍫 Installing Chocolatey
Installs the Chocolatey package manager for Windows to facilitate software installation.

## 🗂️ File Explorer Tweaks
- Shows file extensions.
- Enables dark mode for apps and system.
- Restores the classic right-click context menu.

## 🧹 Taskbar and UI Cleanup
- Disables taskbar widgets and task view button.
- Disables Windows Feeds and News & Interests.
- Moves taskbar icons to the left.

## 🧼 System Cleanup
- Deletes temporary files and prefetch data.
- Disables the Superfetch (SysMain) service.

## 🧯 Crash and Boot Diagnostics
- Enables detailed BSOD (Blue Screen of Death) information.
- Enables verbose logon messages during startup and shutdown.

## 🔒 Privacy and Telemetry
- Disables Activity Feed.
- Disables automatic map downloads and network traffic.

## 👤 User Cleanup
- Deletes the default `defaultuser0` account if it exists.

## 🧹 Microsoft Edge Removal and Debloating
- Uninstalls Microsoft Edge using a remote PowerShell script.
- Applies multiple registry tweaks to disable Edge features and telemetry.

## 🧰 MAS Activation
- Executes a PowerShell command to run the MAS activation script from the web.

## 🔄 Environment Refresh
- Refreshes the environment variables using Chocolatey's `RefreshEnv.cmd`.

## 📦 Software Installation via Chocolatey
Installs the following applications:
- nvidia-display-driver
- firefox
- winrar
- ea-app
- epicgameslauncher
- goggalaxy
- steam
- ubisoft-connect
- powertoys
- eartrumpet
- spicetify-cli
- spotify
- discord
- adobereader
- sublimetext3

## ✅ Final Steps
- Restarts Windows Explorer.
- Ends the script cleanly.
