---
title: ShareLinkFx
date: 2026-11-01
lastmod: 2026-11-01
author: Hexandcube
tagline: An android app that automatically modifies shared links to use embed fixer services
tags: ["Android", "Utility", "Kotlin"]
projectType: android-app
status: Active
license: Apache-2.0
licenseURL: https://github.com/hexandcube/ShareLinkFx/blob/main/LICENSE.md
logo: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/logo.png
banner: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/banner.png
featuredIndex: 3
showDonationbox: true

images:
  - title: Banner
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/banner.png
  - title: Screenshot 1
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/phoneScreenshots/phoneScreenshot-1.png
  - title: Screenshot 2
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/phoneScreenshots/phoneScreenshot-2.png
  - title: Screenshot 3
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/phoneScreenshots/phoneScreenshot-3.png
  - title: Screenshot 4
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/phoneScreenshots/phoneScreenshot-4.png
  - title: Screenshot 5
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/phoneScreenshots/phoneScreenshot-5.png
  - title: Screenshot 6
    url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/_meta/phoneScreenshots/phoneScreenshot-6.png

buttons:
  - title: View project on GitHub
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/ShareLinkFx
    style: primary

links:
  - title: Source Code (GitHub)
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/ShareLinkFx
  - title: Issue Tracker (GitHub)
    icon: fa-brands fa-github
    url: https://github.com/hexandcube/ShareLinkFx/issues

versions:
    - name: ShareLinkFx v1.0.0
      versionNumber: 1.0.0
      type: release
      date: 2026-11-01
      notes: |
          ### Initial Release

          **Full Changelog**: https://github.com/hexandcube/ShareLinkFx/commits/v1.0.0
      links:
        - name: GitHub
          icon: fa-brands fa-github
          url: https://github.com/hexandcube/ShareLinkFx/releases/tag/v1.0.0
      files:
        - fileName: com.hexandcube.sharelinkfx_v1.0.0.apk
          description: Android App Package (APK)
          fileSize: 53.4 MB
          icon: fa-brands fa-android
          hash: e7dd1aee84837bb94642e67c1d785d7a00d3fa433ace039c72fb38530e44d1fa
          download:
            - name: GitHub
              url: https://github.com/hexandcube/ShareLinkFx/releases/download/v1.0.0/com.hexandcube.sharelinkfx_v1.0.0.apk
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/v1.0.0/com.hexandcube.sharelinkfx_v1.0.0.apk
        - fileName: com.hexandcube.sharelinkfx_v1.0.0.aab
          description: Android App Bundle (AAB)
          fileSize: 15.8 MB
          icon: fa-brands fa-android
          hash: 5a10d49a1f234415095d9eb9e24651d485dfedff0ea9a8f73753af7b39c2d929
          download:
            - name: GitHub
              url: https://github.com/hexandcube/ShareLinkFx/releases/download/v1.0.0/com.hexandcube.sharelinkfx_v1.0.0.aab
            - name: Floofware FS
              url: https://fs.floofware.net/hexandcube/projects/ShareLinkFx/v1.0.0/com.hexandcube.sharelinkfx_v1.0.0.aab

noindex: false
draft: false
---
# ShareLinkFx

**ShareLinkFx is a lightweight utility app that replaces shared social media URLs with embed fixer links, allowing for rich post previews in messaging apps like Telegram and Discord.**

Just share a link from a supported app directly to ShareLinkFx. The app will instantly modify the link and allow you to re-share it, no manual editing required.

### App Features:
* Restore Rich Embeds: Replace domains to bring back full post previews on Discord, Telegram, and other messaging platforms.
* Built-In Platform Support*: Bluesky, Twitter/X, Instagram, TikTok, Tumblr, and Mastodon
* Custom Embed Services: Create your own custom domain replacement rules for any website.
* Strip Tracking Parameters: Automatically remove extra URL parameters (like ?t=123) often used for user tracking.
* Remove Extra Text: Automatically strip away annoying promotional text injected by social apps, returning just the clean link.
* Custom Share Behavior: Choose what happens after a link is fixed - copy to clipboard, open the share sheet, or both.

ShareLinkFx is free and open-source. You can view the source code, report issues, or contribute on GitHub: https://github.com/hexandcube/sharelinkfx

***Disclaimer**: Suggested in-app embed fixer services are examples of commonly used third-party services. They are provided by independent third parties and are not affiliated with or endorsed by the developer of ShareLinkFx.