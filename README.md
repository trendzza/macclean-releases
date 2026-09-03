<div align="center">

<img src="https://raw.githubusercontent.com/trendzza/macclean/main/MacClean/AppIcon.iconset/icon_256x256.png" width="128" height="128" alt="MacClean Icon" style="border-radius: 28px; box-shadow: 0 12px 32px rgba(0,0,0,0.15);"/>

# MacClean
### The surgical macOS cleaner built for speed, silence, and zero leftovers.

**Reclaim gigabytes of wasted storage, eliminate zombie background agents, and keep your Mac running as fast as the day you unboxed it.**

<br/>

[![macOS 13+](https://img.shields.io/badge/macOS-13%20%7C%20Sonoma%20%7C%20Sequoia-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/trendzza/macclean-releases/releases/latest)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-M1%20%2F%20M2%20%2F%20M3%20%2F%20M4%20%2F%20M5-0071E3?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/trendzza/macclean-releases/releases/latest)
[![Binary Size](https://img.shields.io/badge/Package%20Size-1.5%20MB-34C759?style=for-the-badge&logo=speedtest&logoColor=white)](https://github.com/trendzza/macclean-releases/releases/latest)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Offline%20%26%20Private-5856D6?style=for-the-badge&logo=icloud&logoColor=white)](https://github.com/trendzza/macclean-releases/releases/latest)

<br/>

<a href="https://github.com/trendzza/macclean-releases/releases/latest/download/MacClean.dmg">
  <img src="https://img.shields.io/badge/Download%20for%20macOS-MacClean.dmg-0071E3?style=for-the-badge&logo=apple&logoColor=white" height="42" alt="Download MacClean"/>
</a>
&nbsp;&nbsp;
<a href="#-interactive-tour">
  <img src="https://img.shields.io/badge/Explore%20Features-%E2%86%93-333333?style=for-the-badge" height="42" alt="Explore Features"/>
</a>

<p align="center">
  <sub>✨ Includes a 7-Day Unrestricted Free Trial • No Credit Card Required • Instant Download</sub>
</p>

</div>

---

## ⚡ Why MacClean?

Most "Mac cleaning" apps on the market today are sluggish, 200 MB Electron bloatware that spam you with notifications, ping foreign tracking servers, and play annoying fake vacuum sounds.

**MacClean was built on a different philosophy: native Swift, surgical precision, and absolute silence.**

| Feature | Typical Cleaning Apps | MacClean |
| :--- | :---: | :---: |
| **Download Size** | 150 MB – 250 MB | **1.5 MB (Instant)** |
| **Framework** | Sluggish Electron / Web Wrapper | **100% Pure SwiftUI & Darwin Kernel** |
| **Developer Waste Sweeper** | ❌ None | **✅ Xcode, Gradle, CocoaPods & npm** |
| **Startup Item Toggles** | Clunky & Destructive | **✅ Non-destructive `.plist.disabled`** |
| **Audio Feedback** | Annoying vacuum / beep noises | **🔇 100% Completely Silent** |
| **Telemetry & Tracking** | Trackers & Analytics SDKs | **🔒 0 Analytics • 100% Offline** |
| **Pricing** | \$40–\$60 / year recurring trap | **✨ Free 7-Day Trial • Lifetime Access** |

---

## 🖥️ Interactive Feature Tour

Click on any feature below to reveal how MacClean optimizes your machine:

<details>
<summary><b>⚡ Smart Care™ — Reclaim Gigabytes in One Click</b></summary>
<br/>

> **One click. Zero thinking. Zero danger.**

Smart Care instantly crawls temporary user caches, orphaned application logs, and developer build waste. It calculates safe-to-delete items and purges them straight to your macOS Trash — ensuring that if an app needs the cache again, it simply regenerates it on launch.

* **Reclaim 5 GB to 40 GB** of hidden clutter instantly.
* **Non-destructive safety**: Never touches documents, photos, code, or personal files.
* **Direct Trash integration**: Everything is moved to macOS Trash, giving you full undo control.

</details>

<details>
<summary><b>🗑️ Deep Uninstaller — 100% Zero-Leftover Guarantee</b></summary>
<br/>

> **When you drag an app to the Trash, up to 70% of its junk remains behind.**

Traditional macOS app deletion leaves hidden files in `~/Library/Application Support`, sandboxed container caches, daemon plists, and crash logs scattered across your drive. 

MacClean’s deep-inspection engine traces the app's bundle identifier across every dark corner of macOS:
* Deep discovery of hidden caches, support files, and preference files.
* Purges zombie background helper processes associated with uninstalled apps.
* Restores pristine system cleanliness in seconds.

</details>

<details>
<summary><b>🛠️ Developer Waste Sweeper — Built for Engineers & Creators</b></summary>
<br/>

> **If you use Xcode, Android Studio, VS Code, or npm, your Mac is hiding 20+ GB of obsolete build cache.**

Most cleanup utilities don't know how to handle developer tools without breaking them. MacClean safely scans and purges:
* **Xcode DerivedData**: Obsolete index files and build artifacts from old projects.
* **iOS Simulator Caches**: Ghost runtimes and device container logs.
* **Gradle & npm Caches**: Obsolete package manager caches that quietly consume storage.
* **CocoaPods Waste**: Legacy downloaded framework caches.

*Safeguard: MacClean cleans directory contents while preserving parent folder structures, ensuring your command-line tools never crash.*

</details>

<details>
<summary><b>🚀 Startup & Background Agent Manager — Quench Zombie Daemons</b></summary>
<br/>

> **Stop third-party apps from secretly launching background processes when your Mac starts.**

Over time, apps like updaters, launchers, and sync tools clutter your `LaunchAgents` directory, slowing down boot times and draining battery life.

* Inspect all active launch items in `~/Library/LaunchAgents` and `/Library/LaunchAgents`.
* **Safe iOS-Style Toggles**: Disable items without deleting them using macOS `.plist.disabled` mechanics.
* **Apple Shield**: Automatically locks and hides critical `com.apple.*` system processes to prevent accidental OS modification.

</details>

<details>
<summary><b>📊 Live Darwin Diagnostics — Direct Kernel Telemetry</b></summary>
<br/>

> **Exact hardware metrics pulled directly from Darwin & IOKit. Zero estimates.**

View live machine statistics with zero third-party utilities:
* **True Processor Identity**: e.g., `Apple M5` via POSIX kernel `sysctl`.
* **Battery & Power Condition**: Real-time charging state, AC power adapter health, and percentage via `IOKit.ps`.
* **Precise Uptime**: Uptime computed to the minute via `kern.boottime`.
* **Active Memory Pressure**: Live breakdown of active, wired, compressed, and free memory.

</details>

---

## 🔒 The Privacy First Architecture

MacClean never collects data, tracks behavior, or connects to external analytics services.

```
[ Your Mac ]  ──(Direct Local Disk Read)──>  [ MacClean Engine ]
     │                                                │
     └──(Zero Analytics • Zero Telemetry)─────────────┘
```

* **No Analytics SDKs**: No Google Analytics, no Mixpanel, no Sentry.
* **Completely Silent**: Designed for focused professionals — no chimes, beeps, or sounds.
* **Direct File Control**: No system extensions or kernel hacks. Operates cleanly within Apple’s standard POSIX and AppKit frameworks.

---

## 🚀 How to Install (30 Seconds)

1. **Download**: Grab the latest release: [**MacClean.dmg**](https://github.com/trendzza/macclean-releases/releases/latest/download/MacClean.dmg).
2. **Install**: Double-click `MacClean.dmg` and drag the icon to your `Applications` folder.
3. **Launch & Enjoy**: Open MacClean. Your **7-Day Free Trial** is already active out of the box!

> **💡 Smart Relocation**: If you simply double-click MacClean directly inside the DMG or your Downloads folder, our built-in assistant will automatically offer to move it to your Applications folder with one click.

---

## 💬 Frequently Asked Questions (FAQ)

<details>
<summary><b>Is MacClean safe to use? Will it delete my personal files?</b></summary>
<br/>
Yes, 100% safe. MacClean strictly targets temporary application caches, log files, and orphaned build artifacts that apps are architected to rebuild on demand. It never touches your Documents, Desktop, Photos, code repositories, or iCloud drive.
</details>

<details>
<summary><b>Does it work completely offline?</b></summary>
<br/>
Yes! MacClean requires zero internet connection to scan, clean, optimize, and manage your startup items. The only network request it ever makes is checking for software updates from this official GitHub release repository.
</details>

<details>
<summary><b>How does the 7-Day Free Trial work?</b></summary>
<br/>
Every new installation includes a 7-day unrestricted free trial. You get access to all features — including deep uninstallation, developer waste purging, and smart care. No credit card or account creation required.
</details>

<details>
<summary><b>How do updates work?</b></summary>
<br/>
MacClean features 1-click in-app background updating. When a new update is released, the app notifies you and allows you to update and relaunch in 2 seconds without ever visiting a web browser or mounting a DMG.
</details>

---

<div align="center">

### Ready to experience a faster, cleaner Mac?

<a href="https://github.com/trendzza/macclean-releases/releases/latest/download/MacClean.dmg">
  <img src="https://img.shields.io/badge/Download%20MacClean-Free%20Download-0071E3?style=for-the-badge&logo=apple&logoColor=white" height="46" alt="Download MacClean"/>
</a>

<br/><br/>

<sub>Crafted with precision for macOS. © 2026 MacClean. All rights reserved.</sub>

</div>
