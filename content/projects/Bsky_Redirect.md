---
title: Bsky Redirect
date: 2026-06-12
lastmod: 2026-06-12
author: Hexandcube
tagline: Redirect bsky.app links to your preferred custom client
tags: ["Chrome extension"]
projectType: browser-extension
status: Active
license: apache-2.0
licenseURL: https://github.com/hexandcube/bsky-redirect/blob/main/LICENSE.md
# icon: 
logo: https://fs.floofware.net/hexandcube/projects/Bsky_Redirect/_meta/logo-small.png
# banner: https://fs.floofware.net/hexandcube/projects/Bsky_Redirect/_meta/marquee-tile.png
# featuredIndex: 
showDonationbox: true

images:
  - title: Bsky Redirect Options
    url: https://fs.floofware.net/hexandcube/projects/Bsky_Redirect/_meta/screenshot.png

buttons:
  - title: View on Chrome Web Store
    icon: fa-brands fa-chrome
    url: https://chromewebstore.google.com/detail/bsky-redirect/dbgfoajdpgadnkigojkncgegfhjkbkbd
    style: primary

links:
  - title: Source Code (GitHub)
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/bsky-redirect

versions:
    - name: Bsky Redirect v.1.0
      versionNumber: '1.0'
      type: release
      date: 2026-06-12
      notes: |
        Initial release
      links:
        - name: Chrome Web Store
          icon: fa-brands fa-chrome
          url: https://chromewebstore.google.com/detail/bsky-redirect/dbgfoajdpgadnkigojkncgegfhjkbkbd
      files:
        - fileName: bsky_redirect-1.0.crx 
          description: Chromium Extension (Signed CRX)
          fileSize: 12.7 KB
          icon: fa-regular fa-puzzle-piece
          hash: d8a1b0943a01855c3701e5b8d1a1cdee429368aaa7abe86711a277303211b458
          download:
            - name: Chrome Web Store
              url: https://chromewebstore.google.com/detail/bsky-redirect/dbgfoajdpgadnkigojkncgegfhjkbkbd
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/Bsky_Redirect/bsky-redirect_1.0.crx

        - fileName: bsky_redirect-1.0.zip
          description: Chromium Extension (Source ZIP, Unsigned)
          fileSize: 9.87 KB
          icon: fa-regular fa-file-zip
          hash: 999df49e740add3a035bf3ec345abe8a41fcc4303cb111ac9931c7a02a23e3e6
          download:
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/Bsky_Redirect/bsky-redirect_1.0.zip

noindex: false
draft: false
---

# Bsky Redirect

Redirect bsky.app links to your preferred custom client

This extension allows you to redirect bsky.app links to your preferred custom client (assuming it supports the social-app URL scheme). 

By default the extension redirects to `witchsky.app`. To configure click on the extension icon.