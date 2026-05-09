---
title: MicMonitor
date: 2022-01-28
lastmod: 2022-01-29
author: Hexandcube
tagline: Quickly toggle Microphone Monitoring in Windows
tags: ["Windows App", "AutoHotkey Script", "Tray Utility"]
projectType: software
status: Archived
license: mit
licenseURL: https://github.com/hexandcube/MicMonitor/blob/master/LICENSE
# icon:
logo: https://fs.floofware.net/hexandcube/projects/MicMonitor/_meta/logo-small.png
# banner:
# featuredIndex: 
showDonationbox: true

# images:
#   - title:
#     url:

buttons:
  - title: View on GitHub
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/MicMonitor
    style: primary

links:
  - title: Issue Tracker (GitHub)
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/MicMonitor/issues
  - title: Chocolatey Package Repository
    # icon: 
    url: https://community.chocolatey.org/packages/micmonitor

install:
    - packageManager: chocolatey
      packageName: micmonitor
    - packageManager: winget
      packageName: Hexandcube.MicMonitor

versions:
    - name: MicMonitor v.1.1.0
      versionNumber: 1.1.0
      type: release
      date: 2022-01-29
      notes: |
        - Added a menu item for changing the device
        - Now MicMonitor will ask the user for the name of the device on the first start
      links:
        - name: GitHub
          icon: fa-brands fa-github
          url: https://github.com/hexandcube/MicMonitor/releases/tag/v.1.1.0
        - name: Chocolatey Package Repository
          # icon: 
          url: https://community.chocolatey.org/packages/micmonitor/1.1.0
      files:
        - fileName: MicMonitor-1.1_setup.exe
          description: MicMonitor Installer (x86_64)
          fileSize: 2.09 MB
          icon: fa-regular fa-compact-disc
          hash: 025f0554d5ca6e817afa87563045ace46f401f0221023644303c835e7aada096
          download:
            - name: GitHub
              url: https://github.com/hexandcube/MicMonitor/releases/download/v.1.1.0/MicMonitor-1.1_setup.exe
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/MicMonitor/v.1.1.0/MicMonitor-1.1_setup.exe
        - fileName: MicMonitor-1.1.zip
          description: MicMonitor Standalone (x86_64)
          fileSize: 2.13 MB
          icon: fa-regular fa-file-zip
          hash: e41e625af59593a9e573d9da22ed42eea21e48895bac08e13f7138ca4d10e038
          download:
            - name: GitHub
              url: https://github.com/hexandcube/MicMonitor/releases/download/v.1.1.0/MicMonitor-1.1.zip
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/MicMonitor/v.1.1.0/MicMonitor-1.1.zip

    - name: MicMonitor v.1.0.0
      versionNumber: 1.0.0
      type: release
      date: 2022-01-28
      notes: Initial Release
      links:
        - name: GitHub
          icon: fa-brands fa-github
          url: https://github.com/hexandcube/MicMonitor/releases/tag/v.1.0.0
        - name: Chocolatey Package Repository
          # icon: 
          url: https://community.chocolatey.org/packages/micmonitor/1.0.0
      files:
        - fileName: MicMonitor-1.0_setup.exe
          description: MicMonitor Installer (x86_64)
          fileSize: 2.09 MB
          icon: fa-regular fa-compact-disc
          hash: 2109300a8341a151b6fcef287c577263950d94da99133438142ea27ee5edd5a3
          download:
            - name: GitHub
              url: https://github.com/hexandcube/MicMonitor/releases/download/v.1.0.0/MicMonitor-1.0_setup.exe
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/MicMonitor/v.1.0.0/MicMonitor-1.0_setup.exe
        - fileName: MicMonitor-1.0.zip
          description: MicMonitor Standalone (x86_64)
          fileSize: 2.13 MB
          icon: fa-regular fa-file-zip
          hash: 0a807cdc5b3883ae577d38e6f6713033430b53c83ccfb9defb86232595243b4d
          download:
            - name: GitHub
              url: https://github.com/hexandcube/MicMonitor/releases/download/v.1.0.0/MicMonitor-1.0.zip
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/MicMonitor/v.1.0.0/MicMonitor-1.0.zip

noindex: false
draft: false
---