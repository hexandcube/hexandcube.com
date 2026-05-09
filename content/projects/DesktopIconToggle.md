---
title: DesktopIconToggle
date: 2021-06-19
lastmod: 2026-03-21
tagline: A lightweight system tray utility that allows you to instantly toggle Windows desktop icons with a double-click.
tags: ["Windows", "Tray application", "Utility", "c-sharp", ".net"]
license: mit
author: Hexandcube
licenseUrl: https://github.com/hexandcube/DesktopIconToggle/blob/main/LICENSE.md
projectType: software
status: Active
logo: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/_meta/logo-small.png
banner: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/_meta/banner.png
featuredIndex: 1
buttons:
  - title: View on GitHub
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/DesktopIconToggle

links:
  - title: Issue Tracker (GitHub)
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/DesktopIconToggle/issues
  - title: Chocolatey Package Repository
    url: https://community.chocolatey.org/packages/desktopicontoggle

install:
  - packageManager: chocolatey
    packageName: desktopicontoggle
  - packageManager: winget
    packageName: Hexandcube.DesktopIconToggle

versions:
  - name: DesktopIconToggle v.2.1.0
    versionNumber: 2.1.0
    type: release
    date: 2026-03-21
    notes: |
      ## What's new
      DesktopIconToggle now only allows one instance to run at the same time (fixes #5)
      Attempting to run another instance while one is already running, will cause the following messagebox to be displayed:
      <img width="413" height="159" alt="image" src="https://github.com/user-attachments/assets/c4f20e22-14dd-429e-a041-3163429c740c"/>

      ---

      **Full Changelog**: https://github.com/hexandcube/DesktopIconToggle/compare/v.2.0.0...v.2.1.0
    links:
      - name: GitHub
        icon: fa-brands fa-github
        url: https://github.com/hexandcube/DesktopIconToggle/releases/tag/v.2.1.0
      - name: Chocolatey Package Repository
          # icon: 
        url: https://community.chocolatey.org/packages/desktopicontoggle/2.1.0
    files:
      - fileName: DesktopIconToggle-Setup.exe
        description: DesktopIconToggle Installer
        fileSize: 2.06 MB
        icon: fa-regular fa-compact-disc
        hash: 009c19d02e756ea0d47cb6d7d7204bf95698a02b2d529603d7566246df0c86fa
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.2.1.0/DesktopIconToggle-Setup.exe
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.2.1.0/DesktopIconToggle-Setup.exe
      - fileName: DesktopIconToggle-x64.zip
        description: DesktopIconToggle Standalone for x86_64
        fileSize: 60.1 MB
        icon: fa-regular fa-file-zip
        hash: 7c8b557b1918252afb7f7143ab940199b071818cd9136e9320a8734784af6660
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.2.1.0/DesktopIconToggle-win_x64.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.2.1.0/DesktopIconToggle-win_x64.zip
      - fileName: DesktopIconToggle-arm64.zip
        description: DesktopIconToggle Standalone for ARM
        fileSize: 56.1 MB
        icon: fa-regular fa-file-zip
        hash: 76a4cf4cae5d1cec5b385ecf9633d514cc25515d0418f2194d317d762471dfef
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.2.1.0/DesktopIconToggle-win_arm64.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.2.1.0/DesktopIconToggle-win_arm64.zip

  - name: DesktopIconToggle v.2.0.0
    versionNumber: 2.0.0
    type: release
    date: 2026-03-19
    notes: |
      ## What's Changed
      The app has been rewritten from scratch in C# (.NET 8.0) and now uses proper Windows APIs.

      ## Upgrading
      It's recommended to uninstall any previously installed versions before upgrading to v.2.0.0.

      The app now requires .NET 8.0 Desktop Runtime to be installed. 
      If you're using the installer (DesktopIconToggle-Setup.exe), it should automatically install any required dependencies.

      You can also use a standalone Portable version (included in the ZIP) file, which is a self-contained executable that comes bundled with all necessary dependencies. 

      ---

      **Full Changelog**: https://github.com/hexandcube/DesktopIconToggle/compare/v.1.4.0...v.2.0.0
    links:
      - name: GitHub
        icon: fa-brands fa-github
        url: https://github.com/hexandcube/DesktopIconToggle/releases/tag/v.2.0.0
      - name: Chocolatey Package Repository
          # icon: 
        url: https://community.chocolatey.org/packages/desktopicontoggle/2.0.0
    files:
      - fileName: DesktopIconToggle-Setup.exe
        description: DesktopIconToggle Installer
        fileSize: 2.06 MB
        icon: fa-regular fa-compact-disc
        hash: 14243f9c5f22c7bd3fba312c3f086dbe1fab823d95dd672b0e29107ee5f4dd88
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.2.0.0/DesktopIconToggle-Setup.exe
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.2.0.0/DesktopIconToggle-Setup.exe
      - fileName: DesktopIconToggle-x64.zip
        description: DesktopIconToggle Standalone for x86_64
        fileSize: 60.1 MB
        icon: fa-regular fa-file-zip
        hash: 6e44f0a7ba21fa0b601c2a15e3d921f5a646e80b6655e343987b18af3a84a3e5
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.2.0.0/DesktopIconToggle-x64.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.2.0.0/DesktopIconToggle-x64.zip
      - fileName: DesktopIconToggle-arm64.zip
        description: DesktopIconToggle Standalone for ARM
        fileSize: 56.1 MB
        icon: fa-regular fa-file-zip
        hash: a8668c1a882e325b15a8e24b65dceef798d52c4c983b2c94d55ec235798e6386
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.2.0.0/DesktopIconToggle-arm64.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.2.0.0/DesktopIconToggle-arm64.zip

  - name: DesktopIconToggle v.1.4.0
    versionNumber: 1.4.0
    type: release
    date: 2023-09-30
    notes: |
      ## What's Changed
      * Allow icons to be toggled even when double-clicking over a hidden icon by @csc530 in https://github.com/hexandcube/desktop-icon-toggle/pull/4

      ## New Contributors
      * @csc530 made their first contribution in https://github.com/hexandcube/desktop-icon-toggle/pull/4

      **Full Changelog**: https://github.com/hexandcube/desktop-icon-toggle/compare/v.1.3.0...v.1.4
    links:
      - name: GitHub
        icon: fa-brands fa-github
        url: https://github.com/hexandcube/DesktopIconToggle/releases/tag/v.1.4.0
      - name: Chocolatey Package Repository
          # icon: 
        url: https://community.chocolatey.org/packages/desktopicontoggle/1.4.0
    files:
      - fileName: DesktopIconToggle-1.4.0_setup.exe
        description: DesktopIconToggle Installer (x86_64 only)
        fileSize: 1.96 MB
        icon: fa-regular fa-compact-disc
        hash: ee945494ad1d8ca7de1444c22d5563c93a5df8ef130a7ed7f856c17972aa99e5
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.4.0/DesktopIconToggle-1.4.0_setup.exe
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.4.0/DesktopIconToggle-1.4.0_setup.exe
      - fileName: DesktopIconToggle-1.4.0.zip
        description: DesktopIconToggle Standalone (x86_64 only)
        fileSize: 1.78 MB
        icon: fa-regular fa-file-zip
        hash: 954837d6578a099bb4f1333abf18721161bf275048209a5a471fbf6f76ec774c
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.4.0/DesktopIconToggle-1.4.0.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.4.0/DesktopIconToggle-1.4.0.zip

  - name: DesktopIconToggle v.1.3.0
    versionNumber: 1.3.0
    type: release
    date: 2022-01-26
    notes: |
      Updated the about box
    links:
      - name: GitHub
        icon: fa-brands fa-github
        url: https://github.com/hexandcube/DesktopIconToggle/releases/tag/v.1.3.0
      - name: Chocolatey Package Repository
          # icon: 
        url: https://community.chocolatey.org/packages/desktopicontoggle/1.3.0
    files:
      - fileName: DesktopIconToggle-1.3.0_setup.exe
        description: DesktopIconToggle Installer (x86_64 only)
        fileSize: 2.10 MB
        icon: fa-regular fa-compact-disc
        hash: bd7979a31a1db98a75b0343a22d70b0d8974e9c07b3321e373108fddc3340a88
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.3.0/DesktopIconToggle-1.3.0_setup.exe
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.3.0/DesktopIconToggle-1.3.0_setup.exe
      - fileName: DesktopIconToggle-1.3.0.zip
        description: DesktopIconToggle Standalone (x86_64 only)
        fileSize: 2.15 MB
        icon: fa-regular fa-file-zip
        hash: 113a027b3e896d4a78376f77ca778abbb7e7b22d8925baf71d3dbb1b38b58ecd
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.3.0/DesktopIconToggle-1.3.0.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.3.0/DesktopIconToggle-1.3.0.zip

  - name: DesktopIconToggle v.1.2.0
    versionNumber: 1.2.0
    type: release
    date: 2021-08-24
    notes: |
      Fixed an issue, that prevented users from renaming a file when the icons on desktop are visible, but the Show Desktop Icons option in the desktop context menu (View > Show Desktop Icons) is unchecked ([#1](https://github.com/hexandcube/DesktopIconToggle/issues/1)).
    links:
      - name: GitHub
        icon: fa-brands fa-github
        url: https://github.com/hexandcube/DesktopIconToggle/releases/tag/v.1.2.0
      - name: Chocolatey Package Repository
          # icon: 
        url: https://community.chocolatey.org/packages/desktopicontoggle/1.2.0
    files:
      - fileName: DesktopIconToggle-1.2.0_setup.exe
        description: DesktopIconToggle Installer (x86_64 only)
        fileSize: 2.08 MB
        icon: fa-regular fa-compact-disc
        hash: 90c661f3a1bda269bcd1c633ec572eb6895bb6f27744c2d8bca97766a8c01672
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.2.0/DesktopIconToggle-1.2.0_setup.exe
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.2.0/DesktopIconToggle-1.2.0_setup.exe
      - fileName: DesktopIconToggle-1.2.0.zip
        description: DesktopIconToggle Standalone (x86_64 only)
        fileSize: 2.10 MB
        icon: fa-regular fa-file-zip
        hash: bf315329cc008dbeec23f087488e23b4a0312d379c9c9ac6ea449c8c7a0763d6
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.2.0/DesktopIconToggle-1.2.0.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.2.0/DesktopIconToggle-1.2.0.zip

  - name: DesktopIconToggle v.1.1.0
    versionNumber: 1.1.0
    type: release
    date: 2021-07-22
    notes: |
      Initial release of DesktopIconToggle
    links:
      - name: GitHub
        icon: fa-brands fa-github
        url: https://github.com/hexandcube/DesktopIconToggle/releases/tag/v.1.1.0
      - name: Chocolatey Package Repository
          # icon: 
        url: https://community.chocolatey.org/packages/desktopicontoggle/1.1.0
    files:
      - fileName: DesktopIconToggle-1.1.0_Setup.exe
        description: DesktopIconToggle Installer (x86_64 only)
        fileSize: 2.08 MB
        icon: fa-regular fa-compact-disc
        hash: 6499fa62be814cc60de621c4b10ed937e5f89f16ea2104b43360bf1c3d0ea9de
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.1.0/DesktopIconToggle-1.1.0_Setup.exe
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.1.0/DesktopIconToggle-1.1.0_Setup.exe
      - fileName: DesktopIconToggle-1.1.0.zip
        description: DesktopIconToggle Standalone (x86_64 only)
        fileSize: 2.08 MB
        icon: fa-regular fa-file-zip
        hash: 2c4da81ade63f52d401485f1283432e39d92a3dfd63ea7ee7a0b0b17dbb6ae14
        download:
          - name: GitHub
            url: https://github.com/hexandcube/DesktopIconToggle/releases/download/v.1.1.0/DesktopIconToggle-1.1.0.zip
          - name: Floofware FS
            url: https://fs.floofware.net/hexandcube/projects/DesktopIconToggle/v.1.1.0/DesktopIconToggle-1.1.0.zip

noindex: false
draft: false
---

## Installation and Usage

### Using the installer

Simply download and launch the installer. The app should launch automatically after installation, and will autostart on boot.
You can also launch it manually from the Start Menu.

### Using a package manager (community packages)

You can install DesktopIconToggle using a package manager such as Chocolatey or Winget.

The app won't launch automatically after a silent install, you need to launch it manually from the Start Menu, or restart Windows for it to launch on startup.

### Standalone executable

The standalone executable is a portable version of the app that doesn't require installation.
Just download the zip file, extract it, and run the executable. The app will launch and start working immediately, but it won't autostart on boot.

In the standalone zip file, 2 different executables are provided:

- **STANDARD** (DesktopIconToggle-win_x64.exe / DesktopIconToggle-win_arm64.exe)

  Lightweight executable, requires [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) to be installed on your system

- **PORTABLE** (DesktopIconToggle-win_x64-Portable.exe / DesktopIconToggle-win_arm64-Portable.exe)

  A heavier, self-contained executable, includes all necessary dependencies.

## Attributions

Desktop icon by [Icons8](https://icons8.com/).

Special thanks to [all GitHub contributors](https://github.com/hexandcube/DesktopIconToggle/graphs/contributors).
