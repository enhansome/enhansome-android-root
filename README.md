<div align="center" class="intro-header">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="docs/public/images/logo.svg">
  <source media="(prefers-color-scheme: dark)" srcset="docs/public/images/logo_dark.svg">
  <img src="docs/public/images/logo.svg" alt="Awesome Android Root Logo" width="120" height="120" />
</picture>

# Awesome Android Root with stars

**🛡️ The Ultimate Android Rooting Hub**

<sub>Discover 500+ top root apps, Magisk/ KernelSU/ LSPosed(xposed) modules & step-by-step guides for every device.</sub>

[![GitHub Repo stars](https://img.shields.io/github/stars/awesome-android-root/awesome-android-root?logo=github\&style=for-the-badge\&color=blue\&cacheSeconds=3600)](https://github.com/awesome-android-root/awesome-android-root) ⭐ 4,460 | 🐛 1 | 🌐 Python | 📅 2026-09-04 [![Total Entries](https://img.shields.io/badge/Apps%20%26%20Modules-500+-blue?style=for-the-badge\&logo=android\&cacheSeconds=3600)](#root-apps-and-modules) [![Codeberg Mirror](https://img.shields.io/badge/Codeberg-Mirror-2185D0?style=for-the-badge\&logo=codeberg\&logoColor=white)](https://codeberg.org/awesome-android-root/awesome-android-root/)

</div>
<div align="center" class="quick-nav">

[Introduction](#introduction) | [Rooting Guides](#rooting-guides) | [Apps & Modules](#root-apps-and-modules) | [Support](#resources-and-help)

</div><br>
<div class="mob-tip">

> 💡 **TIP:** Use   [![Web App](https://img.shields.io/badge/Web-App%E2%86%97-yellow?style=flat-square\&logo=googlechrome\&logoColor=white\&labelColor=blue)](https://awesome-android-root.zhoe.org)   for better navigation and search.

</div><br>

### Table of Contents

<details>
<summary>👉 Tap to expand complete navigation</summary>

<div class="toc-overview">

### 📚 Overview

* [Introduction](#introduction)
* [Rooting Guides](#rooting-guides)
* [Device-Specific Guides](#device-specific-guides)

</div>

### 📚 Glossary

* [Glossary](#glossary)

### ⭐ Featured Essentials

* [Starter Kit: Must have Apps](#starter-kit-must-have-apps)

### 📱 Root Apps by Category

#### 🛠️ **Root & Module Management**

* [Root Managers](#root-managers)
* [Temporary Root (Locked Bootloader)](#temporary-root-locked-bootloader)
* [Module Managers](#module-managers)
* [Metamodules](#metamodules)
* [LSPosed & Xposed](#lsposed-xposed)
* [Zygisk](#zygisk)
* [Root Hiding & Play Integrity](#root-hiding-play-integrity)
* [Bootloop Protection](#bootloop-protection)
* [Root Detection & Testing](#root-detection-testing)

#### ⚙️ **System Management**

* [System Tweaks](#system-tweaks)
  * [VBMeta Mods](#vbmeta-mods)
* [System UI & Framework](#system-ui-framework)
  * [AOSP (Android Open Source Project)](#aosp-android-open-source-project)
  * [ColorOS (Oppo)](#coloros-oppo)
  * [HyperOS (Xiaomi)](#hyperos-xiaomi)
  * [NothingOS](#nothingos)
  * [One UI (Samsung)](#one-ui-samsung)
  * [Onyx](#onyx)
  * [Oxygen OS (OnePlus)](#oxygen-os-oneplus)
  * [ZUI](#zui)
* [Boot & Startup](#boot-startup)
* [Debloating](#debloating)
* [App & Package Management](#app-package-management)
* [Permissions & AppOps](#permissions-appops)
* [System Information & Diagnostics](#system-information-diagnostics)

#### ⚡ **Performance & Battery**

* [Performance Optimization](#performance-optimization)
* [Kernel Management](#kernel-management)
* [Memory & RAM](#memory-ram)
* [Battery Optimization](#battery-optimization)
* [Charging & Power](#charging-power)
* [Task & Process Management](#task-process-management)

#### 🛡️ **Privacy & Security**

* [Ad & Tracker Blocking](#ad-tracker-blocking)
* [Firewalls & Filtering](#firewalls-filtering)
* [Privacy Tools](#privacy-tools)
* [Security Tools](#security-tools)
* [Device ID & Spoofing](#device-id-spoofing)
* [App Isolation](#app-isolation)

#### 🔧 **Apps & App Modifications**

* [App Patchers](#app-patchers)
* [App Mods](#app-mods)
* [Social Media Mods](#social-media-mods)
* [Browser Mods](#browser-mods)
* [YouTube & Media Mods](#youtube-media-mods)
* [Signature & Verification](#signature-verification)

#### 🗃️ **Storage & Data**

* [File Managers](#file-managers)
* [Backup & Restore](#backup-restore)
* [Cleaning](#cleaning)
* [File & Partition Tools](#file-partition-tools)

#### 🎨 **UI & Customization**

* [Themes & Visual Mods](#themes-visual-mods)
* [Launchers & Home Screen](#launchers-home-screen)
* [Status Bar & Navigation](#status-bar-navigation)
* [Gestures & Controls](#gestures-controls)
* [Fonts & Emojis](#fonts-emojis)
* [Notifications](#notifications)
* [Lockscreen & AOD](#lockscreen-aod)
* [Screen & Display](#screen-display)

#### 🎵 **Audio & Media**

* [Audio Enhancement](#audio-enhancement)
* [Audio Control](#audio-control)
* [Audio Effects](#audio-effects)

#### 🌐 **Network & Connectivity**

* [DNS & Network Filtering](#dns-network-filtering)
* [VPN & Proxy](#vpn-proxy)
* [Network Tools](#network-tools)
* [Wi-Fi & Mobile Data](#wi-fi-mobile-data)
* [Bluetooth & NFC](#bluetooth-nfc)
* [Location & GPS](#location-gps)

#### 🎮 **Gaming**

* [Gaming Optimization](#gaming-optimization)
* [Game Modifications & Tools](#game-modifications-tools)

#### 📥 **Developer & Power User**

* [Terminal & Shell](#terminal-shell)
* [ADB & Debugging](#adb-debugging)
* [Developer Tools](#developer-tools)
* [Linux Environments](#linux-environments)
* [Automation](#automation)
* [Hardware & Sensors](#hardware-sensors)

#### 🧰 **General Utilities**

* [Sync & File Transfer](#sync-file-transfer)
* [Reboot & Power](#reboot-power)
* [Sharing & Intent Tools](#sharing-intent-tools)
* [Communication & Messaging](#communication-messaging)
* [General Toolboxes](#general-toolboxes)

### 📚 Support and Safety

* [Resources and Help](#resources-and-help)
* [Legal and Safety](#legal-and-safety)
* [Support us](#contribute-and-participate)

</details>

***

<div class="root-intro">

## Introduction

### What is Android Rooting?

Rooting grants **superuser access** to Android, enabling deep customization, bloatware removal, and performance tuning. Think of it as gaining **Administrator** or **sudo** rights for your mobile device.

### Why Root?

* **Control** - [Remove preinstalled bloat](./docs/general-guides/android-apps-debloating.md), disable telemetry
* **Performance** - Tune CPU, GPU, battery, animations with [optimization tools](#performance-optimization)
* **Privacy** - [Block trackers](./docs/general-guides/android-adblocking.md), restrict app permissions
* **Customization** - Change UI, [fonts](#fonts-emojis), [boot animations](#boot-startup), navigation

| **Benefits**          | **Risks**                    |
| :-------------------- | :--------------------------- |
| Ad-blocking & Privacy | May void warranty            |
| Bloatware removal     | Security risks if misused    |
| Full data backups     | OTA update friction          |
| Performance tuning    | Banking app detection        |
| Deep customization    | Bootloader unlock wipes data |

***

</div>

<div align="center" class="readme-guides">

# Rooting Guides

[![Master Rooting Guide](https://img.shields.io/badge/Master--Rooting-Guide-blue?style=for-the-badge\&cacheSeconds=3600)](./docs/rooting-guides/index.md)

> Ensure you are prepared: [Preparation Checklist](https://fynks.github.io/check-list/)

</div>

<div class="readme-guides-steps">

## The 4-Step Rooting Roadmap

1. **[Unlock Bootloader](./docs/rooting-guides/how-to-unlock-bootloader.md)**: Required for all system modifications.

2. **[Install Recovery](./docs/rooting-guides/how-to-install-custom-recovery.md)**: Flash TWRP or OrangeFox to manage mods.

3. **Choose Root Method**:

   | Method       | Best For       | Guide                                            |
   | :----------- | :------------- | :----------------------------------------------- |
   | **Magisk**   | Most Users     | [Guide](./docs/rooting-guides/magisk-guide.md)   |
   | **KernelSU** | Stealth/Kernel | [Guide](./docs/rooting-guides/kernelsu-guide.md) |
   | **APatch**   | New Devices    | [Guide](./docs/rooting-guides/apatch-guide.md)   |

   > 💡 *Compare them all: [Root Solutions Comparison](./docs/rooting-guides/index.md#root-solutions-comparison)*

4. **Post-Root Setup**:
   * [LSPosed Framework](./docs/rooting-guides/lsposed-guide.md) (Customization)
   * [Ad-Blocking](./docs/general-guides/android-adblocking.md) & [Debloating](./docs/general-guides/android-apps-debloating.md)
   * [Root Hiding and Play Integrity](./docs/rooting-guides/index.md#root-hiding-play-integrity-resources) (for Banking/Integrity)

## Device-Specific Guides

[Google Pixel](./docs/rooting-guides/how-to-root-pixel-phone.md) • [Samsung](./docs/rooting-guides/how-to-root-samsung-phone.md) • [Xiaomi/HyperOS](./docs/rooting-guides/how-to-root-xiaomi-phone.md) • [OnePlus](./docs/rooting-guides/how-to-root-oneplus-phone.md) • [Nothing](./docs/rooting-guides/how-to-root-nothing-phone.md) • [Motorola](./docs/rooting-guides/how-to-root-motorola-phone.md)

## Additional Resources

* [LSPosed Framework Guide](./docs/rooting-guides/lsposed-guide.md)
* [Custom ROMs Installation](./docs/rooting-guides/custom-rom-installation.md)
* [Root Without Unlocking the Bootloader (GhostLock Temporary Root)](./docs/rooting-guides/root-without-unlocking-bootloader.md)
* **[📚 View All Rooting Tutorials ➞](./docs/rooting-guides/index.md)**

[↑ Back to top](#table-of-contents)

***

</div>

<div align="center" class="readme-apps-intro">
<br><br>

# Root Apps and Modules

![Apps & Modules](https://img.shields.io/badge/Apps%20&%20Modules%20​-500+-blue?style=for-the-badge\&logo=stackblitz\&cacheSeconds=3600)

</div><br />

> \[!TIP]
> **Start with our [Complete Rooting Guide](../rooting-guides/)** before exploring apps below.
> For privacy-friendly installs, use the F-Droid ecosystem: install [Droid-ify](https://github.com/Droid-ify/client/releases) ⭐ 7,362 | 🐛 191 | 🌐 Kotlin | 📅 2026-09-04 (modern F-Droid client) and enable the [IzzyOnDroid](https://apt.izzysoft.de/fdroid/) repo for many additional packages.

> \[!NOTE]
> Clicking an app/module entry opens its **Source Code** page (GitHub/GitLab etc.) for `FOSS` apps, otherwise the **Google Play Store** listing.

***

## Glossary

### Entry Tags

| Tag           | Meaning                                                  |
| :------------ | :------------------------------------------------------- |
| ⭐             | Community-recommended (most trusted/popular in category) |
| `FOSS`        | Free and Open Source Software (source code available)    |
| `Proprietary` | Closed-source software or unclear licensing              |

### Framework & Module Badges

| Badge   | Framework               | Requires                                        |
| :------ | :---------------------- | :---------------------------------------------- |
| `[M]`   | Magisk Module           | [Magisk](../rooting-guides/magisk-guide.md)     |
| `[K]`   | KernelSU Module         | [KernelSU](../rooting-guides/kernelsu-guide.md) |
| `[A]`   | APatch Module           | [APatch](../rooting-guides/apatch-guide.md)     |
| `[LSP]` | LSPosed / Xposed Module | [LSPosed](../rooting-guides/lsposed-guide.md)   |

### Store & Source Icons

| Icon | Source                             |
| :--- | :--------------------------------- |
| 🌱   | Available on F-Droid / IzzyOnDroid |
| ▶️   | Available on Google Play Store     |

### Ordering of Entries

1. ⭐ (Community-recommended) entries first
2. Alphabetical order within each (sub-)category

<details>
<summary><b>📚 Common Rooting Terms</b></summary>

* **Bootloader** - Low-level software that starts your OS (must be unlocked for root)
* **Temporary Root** - Root that exists in memory for the current boot only (e.g. GhostLock/CVE-2026-43499 tools); lost on reboot, no bootloader unlock needed
* **Recovery** - Special mode for system modifications (TWRP, CWM)
* **Systemless Root** - Root method that doesn't modify system partition
* **Zygisk** - Feature for advanced app hooking and hiding
* **DenyList** - Feature to hide root from specific apps
* **Play Integrity** - Google's security check (replacing SafetyNet)
* **Knox** - Samsung's security platform (trips when bootloader unlocked)

</details><br>

***

## Starter Kit: Must have Apps

|                                                                              App                                                                             | Why it's essential                                       |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------- |
|       **[Magisk](https://github.com/topjohnwu/Magisk) ⭐ 62,586 \| 🐛 36 \| 🌐 Kotlin \| 📅 2026-09-04** <br><small> `Root & Module Management` </small>      | If you chose Magisk, this is your manager.               |
| **[App Manager](https://github.com/MuntashirAkon/AppManager) ⭐ 8,889 \| 🐛 202 \| 🌐 Java \| 📅 2026-09-04** <br><small> `App & Package Management` </small> | Inspect and manage apps with root privileges.            |
|                                         **[MiXplorer](https://mixplorer.com/)** <br><small> `Storage & Data` </small>                                        | A powerful file manager with full root access.           |
|                                          **[AdAway](https://adaway.org/)** <br><small> `Privacy & Security` </small>                                         | Open-source system-wide ad blocker.                      |
|                       **[Droid-ify](https://f-droid.org/packages/com.looker.droidify)** <br><small> `App & Package Management` </small>                      | A modern F-Droid client for installing open-source apps. |

[↑ Back to top](#table-of-contents)

***

## Root & Module Management

### Root Managers

* **[⭐ Magisk](https://github.com/topjohnwu/Magisk) ⭐ 62,586 | 🐛 36 | 🌐 Kotlin | 📅 2026-09-04** - Manage Magisk modules and root permissions. `FOSS`
* **[⭐ KernelSU](https://github.com/tiann/KernelSU) ⭐ 18,219 | 🐛 71 | 🌐 Kotlin | 📅 2026-09-04** - A Kernel based root solution for Android. `FOSS`
* **[APatch](https://github.com/bmax121/APatch) ⭐ 7,899 | 🐛 47 | 🌐 Kotlin | 📅 2026-09-04** - The patching of Android kernel and Android system. `FOSS` | [🌱](https://f-droid.org/packages/me.bmax.apatch/)
* **[SukiSU-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra) ⭐ 6,206 | 🐛 26 | 🌐 Kotlin | 📅 2026-09-01** - A kernel-based root solution for Android devices, forked from `KernelSU` with some useful changes. `FOSS`
* **[KernelSU-next](https://github.com/KernelSU-Next/KernelSU-Next) ⭐ 4,195 | 🐛 23 | 🌐 Kotlin | 📅 2026-09-04** - An advanced Kernel based root solution for Android. `FOSS`
* **[ReSukiSU](https://github.com/ReSukiSU/ReSukiSU) ⭐ 1,396 | 🐛 8 | 🌐 Kotlin | 📅 2026-09-04** - Fork of SukiSU-Ultra with additional features. `FOSS`
* **[FolkPatch](https://github.com/LyraVoid/FolkPatch) ⭐ 1,094 | 🐛 31 | 🌐 Kotlin | 📅 2026-09-04** - A Root management tool focused on interface optimization and feature extension, based on APatch. `FOSS`

### Temporary Root (Locked Bootloader)

<details>

<summary><strong>What is temporary root (GhostLock)?</strong></summary>

Exploits like **GhostLock (CVE-2026-43499)** - a 15-year-old Linux kernel bug - grant root **in memory only**, for the current boot. No bootloader unlock, no flashing, no Knox trip, no data wipe: reboot and the device is bone-stock again. The trade-offs: root doesn't survive reboots, you can't flash ROMs/recoveries, and it only works on specific devices running firmware up to \~the June 2026 patch level.

<br>
</details>

* **[⭐ Root My Galaxy](https://github.com/BuSung-dev/Root-My-Galaxy) ⭐ 1,091 | 🐛 455 | 🌐 Kotlin | 📅 2026-09-03** - One-tap temporary root for Snapdragon Galaxy flagships (S24/S25 series, S24 FE, A56...) via GhostLock; bootloader stays locked, Knox isn't tripped. `FOSS`
* **[GhostLock App](https://github.com/YuKongA/ghostlock-app) ⭐ 711 | 🐛 43 | 🌐 C | 📅 2026-09-04** - One-tap execution app for the GhostLock (CVE-2026-43499) exploit. `FOSS`
* **[Root-My-Galaxy-Payloads](https://github.com/BuSung-dev/Root-My-Galaxy-Payloads) ⭐ 375 | 🐛 193 | 🌐 C | 📅 2026-09-03** - Signed device profiles, exploit payloads, and KernelSU artifacts that Root My Galaxy fetches at runtime. `FOSS`
* **[ghostlock-oneplus](https://github.com/JoinChang/ghostlock-oneplus) ⭐ 324 | 🐛 19 | 🌐 C | 📅 2026-09-03** - GhostLock kernel exploit for OnePlus/OPPO/realme (and some Xiaomi) devices with locked bootloader; installs KernelSU with runtime kernel auto-detection. `FOSS`
* **[Root My Pixel](https://github.com/alex193a/Root-My-Pixel) ⭐ 310 | 🐛 18 | 🌐 Kotlin | 📅 2026-09-04** - Jailbreak supported Google Pixel phones with GhostLock; stages the payload via Shizuku, no PC needed. `FOSS`
* **[QuestStack](https://github.com/starseed12345/QuestStack) ⭐ 172 | 🐛 0 | 🌐 C# | 📅 2026-08-28** - Unlocks the Meta Quest 1 bootloader and gains root using GhostLock + CVE-2021-1931. `FOSS`
* **[IonStack-S22U](https://github.com/sarabpal-dev/IonStack-S22U) ⭐ 65 | 🐛 11 | 🌐 C | 📅 2026-09-03** - Full CVE-2026-43499 exploit chain for the Samsung Galaxy S22 Ultra (5.10 kernel). `FOSS`
* **[oppo-ghostlock](https://github.com/pubglite55/oppo-ghostlock) ⭐ 63 | 🐛 4 | 🌐 C | 📅 2026-08-08** - GhostLock exploit adaptation for the OPPO Find N2. `FOSS`
* **[GhostLock-Galaxy](https://github.com/wxxsfxyzm/GhostLock-Galaxy) ⭐ 19 | 🐛 1 | 🌐 C | 📅 2026-08-10** - GhostLock app for the Samsung Galaxy Z Fold6 (kernel 6.1); stages via Shizuku or `adb shell` with per-kernel offset matching. `FOSS`
* **[GhostLock-5.10](https://github.com/R0rt1z2/GhostLock-5.10) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2026-08-21** - GhostLock kernel root exploit for some 5.X-kernel devices, mostly Amazon (from the Kaeru/Fenrir developer). `FOSS`
* **[Root My Device](https://github.com/Witaqua-tools/Root-My-Device) ⭐ 15 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-29** - Community fork of Root My Galaxy generalized beyond Samsung, with its own payload feed. `FOSS`
* **[pixel-ksu-root](https://github.com/JingMatrix/pixel-ksu-root) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2026-09-01** - ADB-driven KernelSU loader for stock Pixels; temporary kernel R/W via GhostLock, then late-loads a signature-matched `kernelsu.ko`. Manager-agnostic. `FOSS`
* **[iQOO Z9 5G / vivo T3 5G Root](https://github.com/ankitrawatgit/iQOO-Z9_5G-vivo-T3_5G-Root-GhostLock) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2026-09-01** - One-tap root app and payloads for the iQOO Z9 5G and vivo T3 5G (Dimensity 7200, kernel 5.15). `FOSS`

> \[!TIP]
> See the dedicated guide **[Root Without Unlocking the Bootloader](./docs/rooting-guides/root-without-unlocking-bootloader.md)** for what GhostLock can and can't do, device support, and every app, exploit port, and research project. Also see [Bootloader Mods & Temporary Root Solutions](./docs/rooting-guides/temporary-root-solutions.md) for related locked-bootloader approaches (Kaeru, Fenrir).

### Module Managers

* **[⭐ MMRL](https://github.com/DerGoogler/MMRL) ⭐ 2,154 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-18** - An Android app that helps manage your own modules repository. `FOSS` `[M]` `[K]` `[A]` | [🌱](https://f-droid.org/en/packages/com.dergoogler.mmrl/) | [▶️](https://play.google.com/store/apps/details?id=com.dergoogler.mmrl)
* **[KPatch Next Module](https://github.com/KernelSU-Next/KPatch-Next-Module) ⭐ 482 | 🐛 8 | 🌐 JavaScript | 📅 2026-03-05** - Standalone implementation of KPM (KernelSU Patch Module) support for Magisk/KernelSU with WebUI. `FOSS` `[M]` `[K]`
* **[Magisk Manager for Recovery Mode](https://github.com/Rikj000/Magisk-Manager-for-Recovery-Mode) ⭐ 290 | 🐛 0 | 🌐 Shell | 📅 2026-04-04** - Easily manage your Magisk Modules from a terminal session in your custom recovery. `FOSS` `[M]`

### Metamodules

> \[!NOTE]
> **Metamodules** provides the core mounting infrastructure for the module system. Unlike regular modules that modify system files, metamodules control *how* regular modules are installed and mounted.

* **[Meta-hybrid\_mount](https://github.com/YuzakiKokuban/meta-hybrid_mount) ⭐ 1,531 | 🐛 2 | 🌐 Rust | 📅 2026-09-04** - Three-engine mount orchestration (OverlayFS + Magic Mount + Kasumi LKM) with conflict monitor, SolidJS WebUI, auto-fallback, and EROFS storage backend support. `FOSS` `[K]` `[A]`
* **[⭐ Mountify](https://github.com/backslashxx/mountify) ⭐ 1,357 | 🐛 24 | 🌐 Shell | 📅 2026-08-25** - OverlayFS with tmpfs/ext4 sparse support for reduced detection, works on APatch/Magisk too. `FOSS` `[M]` `[K]` `[A]`
* **[Magic Mount Metamodule](https://github.com/Tools-cx-app/meta-magic_mount-rs) ⚠️ Archived** - An implementation of a metamodule using Magic Mount, based on MKSU. `FOSS` `[M]` `[K]` `[A]`
* **[⭐ Meta-overlayfs](https://github.com/KernelSU-Modules-Repo/meta-overlayfs) ⭐ 467 | 🐛 8 | 🌐 Rust | 📅 2025-12-02** - Official reference implementation using OverlayFS for most users and standard setup. `FOSS` `[K]`
* **[ZeroMount](https://github.com/Enginex0/zeromount) ⭐ 124 | 🐛 3 | 🌐 Rust | 📅 2026-04-15** - Mountless module loading with Kernel-level VFS path redirection & SUSFS integration, WebUI, bootloop guard, and strategy fallback. `FOSS` `[M]` `[K]` `[A]`
* **[meta-mm](https://github.com/KernelSU-Modules-Repo/meta-mm) ⭐ 109 | 🐛 0 | 📅 2026-01-11** - The official KernelSU Modules Repo's Magic Mount metamodule. Lighter alternative to meta-magic\_mount for users who just want Magisk-compatible mounting without extra tooling. `FOSS` `[K]`

### LSPosed & Xposed

> \[!NOTE]
>
> LSPosed allows you to use Xposed modules, that can modify or extend the functionality of your Android system and apps.

* **[⭐ Vector](https://github.com/JingMatrix/Vector) ⭐ 12,312 | 🐛 20 | 🌐 Kotlin | 📅 2026-09-04** - Open Source *Fork* of original LSPosed with dynamic module loading, and other improvements. `FOSS` `[M]`
* **[LSPosed](https://lsposed.zip)** - A Riru / Zygisk module that provides an ART hooking framework delivering consistent APIs with the OG Xposed, leveraging the LSPlant hooking framework. `Proprietary`

> \[!TIP]
> See our [LSPosed installation guide](./docs/rooting-guides/lsposed-guide.md) for setup instructions.

### Zygisk

<details>

<summary><strong>What is Zygisk?</strong></summary>

A feature that lets modules inject code into Android's Zygote process for system-level modifications like root hiding and app patching.

<br>
</details>

* **[⭐ Zygisk Next](https://github.com/Dr-TSNG/ZygiskNext) ⭐ 10,535 | 🐛 9 | 🌐 C | 📅 2026-08-27** The "Gold Standard" for detection evasion. It is a standalone Zygisk implementation that offers the most advanced stealth features, including a dedicated **Zygote Monitor** and dashboard. `Proprietary` `[M]` `[K]` `[A]`
* **[ReZygisk](https://github.com/PerformanC/ReZygisk) ⭐ 3,884 | 🐛 10 | 🌐 C | 📅 2026-08-31** A high-performance implementation **entirely rewritten in C**. It introduces **custom linkers** to bypass modern linker-based detections, offering a WebUI for status monitoring and compatibility with Android 15 and 16. `FOSS` `[M]` `[K]` `[A]`
* **[NeoZygisk](https://github.com/JingMatrix/NeoZygisk) ⭐ 2,250 | 🐛 7 | 🌐 C++ | 📅 2026-09-03** A minimalist, high-stealth implementation using **ptrace injection**. It focuses on "trace cleaning," aiming to remove all injection artifacts from memory once modules are loaded. `FOSS` `[M]` `[K]` `[A]`

<details><summary><strong>Comparison table</strong></summary><br>

|                     | **Magisk Built-in**                                    | **Zygisk Next**                             | **NeoZygisk**                                 | **ReZygisk**                                         |
| :------------------ | :----------------------------------------------------- | :------------------------------------------ | :-------------------------------------------- | :--------------------------------------------------- |
| **Key Advantage**   | Official & simple                                      | Detection evasion                           | Stealth / cleaning                            | Speed / open source                                  |
| **License**         | GPL-3.0                                                | Proprietary                                 | GPL-3.0                                       | GPL-3.0 / AGPL-3.0                                   |
| **Root Support**    | Magisk only                                            | Magisk, KSU, APatch                         | Magisk, KSU, KSU Next, APatch                 | Magisk, KSU, APatch                                  |
| **Hiding Approach** | Basic DenyList                                         | ZN Linker + anon memory + Shamiko           | Ptrace injection + unmounting                 | Custom linker + maps hiding                          |
| **Strengths**       | ✅ Stable, well-documented<br>✅ Widest arch (incl. x86) | ✅ Most feature-rich<br>✅ Largest community  | ✅ Hard to trace in memory<br>✅ Minimal & open | ✅ **Fastest (native C)**<br>✅ Fully open & auditable |
| **Trade-offs**      | ❌ Magisk-only<br>❌ Easily detected                     | ❌ Closed source<br>❌ ZN Linker experimental | ❌ 64-bit only<br>❌ Smaller community          | ❌ RC phase<br>❌ Some compat issues                   |

<br>
</details><br>

> \[!TIP]
> Use these for Zygisk features on KernelSU/APatch, or for more control than Magisk's built-in provides.

### Root Hiding & Play Integrity

<details><summary><strong>What is Play Integrity?</strong></summary>

A Google API that lets apps verify a device is "genuine" - unmodified, Play-certified, and bootloader-locked. Apps use it to block rooted/modified devices. Verdicts: `MEETS_BASIC_INTEGRITY` < `MEETS_DEVICE_INTEGRITY` < `MEETS_STRONG_INTEGRITY`.

</details>

<details><summary><strong>Why hide root?</strong></summary>

Banking, payment, and some streaming/game apps detect root and refuse to run. Hiding root lets them work on a rooted device.

</details>

<details><summary><strong>What's realistic in 2026?</strong></summary>

Since Google's mid-2025 changes, `DEVICE_INTEGRITY` requires a **locked bootloader on Android 13+**, and `STRONG_INTEGRITY` needs an **unrevoked hardware keybox** (increasingly scarce). For most rooted users, passing `BASIC` + `DEVICE` integrity (via PIF + TrickyStore) is the practical ceiling - chasing `STRONG` is a deep, often futile rabbit hole.

</details>

### Susfs

<details><summary><strong>What is SUSFS?</strong></summary>
SUSFS (Systemless User Space File System) is a kernel-level module that allows root-hiding and system modifications without altering the system partition. It provides a stealthy environment for modules to operate, making it harder for apps to detect root or modifications.

</details><br>

* **[⭐ SUSFS for KernelSU](https://github.com/sidex15/susfs4ksu-module) ⭐ 2,550 | 🐛 3 | 🌐 HTML | 📅 2026-08-31** - Add-on root-hiding service for SUSFS-patched kernels (KernelSU/Next). The core of modern KSU hiding setups. `FOSS` `[M]` `[K]`
* **[RENE](https://github.com/rrr333nnn333/BRENE) ⭐ 342 | 🐛 6 | 🌐 Shell | 📅 2026-09-04** - SUSFS/KernelSU module for patched kernels with enhanced root hiding & spoofing. `FOSS` `[M]` `[K]`
* **[ReSuSFS](https://github.com/ahmed-alnassif/ReSuSFS) ⭐ 14 | 🐛 1 | 🌐 JavaScript | 📅 2026-09-04** - SUSFS/KernelSU module for patched kernels with modern ui and configuration options. `FOSS` `[M]` `[K]`

<details><summary><strong>Click for detailed comparison</strong></summary>

|                             | **BRENE**                                                 | **ReSuSFS**                       |
| --------------------------- | --------------------------------------------------------- | --------------------------------- |
| Root hiding                 | **Excellent**                                             | Excellent                         |
| SuSFS utilization           | **Excellent**                                             | **Excellent**                     |
| Mount/path hiding           | **Excellent**                                             | Excellent                         |
| Property/boot spoofing      | **Excellent**                                             | Very good                         |
| Memory-map hiding           | Very good                                                 | **Excellent**                     |
| Configuration/extensibility | Good                                                      | **Excellent**                     |
| Code architecture           | Complex/opinionated                                       | **Cleaner/modular**               |
| Competing-module behavior   | **Aggressive; automatically removes ReSuSFS/PIF variant** | No equivalent behavior identified |
| Security/trust assessment   | **⚠️ Requires caution/audit**                             | **Better**                        |
| **Overall recommendation**  | Powerful but questionable design choice                   | **🏆 Preferred**                  |

<br>
</details><br>

* **[⭐ Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases) ⭐ 6,324 | 🐛 0 | 🌐 HTML | 📅 2026-07-29** - Hides Magisk root from detection. `Proprietary` `[M]`
* **[TrickyStore](https://github.com/5ec1cff/TrickyStore) ⭐ 6,323 | 🐛 4 | 📅 2025-11-30** - Modifies the certificate chain for Android key attestation (keybox-based). The original/reference module. `Proprietary` `[M]` `[K]`
* **[Hide My Applist](https://github.com/Dr-TSNG/Hide-My-Applist) ⭐ 5,575 | 🐛 12 | 🌐 Kotlin | 📅 2026-08-01** - Intercepts app-list detection. `Proprietary` `[LSP]`
* **[Play Integrity Fork (PIF)](https://github.com/osm0sis/PlayIntegrityFork) ⭐ 4,451 | 🐛 0 | 🌐 C++ | 📅 2026-08-29** - The most actively maintained PIF. Fixes `DEVICE_INTEGRITY` verdicts with custom fields/props. Recommended starting point after chiteroman's original was discontinued. `FOSS` `[M]`
* **[Play Integrity Fix (inject)](https://github.com/KOWX712/PlayIntegrityFix) ⭐ 3,826 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-01** - Actively maintained fork using injected GMS/Play Store spoofing with a WebUI. `FOSS` `[M]`
* **[Tricky Addon – Update Target List](https://github.com/KOWX712/Tricky-Addon-Update-Target-List) ⭐ 3,421 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-30** - KSU WebUI to configure TrickyStore's `target.txt`. `FOSS` `[K]`
* **[⭐ HMA-OSS](https://github.com/frknkrc44/HMA-OSS) ⭐ 3,048 | 🐛 7 | 🌐 Kotlin | 📅 2026-09-04** - FOSS rewrite of Hide My Applist; hides your app list, settings, and package installers. `FOSS` `[LSP]`
* **[Zygisk Assistant](https://github.com/snake-4/Zygisk-Assistant) ⭐ 2,590 | 🐛 17 | 🌐 C++ | 📅 2026-05-04** - Zygisk module to hide root on KernelSU, Magisk, and APatch. `FOSS` `[M]`
* **[⭐ TEESimulator](https://github.com/JingMatrix/TEESimulator) ⭐ 2,362 | 🐛 14 | 🌐 C++ | 📅 2026-09-03** - Create a complete, software-based simulation of a hardware-backed Trusted Execution Environment (TEE) for Key Attestation. `FOSS` `[M]` `[K]`
* **[YuriKey](https://github.com/dpejoh/yurikey) ⭐ 1,883 | 🐛 9 | 🌐 Shell | 📅 2026-08-01** - Systemless module to obtain strong integrity easily. `FOSS` `[M]` `[K]`
* **[TEESimulator-RS](https://github.com/Enginex0/TEESimulator-RS) ⭐ 1,718 | 🐛 24 | 🌐 Kotlin | 📅 2026-07-11** - Fork of TEESimulator with native Rust certificate generation, key persistence, and AOSP-compliant attestation behavior. `FOSS` `[M]` `[K]`
* **[TrickyStore OSS](https://github.com/beakthoven/TrickyStoreOSS) ⭐ 1,355 | 🐛 7 | 🌐 Kotlin | 📅 2026-09-02** - Open-source alternative to TrickyStore. `FOSS` `[M]` `[K]`
* **[NoHello](https://github.com/MhmRdd/NoHello) ⭐ 1,351 | 🐛 21 | 🌐 C++ | 📅 2025-06-28** - Lightweight Zygisk module to hide root. `FOSS` `[M]`
* **[PlaycurlNEXT](https://github.com/daboynb/playcurlNEXT) ⭐ 771 | 🐛 0 | 🌐 Shell | 📅 2026-01-23** - Fixes Play Integrity (and SafetyNet) verdicts with custom fields and props. `FOSS` `[M]` `[K]`
* **[Specter](https://github.com/dpejoh/specter) ⭐ 583 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-04** - Unified Play Integrity and root hiding stack for Android. Successor of Yurikey. `FOSS` `[M]` `[K]`
* **[Always Strong](https://github.com/evoker0/AlwaysStrong) ⭐ 458 | 🐛 1 | 🌐 Shell | 📅 2026-08-25** - Bundles TEESimulator-RS and PlayIntegrityFork into a single module for strong integrity on rooted devices. `FOSS` `[M]` `[K]`
* **[Sensitive Props](https://github.com/Pixel-Props/sensitive-props) ⭐ 398 | 🐛 1 | 🌐 Shell | 📅 2026-03-22** - Modifies system properties and applies device-specific fixes to bypass SafetyNet/Play Integrity. `FOSS` `[M]`
* **[OhMyKeymint](https://github.com/qwq233/OhMyKeymint) ⭐ 323 | 🐛 3 | 🌐 Rust | 📅 2026-08-27** - Custom keystore implementation for Android Keystore Spoofer. `FOSS` `[M]` `[K]`
* **[ReZygisk's Treat Wheel](https://github.com/PerformanC/Treat-Wheel-Zygisk) ⭐ 260 | 🐛 7 | 🌐 C | 📅 2026-07-22** - Hides Magisk/root traces exclusively for ReZygisk, acting as the best userspace root hiding tool. `FOSS` `[M]` `[K]`
* **[DirtySepolicy Bypass](https://github.com/flipphoneguy/DirtySepolicy_Bypass) ⭐ 76 | 🐛 8 | 🌐 C++ | 📅 2026-06-19** - Bypasses new DirtySepolicy on rooted Android devices to keep apps working. `FOSS` `[M]` `[K]` `[A]`
* **[Komodo Build Props](https://github.com/Elcapitanoe/Komodo-Build-Prop#komodo-build-props) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2026-09-01** - Spoofs your device as a Pixel 9 Pro XL (komodo). `FOSS` `[M]`

> \[!TIP]
> Combine these with a proper [Zygisk implementation](#zygisk) for best results.

### Bootloop Protection

* **[Anti bootloop](https://github.com/Magisk-Modules-Alt-Repo/abootloop) ⭐ 445 | 🐛 8 | 🌐 Shell | 📅 2025-03-11** - Protect from bootloops. `FOSS` `[M]`
* **[AshReXcue - Bootloop Protector](https://github.com/RipperHybrid/AshLooper) ⭐ 189 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-13** - Prevent boot loops caused by problematic modules installed via KernelSU or Magisk. `FOSS` `[M]` `[K]`
* **[YetAnotherBootloopProtector](https://github.com/Magisk-Modules-Alt-Repo/YetAnotherBootloopProtector) ⭐ 178 | 🐛 5 | 🌐 Shell | 📅 2026-08-27** - Monitor and fix potential Bootloops and SystemUI failures. `FOSS` `[M]`

### Root Detection & Testing

* **[⭐ Android-Native-Root-Detector](https://github.com/reveny/Android-Native-Root-Detector) ⭐ 1,380 | 🐛 15 | 🌐 Kotlin | 📅 2026-04-11** - A tool for detecting root on android. `FOSS`
* **[MagiskDetection](https://github.com/apkunpacker/MagiskDetection) ⭐ 1,053 | 🐛 5 | 📅 2026-05-10** - Collection of Some publicly Available POC Apps to Detect Root/Magisk presence. `Proprietary`
* **[Duck Detector](https://github.com/eltavine/Duck-Detector-Refactoring) ⭐ 957 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-28** - Android environment integrity inspection tool for root, hook, bootloader, SELinux, virtualization, and attestation signals. `FOSS`
* **[Play Integrity API Checker](https://github.com/1nikolas/play-integrity-checker-app) ⭐ 813 | 🐛 8 | 🌐 Java | 📅 2025-08-19** - This app shows info about your device integrity as reported by Google Play Services. If any of this fails could mean your device is rooted or tampered in a way. `FOSS` | [▶️](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck)
* **[Chunqiu Detector](https://github.com/mingzun09/Chunqiu-Detector-Problem-solution) ⭐ 379 | 🐛 2 | 🌐 HTML | 📅 2026-09-02** - Solutions, scripts, and modules for bypassing and troubleshooting Chunqiu Detector checks on rooted Android devices. `FOSS`
* **[Securify](https://github.com/RabehX/Securify) ⭐ 163 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-31** - Yet Another Root Checker and Play Integrity API Application. `FOSS`
* **[PIF Detector](https://github.com/IR0NBYTE/playIntegrityFixDetector) ⭐ 65 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-28** - Native app designed to detect modifications, bypasses, or "fixes" applied to the Google Play Integrity API. `FOSS` `[M]` `[K]`
* **[⭐ Duck Detector Fork](https://github.com/rrr333nnn333/Duck-Detector-Refactoring) ⭐ 48 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-28** - Duck Detector fork with additional features and improvements. `FOSS`
* **[Android-Device-Trust](https://github.com/reveny/Android-Device-Trust) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2026-08-20** - Android device attestation and fingerprinting tool. `FOSS`
* **[Play Integrity Alert](https://github.com/Xiddoc/PlayIntegrityAlert) ⭐ 29 | 🐛 2 | 🌐 Kotlin | 📅 2026-07-02** - Get notified when an app calls the Play Integrity API. `FOSS` `[LSP]`
* **[ZygoteNextProbe](https://github.com/XiaoTong6666/ZygoteNextProbe) ⭐ 18 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-15** - Research probe that checks whether Android 17's `zygote_next` native isolated services leak a global mount view - potentially exposing Magisk/Zygisk/LSPosed mounts to apps. `FOSS`

[↑ Back to top](#table-of-contents)

***

## System Management

### System Tweaks

* **[TWRP A/B Retention Script](https://github.com/Magisk-Modules-Repo/twrp-keep) ⭐ 275 | 🐛 0 | 🌐 Shell | 📅 2026-08-08** - Keep TWRP installed after an A/B OTA. `FOSS` `[M]`
* **[Noogle Magisk](https://github.com/SelfRef/noogle-magisk) ⭐ 131 | 🐛 17 | 🌐 Shell | 📅 2025-04-23** - Magisk modules for removing/replacing Google applications on stock Android 11-15. `FOSS` `[M]`
* **[HyperOS Security Center](https://github.com/Mods-Center/HyperOS-Security-Center) ⭐ 127 | 🐛 5 | 📅 2026-08-14** - Advanced app info tools, system app Wi-Fi management, removal of root/account restrictions etc. `Proprietary` `[M]` `[K]`
* **[Secure Element Access](https://github.com/jqssun/android-se-access) ⭐ 34 | 🐛 0 | 🌐 Kotlin | 📅 2026-04-25** - Enable access to secure element for trusted apps. `FOSS`
* **[Disable Low Ram Flag](https://github.com/Magisk-Modules-Alt-Repo/disable-low-ram) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2026-05-11** - Disable Low‑RAM flag on Android Go devices. `FOSS` `[M]`
* **[HyperOS Accessibility Fix](https://github.com/chickendrop89/hyperos-accessibility-fix) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2026-07-20** - Stop HyperOS from randomly disabling accessibility services. `FOSS` `[M]` `[K]`
* **[Cromite SystemWebView](https://github.com/hddq/magisk-cromite-webview) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2026-06-12** - Replaces the Android System WebView with Cromite WebView. `FOSS` `[M]`
* **[Multi Userui Enabler](https://github.com/InsertX2k/multiuseruienabler) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2025-12-19** - Magisk module that tries to enable Multi-User UI. `FOSS` `[M]`

#### VBMeta Mods

<details><summary><strong>What is VBMeta</strong></summary>

* VBMeta is a critical component of Android Verified Boot (AVB), a security feature designed to **ensure the integrity of the software running on an Android device during the boot process**.

<br>
</details>

* **[Android VBMeta Fixer](https://github.com/reveny/Android-VBMeta-Fixer) ⭐ 526 | 🐛 9 | 🌐 Java | 📅 2025-10-16** - A Magisk/KernelSU/Apatch module to fix VBMeta detections on Android. `FOSS` `[M]` `[K]`
* **[VBMeta Disguiser](https://github.com/Astoritin/VBMetaDisguiser) ⭐ 83 | 🐛 0 | 🌐 Shell | 📅 2025-11-22** - Disguises the properties of vbmeta. `FOSS` `[M]` `[K]`

### System UI & Framework

|                                                                         |                                 |                                     |                         |                                     |               |                                           |             |
| :---------------------------------------------------------------------- | :------------------------------ | :---------------------------------- | :---------------------- | :---------------------------------- | :------------ | :---------------------------------------- | :---------- |
| [AOSP (Android Open Source Project)](#aosp-android-open-source-project) | [ColorOS (Oppo)](#coloros-oppo) | [HyperOS (Xiaomi)](#hyperos-xiaomi) | [NothingOS](#nothingos) | [One UI (Samsung)](#one-ui-samsung) | [Onyx](#onyx) | [Oxygen OS (OnePlus)](#oxygen-os-oneplus) | [ZUI](#zui) |
|                                                                         |                                 |                                     |                         |                                     |               |                                           |             |

#### AOSP (Android Open Source Project)

* **[⭐ PixelXpert](https://github.com/siavash79/PixelXpert) ⚠️ Archived** - A mixed Xposed+Magisk module, which is made to allow customizations that are not originally designed in AOSP. `FOSS` `[M]` `[LSP]`
* **[SystemUI Tuner](https://github.com/zacharee/Tweaker?tab=readme-ov-file) ⭐ 1,723 | 🐛 67 | 🌐 Kotlin | 📅 2026-08-27** - View and modify hidden settings on Android devices. `FOSS` `[M]`
* **[PIXELIFY NEXT](https://github.com/BasGame1/Pixelify-Next) ⭐ 309 | 🐛 3 | 🌐 Shell | 📅 2026-08-26** - A Magisk Module which enables Pixel UI and some exclusive features. `FOSS` `[M]`
* **[PixelUpdater](https://github.com/PixelUpdater/PixelUpdater) ⭐ 234 | 🐛 5 | 🌐 Kotlin | 📅 2026-05-11** - Pixel Updater is an app for installing Android A/B OTA updates from Google's OTA server. `FOSS` `[M]`

#### ColorOS (Oppo)

* **[LuckyTool](https://github.com/Xposed-Modules-Repo/com.luckyzyx.luckytool/blob/main/README_EN.md) ⭐ 1,894 | 🐛 8 | 📅 2026-04-26** - Extended functionality and optimization module for ColorOS. `Proprietary` `[LSP]`
* **[OShin](https://github.com/suqi8/OShin/blob/master/README_EN.md) ⭐ 1,190 | 🐛 112 | 🌐 Kotlin | 📅 2026-07-28** - Auxiliary module deeply integrated with ColorOS, designed to enhance and optimize your operating system experience. `FOSS` `[LSP]`
* **[OPCameraPro](https://github.com/Xposed-Modules-Repo/com.tlsu.opluscamerapro) ⭐ 139 | 🐛 0 | 📅 2026-05-31** - ColorOS and realmeUI module providing various AI functions, enhancing cameras and other photo related tweaks. `Proprietary` `[LSP]`
* **[ColorOS Feature Enhance](https://github.com/ItosEO/ColorFeatureEnhance) ⭐ 68 | 🐛 0 | 🌐 Kotlin | 📅 2025-08-18** - Visually edit and managing ColorOS feature switches. `FOSS` `[LSP]`
* **[Oplus Launcher Radius Optimization](https://github.com/Qjj7679/Oplus-Luncher-RadiusOptimization) ⭐ 10 | 🐛 0 | 🌐 Kotlin | 📅 2026-04-23** - Optimize the rounded corners of the recent tasks card on the ColorOS system desktop. `FOSS` `[LSP]`

#### HyperOS (Xiaomi)

* **[⭐ HyperCeiler](https://github.com/ReChronoRain/HyperCeiler/blob/main/README_en-US.md) ⭐ 5,334 | 🐛 236 | 🌐 Java | 📅 2026-09-01** - Extensive customizations for HyperOS. `FOSS` `[LSP]`
* **[Pengeek](https://github.com/monwf/customiuizer) ⭐ 1,470 | 🐛 47 | 🌐 Java | 📅 2026-05-19** - Customize your HyperOS to your liking. For HyperOS based on Android 14. `FOSS` `[LSP]`
* **[Hyper Helper](https://github.com/HowieHChen/XiaomiHelper/blob/master/README_EN-US.md) ⭐ 353 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-30** - Lightweight customization module for HyperOS only. `FOSS` `[LSP]`
* **[Hyper Unlocked](https://github.com/ukriu/HyperUnlocked) ⭐ 225 | 🐛 16 | 🌐 Shell | 📅 2026-08-29** - Unlock all high-end features possible to be unlocked on low-end xiaomi devices. `FOSS` `[M]`
* **[HyperStar](https://github.com/YunZiA/HyperStar/blob/master/README_EN-US.md) ⭐ 130 | 🐛 6 | 🌐 Kotlin | 📅 2026-05-13** - An LSPosed module mainly designed to customize the Xiaomi HyperOS Control Center, along with some features. `FOSS` `[LSP]`
* **[Better Miui Express](https://github.com/Robotxm/BetterMiuiExpress) ⭐ 128 | 🐛 2 | 🌐 Kotlin | 📅 2025-10-23** - Prevents MIUI/HyperOS's express widget from jumping to third-party applications such as Taobao and Cainiao, and uses a customized interface to display express details. `FOSS` `[LSP]`
* **[ClipboardList](https://github.com/HChenX/ClipboardList/blob/master/README-en.md) ⭐ 85 | 🐛 3 | 🌐 Java | 📅 2025-08-09** - Remove the 20-item limit and time limit for the Clipboard and Phrases feature. Only for MIUI and HyperOS. `FOSS` `[LSP]`
* **[ColorOS\_Control\_Center](https://github.com/Mods-Center/ColorOS_Control_Center) ⭐ 46 | 🐛 2 | 📅 2026-03-31** - Replace HyperOS control panel with ColorOS-style quick settings, featuring customizable and squared tiles. `Proprietary`
* **[Fingerprint Catalog](https://github.com/custombeta/fingerprint-cataloge) ⭐ 22 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-03** - Allows you to create, upload, import, and apply your own fingerprint icons and animations on HyperOS. `Proprietary` `[LSP]`
* **[Janus](https://modules.lsposed.org/module/org.pysh.janus/)** - Enhances Xiaomi rear screens with multitasking, app shortcuts, gestures, notification mirroring, and power-saving features. `Proprietary` `[LSP]`

> \[!TIP]
> Check this resource for more [HyperOS Mods ↗](https://github.com/ImKKingshuk/Awesome-HyperOS) ⭐ 157 | 🐛 0 | 📅 2026-01-12

#### NothingOS

* **[NothingTweaks](https://github.com/RevealedSoulEven/NothingTweaks) ⭐ 12 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-28** - A customization module for Nothing OS based on Xposed framework. `FOSS` `[LSP]`

#### One UI (Samsung)

* **[⭐ KnoxPatch](https://github.com/salvogiangri/KnoxPatch) ⭐ 1,501 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-25** - Get Samsung apps/features working again in your rooted Galaxy device. For better experience, please also [read this ↗](https://github.com/salvogiangri/KnoxPatch?tab=readme-ov-file#knoxpatch-enhancer) ⭐ 1,501 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-25 . `FOSS` `[LSP]`
* **[One UI X](https://github.com/SoClear/OneUIX) ⭐ 190 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-21** - Remove annoying restrictions, and inject powerful enhancements into the Status Bar, Quick Settings, and native apps etc on Samsung's One UI. `FOSS` `[LSP]`
* **[Samsung Dex Standalone Mode](https://github.com/supermarsx/magisk-samsung-dex-standalone-mode) ⭐ 69 | 🐛 0 | 🌐 Shell | 📅 2026-06-30** - Systemlessly enable Samsung DeX standalone mode. `FOSS` `[M]`
* **[One Design](https://github.com/Xposed-Modules-Repo/qyz.onedesign) ⭐ 34 | 🐛 0 | 📅 2026-08-29** - Customize multiple applications at the system level, providing feature enhancements, and system optimizations. `Proprietary` `[LSP]`
* **[OneLab](https://github.com/pigerzhu/OneLab) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2026-09-01** - One UI feature extensions and foldable app adaptations for Samsung devices. `FOSS` `[LSP]`

#### Onyx

* **[OnyxTweaks](https://github.com/timschneeb/OnyxTweaks) ⭐ 63 | 🐛 1 | 🌐 Kotlin | 📅 2026-05-25** - Xposed module for Onyx Boox e-Ink devices with Android 12.It adds other mods to the SystemUI, Android Framework, and Onyx Launcher. `FOSS` `[LSP]`

#### Oxygen OS (OnePlus)

* **[Oxygen-Customizer](https://github.com/DHD2280/Oxygen-Customizer/) ⭐ 455 | 🐛 34 | 🌐 Java | 📅 2026-08-30** - Open-source Oxygen OS customizer application. `FOSS` `[LSP]`

#### ZUI

* **[ZTool](https://github.com/qwqawa64/ZUX-ZTool) ⭐ 64 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-04** - Provides optimization and customization features for the ZUXOS system. `FOSS` `[LSP]`
* **[Unf\*\*k ZUI Tablet](https://github.com/Xposed-Modules-Repo/xyz.cirno.unfuckzui/) ⭐ 20 | 🐛 0 | 📅 2026-02-08** - Adjust notification icon size, restore AOSP-style installers/permissions, enforce screen rotation persistence, and allow package querying etc. `Proprietary` `[LSP]`
* **[BetterZUIKey](https://github.com/CommandPrompt-Wang/BetterZUIKey) ⭐ 4 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-31** - An LSPosed module for overriding keyboard shortcuts on Lenovo ZUXOS devices. `FOSS` `[LSP]`

### Boot & Startup

* **[Live Boot Module](https://github.com/symbuzzer/livebootmodule) ⭐ 440 | 🐛 8 | 🌐 Shell | 📅 2026-09-03** - Enables unix-style (verbose) boot animation for Android devices. `FOSS` `[M]` `[K]`
* **[video-to-bootanimation](https://github.com/Magisk-Modules-Alt-Repo/video-to-bootanimation) ⭐ 126 | 🐛 12 | 🌐 Shell | 📅 2026-08-27** - A Magisk Module Which Can Set Videos as Android Device BootAnimation. `FOSS` `[M]`
* **[Samsung Boot Animation Module](https://github.com/John0n1/SMbootFX) ⭐ 85 | 🐛 0 | 🌐 Shell | 📅 2026-09-03** - Custom boot animations for Samsung devices via Magisk. `FOSS` `[M]`
* **[Live Boot](https://play.google.com/store/apps/details?id=eu.chainfire.liveboot)** - Get a Linux-like live boot screen on Android. `Proprietary`

### Debloating

> \[!TIP]
> **Related Guide**: [Complete Debloating Tutorial](../general-guides/android-apps-debloating.md)

* **[⭐ Canta](https://github.com/samolego/Canta) ⭐ 5,770 | 🐛 30 | 🌐 Kotlin | 📅 2026-09-04** - Uninstall any app without root using [Shizuku](#developer-tools). `FOSS` | [🌱](https://f-droid.org/en/packages/io.github.samolego.canta/) | [▶️](https://play.google.com/store/apps/details?id=io.github.samolego.canta)
* **[De-Bloater](https://github.com/sunilpaulmathew/De-Bloater) ⭐ 782 | 🐛 49 | 🌐 Java | 📅 2026-05-25** - An application using the power of Magisk to debloat unwanted system apps!. `FOSS` | [🌱](https://f-droid.org/packages/com.sunilpaulmathew.debloater) | [▶️](https://play.google.com/store/apps/details?id=com.sunilpaulmathew.debloater)
* **[System App Nuker](https://github.com/ChiseWaguri/systemapp_nuker) ⭐ 252 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-30** - A module to debloat system apps with WebUI Interface. `FOSS` `[M]`
* **[Scalpel](https://github.com/Enginex0/Scalpel) ⭐ 46 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-23** - Precision Debloat & Systemize for Rooted Android. `FOSS` `[M]` `[K]`
* **[EXA System App Remover](https://play.google.com/store/apps/details?id=exa.free.saux)** - Remove Bloatware, clear memory and speed up your phone now by uninstalling unused system apps. `Proprietary`
* **[System app remover](https://play.google.com/store/apps/details?id=com.jumobile.manager.systemapp)** - A system app remover and user app uninstaller, move app to sdcard, move app to phone, apk on sdcard scan/install/delete. `Proprietary`

### App & Package Management

* **[⭐ App Manager](https://github.com/MuntashirAkon/AppManager) ⭐ 8,889 | 🐛 202 | 🌐 Java | 📅 2026-09-04** - A full-featured package manager and viewer for Android. `FOSS` | [🌱](https://f-droid.org/packages/io.github.muntashirakon.AppManager/)
* **[⭐ Droid-ify](https://github.com/Droid-ify/client) ⭐ 7,362 | 🐛 191 | 🌐 Kotlin | 📅 2026-09-04** - F-Droid client with Material UI and auto updating apps using root. `FOSS` | [🌱](https://f-droid.org/packages/com.looker.droidify)
* **[⭐ Hail](https://github.com/aistra0528/Hail) ⭐ 6,600 | 🐛 168 | 🌐 Kotlin | 📅 2026-08-29** - Disable / Hide / Suspend / Uninstall Android apps. `FOSS` | [🌱](https://f-droid.org/packages/com.aistra.hail/)
* **[InstallerX-Revived](https://github.com/wxxsfxyzm/InstallerX-Revived) ⭐ 6,478 | 🐛 21 | 🌐 Kotlin | 📅 2026-09-04** - A modern and functional Android app installer. `FOSS` `[LSP]`
* **[Neo Store](https://github.com/NeoApplications/Neo-Store) ⭐ 4,972 | 🐛 121 | 🌐 Kotlin | 📅 2026-08-31** - An F-Droid client with modern UI and an arsenal of extra features. `FOSS` | [🌱](https://f-droid.org/packages/com.machiav3lli.fdroid)
* **[Aurora Store](https://github.com/whyorean/AuroraStore) ⭐ 2,940 | 🐛 26 | 🌐 Kotlin | 📅 2026-08-24** - A Google Play Store client to search, view app details, and download APKs directly to your device. `FOSS` | [🌱](https://f-droid.org/packages/com.aurora.store/)
* **[⭐ Zygisk Detach](https://github.com/j-hc/zygisk-detach) ⭐ 2,124 | 🐛 0 | 🌐 Rust | 📅 2026-07-09** - Zygisk module to detach installed apps from Play Store, hooking binder. `FOSS` `[M]` `[K]`
* **[Inure](https://github.com/Hamza417/Inure) ⭐ 1,901 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-04** - An elegant and beautiful premium Android app manager for rooted and non-rooted devices. `FOSS` | [🌱](https://f-droid.org/en/packages/app.simple.inure/) | [▶️](https://play.google.com/store/apps/details?id=app.simple.inure.play)
* **[Universal Installer](https://github.com/pass-with-high-score/universal-installer) ⭐ 1,368 | 🐛 21 | 🌐 Kotlin | 📅 2026-09-04** - Install and manage APK packages with split APK support. `FOSS` `[LSP]`
* **[InxLocker](https://github.com/Chimioo/InxLocker) ⭐ 898 | 🐛 2 | 🌐 Kotlin | 📅 2026-06-11** - Intercepts/forwards Android system application installation and uninstallation requests, redirecting them to your specified installer app. `FOSS` `[LSP]`
* **[Package Manager](https://github.com/SmartPack/PackageManager) ⭐ 818 | 🐛 71 | 🌐 Java | 📅 2026-08-25** - A highly powerful app to manage both system and user apps installed on an Android device. `FOSS` | [🌱](https://f-droid.org/packages/com.smartpack.packagemanager) | [▶️](https://play.google.com/store/apps/details?id=com.smartpack.packagemanager)
* **[BetterKnownInstalled](https://github.com/Pixel-Props/BetterKnownInstalled) ⭐ 559 | 🐛 0 | 🌐 Shell | 📅 2026-09-03** - Patches packages to fix DroidGuard UNKNOWN\_INSTALLED issues. `FOSS` `[LSP]`
* **[Thor](https://github.com/trinadhthatakula/Thor) ⭐ 538 | 🐛 13 | 🌐 Kotlin | 📅 2026-09-04** - Android App Manager and App Installer utility. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/com.valhalla.thor) | [▶️](https://play.google.com/store/apps/details?id=com.valhalla.thor)
* **[Let Me Downgrade](https://github.com/DavidBerdik/Let-Me-Downgrade) ⭐ 296 | 🐛 3 | 🌐 Kotlin | 📅 2026-07-15** - Add support for downgrading apps on Android 12 through 15 QPR1. `FOSS` `[LSP]` | [🌱](https://f-droid.org/packages/com.berdik.letmedowngrade/) | [▶️](https://play.google.com/store/apps/details?id=com.berdik.letmedowngrade)
* **[Update Locker](https://github.com/Xposed-Modules-Repo/ru.mike.updatelocker/) ⭐ 248 | 🐛 6 | 📅 2026-03-10** - Block updates (and auto-updates) selected apps via popular markets including Google Play Market, Huawei AppGallery and Samsung Galaxy Store. `Proprietary`
* **[⭐ Disable Target API Block](https://github.com/buttercookie42/DisableTargetAPIBlock) ⭐ 234 | 🐛 2 | 🌐 Java | 📅 2025-10-18** - Disable Android 14's installation block for old apps. `FOSS` `[LSP]`
* **[Play Version Spoofer](https://github.com/byemaxx/PlayVersionSpoofer) ⭐ 167 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-18** - Prevents the Google Play Store from automatically updating itself. `FOSS` `[LSP]`
* **[AlterInstaller](https://github.com/chenxiaolong/AlterInstaller) ⭐ 134 | 🐛 1 | 🌐 Java | 📅 2026-08-20** - Spoof Android package manager installer fields to bypass installation restrictions. `FOSS` `[M]` `[K]`
* **[BanUninstall](https://github.com/TinyHai/BanUninstall/) ⭐ 62 | 🐛 2 | 🌐 Kotlin | 📅 2026-07-19** - Prevents apps from being uninstalled or apps' data from being cleared. `FOSS` `[LSP]`
* **[Play Store Self Update Blocker](https://github.com/himanshujjp/PlayStoreSelfUpdateBlocker) ⭐ 55 | 🐛 2 | 🌐 Shell | 📅 2025-09-17** - Prevents the Google Play Store from auto-updating itself. Useful for users trying to maintain valid device attestation under the newer Play Integrity API rules. `FOSS` `[M]` `[K]`
* **[Updates Manager Extended](https://github.com/Senliast/xposed-modules/tree/main/Updates_Manager_Extended) ⭐ 22 | 🐛 2 | 🌐 Java | 📅 2026-05-26** - Allows to block app updates (including automatic updates) for specific apps, no matter from which app store they were installed. `FOSS` `[LSP]`
* **[Auto Uninstaller](https://github.com/MeRaazi/auto-uninstaller) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-24** - Automatically uninstall blacklisted apps. `FOSS` `[K]`
* **[App Manager](https://play.google.com/store/apps/details?id=com.lb.app_manager)** - A feature rich app manager with batch operation support. `Proprietary`
* **[AppDash: App Manager & Backup](https://play.google.com/store/apps/details?id=flar2.appdashboard\&hl=en)** - Makes it easy to manage APKs and apps installed on your device. `Proprietary`
* **[F-Droid Privileged Extension](https://gitlab.com/fdroid/privileged-extension)** - Enables F-Droid to install and delete apps without needing "Unknown Sources" & install updates in the background. `FOSS` | [🌱](https://f-droid.org/en/packages/org.fdroid.fdroid.privileged/)
* **[Ice Box](https://play.google.com/store/apps/details?id=com.catchingnow.icebox)** - Freeze and hide apps rarely used. `Proprietary`

> \[!TIP]
>
> Check out our **[Zygisk Detach Guide ↗](./docs/general-guides/stop-android-app-auto-updates-play-store.md)**

### Permissions & AppOps

* **[Thanox](https://github.com/Tornaco/Thanox) ⭐ 3,251 | 🐛 469 | 🌐 Java | 📅 2026-08-14** - A system management tool that provide convenient functions like application startup management, background management, permission management etc. `FOSS` `[LSP]` | [▶️](https://play.google.com/store/apps/details?id=github.tornaco.android.thanos.pro\&hl=en\&gl=US)
* **[PermissionManagerX](https://github.com/mirfatif/PermissionManagerX) ⭐ 766 | 🐛 7 | 🌐 HTML | 📅 2026-09-03** - eXtended Permission Manager for Android to view and set Manifest Permissions and AppOps. `FOSS` | [🌱](https://f-droid.org/packages/com.mirfatif.permissionmanagerx) | [▶️](https://play.google.com/store/apps/details?id=com.mirfatif.permissionmanagerx)
* **[AppOps](https://play.google.com/store/apps/details?id=rikka.appops)** - Control the hidden appops conveniently. `Proprietary`
* **[Permission Ruler](https://play.google.com/store/apps/details?id=com.stefanosiano.permissionruler\&hl=en)** - Automatically manages app permissions when the screen is off for enhanced privacy. `Proprietary`

> \[!TIP]
> Check out [Firewall Tools](#firewalls-filtering) for network control of apps

### System Information & Diagnostics

* **[Infamick Script](https://github.com/Infamousmick/Infamick-script/) ⭐ 87 | 🐛 0 | 🌐 Shell | 📅 2026-04-15** - A powerful system utility script that provides easy access to various system information and settings. `FOSS` `[M]`
* **[Castro - system info](https://play.google.com/store/apps/details?id=com.itemstudio.castro)** - A huge collection of information about your device and a set of tools for monitoring its status. `Proprietary`
* **[Device Info HW](https://play.google.com/store/apps/details?id=ru.andr7e.deviceinfohw)** - A hardware and software information app for Android devices. `Proprietary`

[↑ Back to top](#table-of-contents)

***

## Performance & Battery

> \[!TIP]
> For gaming-specific tweaks, see [Gaming](#gaming). For CPU/GPU management, see [Kernel Management](#kernel-management). For memory optimization, check [Memory Management](#memory-ram).

### Performance Optimization

* **[FDE.AI](https://github.com/feravolt/FDE.AI-docs) ⭐ 671 | 🐛 0 | 🌐 HTML | 📅 2026-08-19** - All-in-One ultimate optimizer for all devices running Android OS. `Proprietary` `[LSP]`
* **[COPG](https://github.com/AlirezaParsi/COPG) ⭐ 381 | 🐛 3 | 🌐 JavaScript | 📅 2026-09-03** - Spoof your device to enjoy premium features, max performance, and exclusive benefits. `FOSS` `[M]`
* **[MAGNETAR](https://github.com/Kyliekyler/MAGNETAR) ⭐ 312 | 🐛 1 | 🌐 Shell | 📅 2025-08-30** - Device Performance Optimizer - Aims To Provide An Optimal Experience At Every Usage Scenario. `FOSS` `[M]`
* **[Hydrostellaire](https://github.com/AestasBritannia/Hydro-Br-leur) ⭐ 309 | 🐛 9 | 🌐 Shell | 📅 2026-04-18** - A magisk module for devices running on Dimensity flagship platforms and OnePlus, Realme devices. `FOSS` `[M]`
* **[Androoster](https://github.com/cioccarellia/androoster) ⭐ 161 | 🐛 5 | 🌐 Kotlin | 📅 2025-03-17** - Android root tweak toolbox. It is built to help you tweak your device, keeping it cool, fast and responsive. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/com.andreacioccarelli.androoster)
* **[AZenith](https://github.com/Liliya2727/AZenith) ⭐ 119 | 🐛 7 | 🌐 Kotlin | 📅 2026-09-03** - All-In-One (AIO) system optimization module designed to enhance Android performance. `FOSS` `[M]` `[K]`
* **[Stellar Tweaks](https://github.com/kanaodnd/Stellar-Tweaks) ⭐ 87 | 🐛 0 | 📅 2026-04-26** - Sophisticated scheduler designed to harmonize device performance and efficiency. `Proprietary` `[M]` `[K]` `[A]`
* **[COPG-VD](https://github.com/VD171/COPG-VD) ⭐ 82 | 🐛 0 | 🌐 C++ | 📅 2026-08-10** - Fork of COPG with additional features and optimizations. `FOSS` `[M]` `[K]`
* **[SpeedCool](https://github.com/Llucs/SpeedCool-Magisk-Module) ⚠️ Archived** - Boost, cool down, and optimize your Android with SpeedCool: less lag, more performance, and a cooler system. `FOSS` `[M]`
* **[Dynamic System Tweaks Magisk Module](https://github.com/PS2ClassicsVault/Dynamic-System-Tweaks-Magisk-Module) ⭐ 47 | 🐛 1 | 🌐 Shell | 📅 2026-05-10** - Improves overall System performance without overheating and losing battery power for armeabi-v7a devices. `FOSS` `[M]`
* **[TNF Tweaker](https://github.com/topnotchfreaks/tnf_tweaker) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-02** - Optimization tool designed exclusively for devices running the TopNotchFreaks and Zephyr kernels. `FOSS` `[K]`
* **[⭐ 3C All-in-One Toolbox](https://play.google.com/store/apps/details?id=ccc71.at.free)** - A comprehensive utility that offers a wide range of tools for monitoring, controlling, and optimizing device performance in a user-friendly interface. `Proprietary`

### Kernel Management

* **[KonaBess](https://github.com/libxzr/KonaBess) ⭐ 1,779 | 🐛 12 | 🌐 Java | 📅 2025-10-03** - A straightforward application designed to customize GPU frequency and voltage tables without the need for kernel recompilation. `FOSS`
* **[Kernel Flasher](https://github.com/fatalcoder524/KernelFlasher) ⭐ 503 | 🐛 7 | 🌐 Kotlin | 📅 2026-07-01** - An Android app to flash (AK3 files), backup, and restore kernels. `FOSS`
* **[Rv Kernel Manager](https://github.com/Rve27/RvKernel-Manager) ⭐ 258 | 🐛 11 | 🌐 Kotlin | 📅 2026-05-11** - A modern Kernel Manager with Material 3 Expressive Design. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/com.rve.rvkernelmanager)
* **[KonaBess Next](https://github.com/KonaBess-Next/KonaBess-Next) ⭐ 222 | 🐛 23 | 🌐 Kotlin | 📅 2026-08-06** - Fork of KonaBess, Custom GPU overclocking and undervolting tool with granulated voltage for rooted Snapdragon Android devices. `FOSS`
* **[Minimal Kernel Manager](https://github.com/abhay-byte/mkm) ⭐ 148 | 🐛 8 | 🌐 Kotlin | 📅 2026-09-04** - Android kernel management and system monitoring application. `FOSS` | [🌱](https://f-droid.org/packages/com.ivarna.fluxlinux/)
* **[iUnlocker GLTool](https://github.com/i-Taylo/iUnlockerGL) ⭐ 103 | 🐛 17 | 🌐 Shell | 📅 2025-12-29** - Designed to spoof GPU information, allowing users to modify GPU information for unlocking graphics in games and testing. `FOSS` `[M]`
* **[Zuan Kernel Manager](https://github.com/ZUANVFX01/ZKM/) ⭐ 97 | 🐛 2 | 🌐 Kotlin | 📅 2026-02-22** - Advanced Android kernel management tool, rebuilt from the Rve Kernel Manager project base with Material 3 Expressive Modern Style. `FOSS`
* **[PerfMTK](https://github.com/JUANIMAN/PerfMTK) ⭐ 89 | 🐛 21 | 🌐 Shell | 📅 2026-06-28** - Designed to optimize performance and power efficiency on MediaTek devices with Mali GPUs. `FOSS` `[M]`
* **[Kernel Enhancer](https://github.com/RAAJK20Pro/KernelEnhancer) ⭐ 36 | 🐛 1 | 📅 2026-06-18** - A Simple Kernel Parameters Optimization for all devices. `Proprietary` `[M]`
* **[EX Kernel Manager](https://play.google.com/store/apps/details?id=flar2.exkernelmanager)** - Root tool for backup and flashing kernels, tweaking color, sound, gestures and other kernel settings. `Proprietary`
* **[Franco Kernel Manager](https://play.google.com/store/apps/details?id=com.franco.kernel)** - A complete toolbox for all devices with a rich interface that combines everything you need to manage, tweak and empower your device. `Proprietary`

### Memory & RAM

* **[ZRAM Module](https://github.com/FurLC/ZRAM-Module) ⭐ 71 | 🐛 0 | 🌐 Shell | 📅 2026-05-11** - A Magisk/KernelSU module that provides ZRAM compression algorithm support for Android devices. `FOSS` `[M]` `[K]`
* **[Magisk Swapspace](https://github.com/chickendrop89/magisk-swapspace) ⭐ 47 | 🐛 0 | 🌐 Shell | 📅 2026-07-14** - This module allows for creating a persistent swap space on android. `FOSS` `[M]`
* **[SkyScene Add-on](https://github.com/WeirdMidas/SkySceneAddon) ⭐ 37 | 🐛 10 | 🌐 Shell | 📅 2026-08-18** - Optimizations for most memory management subsystems, as well as integrated intelligent memory expansion, a way to expand memory that mimics OEMs like Ram Plus. `FOSS` `[M]` `[K]`
* **[Swap Disabler](https://github.com/rompelhd/Swap-Disabler) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2026-08-29** - Disable swap at system startup. `FOSS` `[M]`
* **[SwapBoost Pro](https://github.com/yadavnikhil03/SwapBoost-Pro) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2026-06-16** - Optimizes your device's memory performance through persistent zRAM + Swapfile optimization with VM tweaks. `FOSS` `[M]`

### Battery Optimization

* **[Plus Plus Battery](https://github.com/dijia1124/plusplusbattery) ⭐ 468 | 🐛 16 | 🌐 Kotlin | 📅 2026-02-22** - Real-time battery stats & health estimator for OnePlus/Oppo/Realme phones. `FOSS` | [🌱](https://f-droid.org/en/packages/com.dijia1124.plusplusbattery/)
* **[EnforceDoze](https://github.com/farfromrefug/EnforceDoze) ⭐ 358 | 🐛 21 | 🌐 Java | 📅 2026-07-26** - Enable Doze mode immediately after screen off and turn off motion sensing to get best battery life. `FOSS` | [🌱](https://f-droid.org/packages/com.akylas.enforcedoze/)
* **[NoWakeLock](https://github.com/NoWakeLock/NoWakeLock) ⭐ 309 | 🐛 4 | 🌐 Kotlin | 📅 2026-05-16** - An application that controls Android wakelocks can run on Android N and later. `FOSS` `[LSP]`
* **[⭐ FROSTY](https://github.com/Drsexo/Frosty) ⭐ 219 | 🐛 3 | 🌐 Shell | 📅 2026-09-03** - Optimizes battery life by selectively freezing Google Mobile Services (GMS) components and applying system-wide doze enhancements. `FOSS` `[M]` `[K]`
* **[AntiWakeLock](https://github.com/binarynoise/XposedModulets/releases?q=AntiWakeLock) ⭐ 217 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-03** - Disable WAKE\_LOCK and FLAG\_KEEP\_SCREEN\_ON to save battery. `FOSS` `[LSP]`
* **[BatStats](https://github.com/mlm-games/BatStats) ⭐ 178 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-01** - Battery monitor with stats via Shizuku/root. `FOSS`
* **[GhostGMS](https://github.com/kaushikieeee/GhostGMS) ⭐ 171 | 🐛 3 | 🌐 Shell | 📅 2026-06-07** - Optimize Google Mobile Services for better battery life, privacy, and performance. `FOSS` `[M]`
* **[Xtreme-Battery-Saver](https://github.com/Magisk-Modules-Alt-Repo/Xtreme-Battery-Saver) ⭐ 128 | 🐛 2 | 🌐 Shell | 📅 2025-08-13** - An extreme battery saver Magisk Module for users who want to really stretch their battery life. `FOSS` `[M]`
* **[LSPDoze](https://github.com/Xposed-Modules-Repo/com.op.lspdoze) ⭐ 118 | 🐛 0 | 📅 2026-02-27** - Optimizes your standby battery life. `Proprietary` `[LSP]`
* **[Hyper Optimize](https://github.com/TatshSiow/HyperOptimize) ⭐ 73 | 🐛 0 | 🌐 Shell | 📅 2026-07-28** - Tune HyperOS System and Kernel parameters to reduce power consumption. `FOSS` `[M]`
* **[Universal GMS Doze Fork](https://github.com/MarsPatrick/universal-gms-doze) ⭐ 68 | 🐛 1 | 🌐 Shell | 📅 2026-08-17** - Patches Google Play services app and certain processes/services to be able to use battery optimization. `FOSS` `[M]`
* **[OOSGMS-OPTIMISER](https://github.com/epicmann24/OOSGMS-OPTIMISER) ⭐ 62 | 🐛 1 | 🌐 Shell | 📅 2025-10-12** - Optimise and remove trackers for GMS and OOS. `FOSS` `[M]`
* **[Extreme GMS Doze](https://github.com/Skyghost090/Extreme-Gms-Doze) ⭐ 49 | 🐛 1 | 🌐 Shell | 📅 2025-07-17** - Intelligently kills Google Play Services when your screen is turned off, dramatically boosting battery life. `FOSS` `[M]`
* **[Battery Honey](https://github.com/kaminarich/BatteryHoney) ⭐ 29 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-24** - Optimize Battery Saving when screen OFF. `FOSS` `[M]`
* **[Doze Disabler](https://github.com/draumaz/dozedisabler) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-11-18** - A Magisk module that disables Doze battery optimizations at boot time. `FOSS` `[M]`
* **[Realme-GT3-neo5-CPU-limiter](https://github.com/Quantom2/Realme-GT3-neo5-CPU-limiter) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-09-01** - A Magisk/KSU based module to slow down your CPU to make your screen time better. `FOSS` `[M]` `[K]`
* **[Battery Guru](https://play.google.com/store/apps/details?id=com.paget96.batteryguru)** - Battery optimization and monitoring. `Proprietary`
* **[Drowser](https://gitlab.com/juanitobananas/drowser)** - Drowser is a simple app that kills the apps you select when the screen turns off. `FOSS` | [🌱](https://f-droid.org/app/com.jarsilio.android.drowser)
* **[SaverTuner](https://codeberg.org/s1m/savertuner)** - Allows you to take advantage of this built-in battery saver. You can now set different profiles that save the battery more or less aggressively. [Does not work on Xiaomi](https://codeberg.org/s1m/savertuner/issues/98#issuecomment-5777054). `FOSS` | [🌱](https://f-droid.org/packages/s1m.savertuner/)

> \[!TIP]
> For privacy benefits of reducing Google Services activity, also see [Privacy and Security](#privacy-security).

### Charging & Power

* **[AccA](https://github.com/VR-25/acc) ⭐ 2,390 | 🐛 19 | 🌐 Shell | 📅 2025-06-06** - Advanced Charging Controller app. `FOSS`
* **[FastCharge Next](https://github.com/Dev97633/Fastcharge-next) ⭐ 45 | 🐛 0 | 🌐 Shell | 📅 2026-04-23** - Boost charging speed with smart tweaks. `FOSS` `[M]`
* **[Charging Bypass](https://github.com/AbhishekTor55/charging-bypass-magisk) ⭐ 18 | 🐛 1 | 🌐 Shell | 📅 2025-06-25** - Disables charging when screen is ON and re-enables when OFF. Useful for gaming/dev use. `FOSS` `[M]`

### Task & Process Management

* **[TaskManager](https://github.com/RohitKushvaha01/TaskManager) ⭐ 618 | 🐛 4 | 🌐 C++ | 📅 2026-08-18** - Task Manager inspired from gnome system monitor for android.Must read [F-Droid inclusion](https://github.com/RohitKushvaha01/TaskManager/issues/24) ⭐ 618 | 🐛 4 | 🌐 C++ | 📅 2026-08-18 `FOSS` | [▶️](https://play.google.com/store/apps/details?id=com.rk.taskmanager)
* **[Shappky](https://github.com/YasserNull/shappky) ⭐ 552 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-25** - A simple app to boost performance by stopping background apps, relying on Root/Shizuku permissions. `FOSS` `[M]`
* **[No More Background](https://github.com/adil192/no_more_background) ⭐ 315 | 🐛 11 | 🌐 Dart | 📅 2026-09-01** - A fire-and-forget program to stop Android apps from running in the background. `FOSS` | [🌱](https://f-droid.org/en/packages/com.adilhanney.no_more_background/)
* **[Appzuku](https://github.com/northmendo/Appzuku) ⭐ 184 | 🐛 1 | 🌐 Java | 📅 2026-03-29** - Simple app to boost performance by stopping background apps, relying on Root/Shizuku permissions. `FOSS`
* **[Greenify4Magisk/KSU Reborn](https://github.com/Drsexo/Greenify4Magisk-KSU-Reborn) ⭐ 61 | 🐛 0 | 🌐 Shell | 📅 2026-02-16** - Integrates Greenify as a privileged system app to enable Boost Mode, enhancing hibernation performance without modifying the ROM. `FOSS` `[M]` `[K]`
* **[Operator](https://github.com/by-architect/Operator) ⭐ 34 | 🐛 3 | 🌐 Kotlin | 📅 2025-12-08** - Matrix-inspired Android Task Manager that lets you monitor, manage, and terminate processes directly from your device. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/com.byarchitect.operator)
* **[DeepSuppressor](https://github.com/Aurora-Nasa-1/DeepSuppressor) ⭐ 19 | 🐛 0 | 🌐 C++ | 📅 2025-06-01** - Background process management tool to monitor and control application processes. `FOSS` `[M]`
* **[Background App Slayer (BAS)](https://github.com/UNKNUW/Background-App-Slayer) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-06-05** - Automatic Killing Background apps. `FOSS` `[M]`

[↑ Back to top](#table-of-contents)

***

## Privacy & Security

### Ad & Tracker Blocking

* **[⭐ AdAway](https://github.com/AdAway/AdAway) ⭐ 9,391 | 🐛 670 | 🌐 C | 📅 2026-02-10** - Open-source ad blocker using the hosts file. Blocks ads without permissions. `FOSS` | [🌱](https://f-droid.org/packages/org.adaway)
* **[BlockAds](https://github.com/pass-with-high-score/blockads-android) ⭐ 1,943 | 🐛 63 | 🌐 Kotlin | 📅 2026-08-23** - System‑wide ad, tracker, & malware filtering, custom blocklists, per‑app controls etc. `FOSS` | [🌱](https://f-droid.org/packages/app.pwhs.blockads)
* **[⭐ Bindhosts](https://github.com/bindhosts/bindhosts) ⭐ 1,408 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-30** - Systemless hosts for APatch, KernelSU and Magisk that is fully standalone and self-updating. `FOSS` `[M]` `[K]`
* **[Systemless hosts KernelSU module](https://github.com/symbuzzer/systemless-hosts-KernelSU-module) ⭐ 636 | 🐛 9 | 🌐 Shell | 📅 2025-09-26** - Required module to use applications such as AdAway on KernelSU and APatch. `FOSS` `[K]`
* **[Magisk Ad Blocking Module](https://github.com/pantsufan/Magisk-Ad-Blocking-Module) ⭐ 570 | 🐛 19 | 📅 2026-09-04** - Block ads on android. `FOSS` `[M]`
* **[AdClose](https://github.com/Xposed-Modules-Repo/com.close.hook.ads/) ⭐ 544 | 🐛 3 | 📅 2026-04-08** - Prevents the initial loading of the advertising SDK within the application and intercepts application advertising requests to block ads. `Proprietary` `[LSP]`
* **[F\*ck AD](https://github.com/hujiayucc/Fuck-AD) ⭐ 483 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-16** - Ad-blocking Xposed module. `FOSS` `[LSP]`
* **[Re-Malwack](https://github.com/ZG089/Re-Malwack) ⭐ 448 | 🐛 4 | 🌐 C | 📅 2026-08-16** - A fully-fledged ad-block module. Contains all your needs. `FOSS` `[M]`
* **[StevenBlock](https://github.com/mikropsoft/StevenBlock) ⭐ 297 | 🐛 2 | 🌐 Shell | 📅 2026-04-25** - Ad Blocking Module for Android supporting Magisk, KernelSU and APatch. `FOSS` `[M]`
* **[BlockAds Module](https://github.com/pantsufan/BlockAds) ⭐ 214 | 🐛 2 | 📅 2026-09-01** - BlockAds is an advertisement blocking Magisk module. `FOSS` `[M]` `[K]`
* **[Cubic-AdBlock](https://github.com/Vaz15k/Cubic-AdBlock) ⭐ 77 | 🐛 1 | 🌐 Python | 📅 2026-08-31** - A simple AdBlock module based on the hosts file. `FOSS` `[M]`
* **[Magical Protection](https://github.com/programminghoch10/MagicalProtection) ⭐ 45 | 🐛 1 | 🌐 Shell | 📅 2026-09-02** - Magisk-only completely systemless adblocking. `FOSS` `[M]`
* **[Discover Ads Filter](https://github.com/hxreborn/discover-ads-filter) ⭐ 44 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-03** - Hides sponsored cards and ads from the Google Discover feed in the Pixel Launcher -1 screen and inside the Google app itself. `FOSS` `[LSP]`
* **[Marketing Notification Blocker](https://github.com/lm060719/io.mo.mnblocker) ⭐ 41 | 🐛 0 | 🌐 Java | 📅 2026-07-30** - Intercepts and blocks annoying marketing ads and spam push notifications. `FOSS` `[LSP]`
* **[systemless-adblocker](https://github.com/Magisk-Modules-Alt-Repo/systemless-adblocker) ⭐ 36 | 🐛 0 | 🌐 Shell | 📅 2025-02-22** - Ultimate adblocker module derived from gloeyisk/systemless-hosts. `FOSS` `[M]`
* **[AdAway Helper](https://github.com/DEMONNICA/AdAway-Helper) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2026-06-23** - Enables AdAway to work on KernelSU, its variants by managing /system/etc/hosts via bind mount and overlay. `FOSS` `[M]` `[K]`
* **[AdGuard](https://adguard.com/en/adguard-android/overview.html)** - Comprehensive ad blocking solution. `Proprietary`
* **[Blokada](https://blokada.org/)** - Advanced ad blocker with VPN functionality. `Proprietary`

> \[!TIP]
> **Related Guide**: [Complete Android Ad Blocking Tutorial ↗](./docs/general-guides/android-adblocking.md)\
> For network-level blocking, also check [DNS Tools](#dns-network-filtering) and [Firewall Tools](#firewalls-filtering)

### Firewalls & Filtering

* **[PCAPdroid](https://github.com/emanuele-f/PCAPdroid#pcapdroid) ⭐ 4,656 | 🐛 46 | 🌐 Java | 📅 2026-08-30** - Lets you track, analyze and block the connections made by the other apps in your device. `FOSS` | [🌱](https://f-droid.org/packages/com.emanuelef.remote_capture) | [▶️](https://play.google.com/store/apps/details?id=com.emanuelef.remote_capture)
* **[NetGuard](https://github.com/M66B/NetGuard) ⭐ 3,863 | 🐛 1 | 🌐 Java | 📅 2026-08-01** - Block access to the internet. Apps and addresses can individually be allowed or denied access to your Wi-Fi and/or mobile connection. `FOSS`
* **[AFWall+](https://github.com/ukanth/afwall) ⭐ 3,463 | 🐛 220 | 🌐 Java | 📅 2026-08-06** - Iptables-based firewall. `FOSS` | [🌱](https://f-droid.org/packages/dev.ukanth.ufirewall/) | [▶️](https://play.google.com/store/apps/details?id=dev.ukanth.ufirewall)
* **[ShizuWall](https://github.com/AhmetCanArslan/ShizuWall) ⭐ 2,212 | 🐛 7 | 🌐 Kotlin | 📅 2026-09-03** - Android firewall without VPN powered by Shizuku / local ADB daemon / Root. `FOSS` | [🌱](https://f-droid.org/packages/com.arslan.shizuwall/) | [▶️](https://play.google.com/store/apps/details?id=com.arslan.shizuwall)
* **[Athena](https://github.com/Kin69/Athena) ⭐ 698 | 🐛 43 | 🌐 Kotlin | 📅 2026-01-26** - Material You (Material 3) firewall and ad blocker that works seamlessly on both rooted and non-rooted devices. `FOSS` | [▶️](https://play.google.com/store/apps/details?id=com.kin.athena)
* **[De1984 Firewall](https://github.com/dorumrr/de1984) ⭐ 409 | 🐛 2 | 🌐 Kotlin | 📅 2026-09-04** - A privacy-focused Firewall and Package Manager for Android devices. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/io.github.dorumrr.de1984)
* **[Net Switch](https://github.com/Rem01Gaming/net-switch) ⭐ 322 | 🐛 3 | 🌐 JavaScript | 📅 2025-11-08** - Isolate any app from Internet access. `FOSS` `[M]`
* **[Fyrypt](https://github.com/mirfatif/Fyrypt) ⭐ 75 | 🐛 0 | 📅 2026-08-27** - Android firewall with UID + PID rules, dnscrypt-proxy management, and per-app live network monitoring. `Proprietary`

### Privacy Tools

* **[⭐ Amarok](https://github.com/deltazefiro/Amarok-Hider) ⭐ 3,229 | 🐛 62 | 🌐 Java | 📅 2026-08-11** - Android application which enables you to hide your private files and apps with a single click. `FOSS` | [🌱](https://f-droid.org/zh_Hans/packages/deltazero.amarok.foss/)
* **[Tarnhelm](https://github.com/lz233/Tarnhelm) ⭐ 789 | 🐛 9 | 🌐 Kotlin | 📅 2026-08-13** - The magic to clean sharing links up. `FOSS` `[LSP]`
* **[IAmNotADeveloper](https://github.com/xfqwdsj/IAmNotADeveloper) ⭐ 583 | 🐛 13 | 🌐 Kotlin | 📅 2025-10-23** - Hide Android developer-related switches status. `FOSS` `[LSP]`
* **[FuseFixer](https://github.com/5ec1cff/FuseFixer) ⭐ 403 | 🐛 1 | 🌐 C | 📅 2026-04-14** - Hooks the MediaProvider Fuse Daemon to stop apps probing package existence through `Android/data` directory quirks (Unicode casefold tricks). `FOSS` `[LSP]`
* **[PrivacyFlip](https://github.com/dorumrr/privacyflip) ⭐ 281 | 🐛 13 | 🌐 Kotlin | 📅 2026-01-22** - Automatically disables/enables Wi-Fi, Bluetooth, mobile data, location services, NFC, and even camera/microphone sensors based on lock/unlock state. `FOSS` | [🌱](https://f-droid.org/packages/io.github.dorumrr.privacyflip/)
* **[FuseHide](https://github.com/XiaoTong6666/FuseHide) ⭐ 263 | 🐛 6 | 🌐 C++ | 📅 2026-09-04** - Hides chosen storage paths from MediaProvider on Android 12+ at runtime, and debugs/fixes `Android/data` Unicode casefold scenarios. `FOSS` `[LSP]`
* **[Do Not Try Accessibility](https://github.com/Nitsuya/DoNotTryAccessibility) ⭐ 205 | 🐛 7 | 🌐 Kotlin | 📅 2025-01-23** - Hook System Framework makes the app think that accessibility services are not enabled. `FOSS` `[LSP]`
* **[Transparent Screenshot](https://github.com/Dszsu/Transparent_screenshot) ⭐ 57 | 🐛 0 | 🌐 Java | 📅 2026-06-29** - Hide the application window during screenshots, screen recording, and screen casting. `FOSS` `[LSP]`
* **[GreenDotHide](https://github.com/Dorian399/GreenDotHide) ⭐ 27 | 🐛 1 | 🌐 Java | 📅 2026-03-28** - Hides the green dot indicating sensitive permission use. Works only on MIUI/HyperOS. `FOSS` `[LSP]`
* **[Oplus16 Hide Zoom Window](https://github.com/jhl337/Oplus16_HideZoomWindow) ⭐ 23 | 🐛 2 | 🌐 Java | 📅 2026-01-24** - Hides small windows from screenshots and screen recordings (designed for ColorOS 16). `FOSS` `[LSP]`
* **[Stealth Debug](https://github.com/sp11xy/StealthDebug) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2025-07-22** - Hide USB-Debugging properties. `FOSS` `[M]`
* **[Turn Off Sensors](https://github.com/KatelynTheStargazer/TurnOffSensors-Magisk) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2026-05-12** - Disables device sensors on startup via the sensor\_privacy service on Android. `FOSS` `[M]`
* **[Image Copy Hide](https://github.com/cookieof/ImageCopyHide) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-05-24** - Automatically copy and hide files from /sdcard/DCIM/Camera to /sdcard/wot/cptp. `FOSS` `[M]`
* **[microG Installer Revived Again](https://modules.kernelsu.org/module/microg_installer_revived_again/)** - Promote microG GmsCore, GsfProxy, Companion/Play Store, and MapsV1 to system with privileged permissions. `FOSS` `[M]` `[K]`
* **[MicroGPlus](https://bitgapps.io/extra)** - Installs microG services and other useful apps. `Proprietary` `[M]` `[K]`

### Security Tools

> \[!NOTE]
>
> **FLAG\_SECURE** is a window-level security flag in Android that **prevents the window's content from appearing in screenshots** or being captured during screen recordings.

* **[Always Trust User Certs](https://github.com/NVISOsecurity/AlwaysTrustUserCerts) ⭐ 2,557 | 🐛 10 | 🌐 Shell | 📅 2025-06-24** - A Magisk/KernelSU module that automatically adds user certificates to the system root CA store. `FOSS` `[M]` `[K]`
* **[⭐ Move Certificate](https://github.com/ys1231/MoveCertificate) ⭐ 1,962 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-02** - Move user certificates to system certificates. Supports Android 7-16. `FOSS` `[M]` `[K]`
* **[StrykerOSS](https://github.com/zalexdev/strykerapp) ⭐ 1,482 | 🐛 22 | 🌐 Java | 📅 2026-08-13** - Bundles a curated set of network, wireless and web security tools into a single rooted-Android application for penetration testing. `FOSS`
* **[⭐ Enable Screenshot](https://github.com/LSPosed/DisableFlagSecure) ⭐ 1,310 | 🐛 7 | 🌐 Java | 📅 2026-09-01** - Enabling screenshots in apps that normally wouldn't allow it, and disabling screenshot(Android 14+) and screen record(Android 15+) detection. `FOSS` `[LSP]`
* **[⭐ Flag Secure Patcher](https://github.com/j-hc/FlagSecurePatcher) ⚠️ Archived** - Patch service.jar on device to disable secure lock and screenshot listeners. `FOSS` `[M]`
* **[CaptureSposed](https://github.com/99keshav99/CaptureSposed) ⭐ 296 | 🐛 3 | 🌐 Kotlin | 📅 2026-06-28** - Disables the newly introduced screenshot detection API in Android 14. `FOSS` `[LSP]`
* **[Cert-Fixer](https://github.com/pwnlogs/cert-fixer) ⭐ 282 | 🐛 0 | 🌐 Shell | 📅 2026-07-07** - Installs custom CA certificates to Android's system certificate store. `FOSS` `[M]`
* **[DriFiCrack](https://github.com/ZeltNamizake/DriFiCrack) ⚠️ Archived** - Brute Force Tool to Crack Wi-Fi Passwords. `FOSS` `[M]`
* **[AlternativeUnlockXposed](https://github.com/leohearts/AlternativeUnlockXposed) ⭐ 185 | 🐛 10 | 🌐 Kotlin | 📅 2025-12-20** - Unlock your Android phone with an alternative PIN. `FOSS` `[LSP]`
* **[ih8SecureLock](https://github.com/j-hc/ih8SecureLock) ⭐ 177 | 🐛 2 | 🌐 C++ | 📅 2026-08-15** - Prevent apps from blocking and listening to your screenshots with Zygisk. `FOSS` `[M]` `[K]`
* **[⭐ SSL Killer](https://github.com/Xposed-Modules-Repo/com.simo.ssl.killer) ⭐ 168 | 🐛 0 | 📅 2026-08-04** - Bypass multiple ssl pinning implementations. `Proprietary` `[LSP]`
* **[TapDucky](https://github.com/iodn/tap-ducky) ⭐ 163 | 🐛 8 | 🌐 Dart | 📅 2026-05-17** - Open-source DuckyScript runner for rooted Android with USB Gadget (ConfigFS) support. `FOSS`  | [🌱](https://f-droid.org/en/packages/org.kaijinlab.tap_ducky/)
* **[Just Trust Me Pro](https://github.com/hang666/JustTrustMePro) ⭐ 154 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-27** - Disables SSL certificate checking for the purposes of auditing an app with cert pinning. `FOSS` `[M]`
* **[Biometric Bypass Module](https://github.com/hxreborn/biometric-bypass) ⭐ 143 | 🐛 1 | 🌐 Kotlin | 📅 2026-09-02** - Fast-forwards face unlock by skipping the biometric confirmation step in System UI on Android 10+. `FOSS` `[LSP]` | [🌱](https://f-droid.org/packages/eu.rafareborn.biometricbypass)
* **[OneShot Extended](https://github.com/chickendrop89/OneShot-Extended) ⭐ 123 | 🐛 0 | 🌐 Python | 📅 2026-07-14** - Performs various WPS attacks without the requirement of monitor mode. `FOSS` `[M]` `[K]`
* **[Simple Flag Secure](https://github.com/ShivamXD6/Simple-Flag-Secure) ⭐ 105 | 🐛 4 | 🌐 Shell | 📅 2026-09-03** - Disable Secure Flag and allow taking screenshots/screen recording in apps supports KSU/APatch . `FOSS` `[M]` `[K]`
* **[Custom Certificate Authorities](https://github.com/Magisk-Modules-Alt-Repo/custom-certificate-authorities) ⭐ 91 | 🐛 2 | 🌐 Shell | 📅 2026-06-15** - Moves user-installed certificate authorities into the system trust store, making them trusted by all apps. `FOSS` `[M]`
* **[Android-FlagSecure-Disabler](https://github.com/BlassGO/Android-FlagSecure-Disabler) ⭐ 74 | 🐛 1 | 🌐 Shell | 📅 2026-05-13** - FlagSecure Disabler, Screenshot Observer Disabler & DRM Disabler. `FOSS` `[M]` `[K]`
* **[Biometric App Lock](https://github.com/hxreborn/biometric-app-lock) ⭐ 50 | 🐛 5 | 🌐 Kotlin | 📅 2026-09-02** - Locks apps you choose behind fingerprint or face unlock. `FOSS` `[LSP]`
* **[Disable usb debugging](https://github.com/Aakif17/disable_usb_debugging) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-03-12** - Disables USB Debugging after every reboot. `FOSS` `[M]`
* **[Custom Certificates](https://github.com/YujiaCheng1996/custom-certificates) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-19** - A Magisk/KernelSU module which adds custom certificates to the system trust store. `FOSS` `[M]` `[K]`
* **[PinGuard](https://github.com/khiqwq/PinGuard/blob/main/README_EN.md) ⭐ 2 | 🐛 0 | 🌐 Kotlin | 📅 2026-04-17** - LSPosed module that requires fingerprint / password to unpin screen-pinned apps. `FOSS` `[LSP]`

### Device ID & Spoofing

* **[Device Faker](https://github.com/Seyud/device_faker/) ⭐ 742 | 🐛 1 | 🌐 Vue | 📅 2026-09-04** - A device model spoofing module based on Zygisk that can configure different device models for different applications. `FOSS` `[M]` `[K]`
* **[DeviceID/SSAID Changer](https://github.com/sidex15/deviceidchanger) ⭐ 270 | 🐛 4 | 🌐 HTML | 📅 2025-12-19** - A simple WebUI Module to change SSAID/DeviceID on Rooted Android Devices with Apatch, KSU (And its forks), or Magisk. `FOSS` `[M]` `[K]`
* **[MACsposed](https://github.com/DavidBerdik/MACsposed) ⭐ 157 | 🐛 9 | 📅 2026-08-17** - Adds support for MAC Address spoofing to Android 12 through 15. `Proprietary` `[LSP]`
* **[SpoofMyDevice](https://github.com/BuSung-dev/SpoofMyDevice) ⭐ 135 | 🐛 10 | 🌐 Java | 📅 2026-07-19** - Xposed module and companion app for building, saving, and applying spoofed Android device profiles to selected apps. `FOSS` `[LSP]`
* **[HideMyAndroid](https://github.com/Xposed-Modules-Repo/com.wowsoftware.hidemyandroid/) ⭐ 94 | 🐛 0 | 📅 2026-09-04** - Android anti-detect module with profile isolation and spoofing. `Proprietary` `[LSP]`
* **[Geergit](https://github.com/pyshivam/geergit-discussion) ⭐ 72 | 🐛 14 | 📅 2026-05-03** - Change (MASKE) the various IDs in the Phone. `Proprietary` `[LSP]`
* **[MAC Editor for Android](https://github.com/jqssun/android-mac-editor) ⭐ 62 | 🐛 2 | 🌐 Kotlin | 📅 2026-06-02** - Securely edit Wi-Fi MAC address on Android. `FOSS` `[LSP]`
* **[Telephony Spoofer](https://github.com/BrianWalczak/TelephonySpoofer) ⭐ 49 | 🐛 0 | 🌐 Java | 📅 2026-03-07** - Spoof cellular information, including eSIM compatibility. `FOSS` `[LSP]`
* **[SSAID (Android ID Modifier)](https://github.com/HSSkyBoy/AndroidIDChange) ⭐ 34 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-17** - A modern Android SSAID (Android ID) inspector, modifier, backup, and management utility. `FOSS` `[LSP]`
* **[Privacy Kit](https://github.com/Xposed-Modules-Repo/com.sal.privacykit) ⭐ 28 | 🐛 0 | 📅 2026-08-22** - Per-app Android identifier spoofing for LSPosed. `Proprietary` `[LSP]`

### App Isolation

* **[Island](https://github.com/oasisfeng/island/tree/dev) ⭐ 3,901 | 🐛 670 | 🌐 Java | 📅 2025-04-24** - App isolation and cloning. `FOSS` | [▶️](https://play.google.com/store/apps/details?id=com.oasisfeng.island)
* **[Insular](https://gitlab.com/secure-system/Insular)** - Isolate your big brother app. A fork based on the excellent Island. `FOSS` | [🌱](https://f-droid.org/packages/com.oasisfeng.island.fdroid)
* **[Shelter](https://gitea.angry.im/PeterCxy/Shelter)** - Isolate and clone apps. `FOSS` | [🌱](https://f-droid.org/app/net.typeblog.shelter)

[↑ Back to top](#table-of-contents)

***

## Apps & App Modifications

### App Patchers

* **[⭐ Morphe](https://morphe.software/)** - A next-generation app patcher built by some of the original ReVanced developers. It offers a modern interface, enhanced stability, and a growing list of supported apps and features. `FOSS`
* **[Lucky Patcher](https://www.luckypatchers.com/)** - App patcher and modifier (use with caution). `Proprietary`
* **[ReVanced](https://revanced.app/)** - A powerful app patcher that allows you to modify popular apps like YouTube, Spotify, and more with additional features and customizations. `FOSS`

> \[!TIP]
> Also check out [Morphe Patches list ↗](https://morphe-patches.software/)

### App Mods

* **[FingerprintPay](https://github.com/eritpchy/FingerprintPay) ⭐ 4,497 | 🐛 35 | 🌐 Java | 📅 2026-03-06** - Enables fingerprint payment via WeChat, Alipay, Taobao, Tencent QQ, and UnionPay on phones that support fingerprint recognition. `FOSS` `[M]` `[LSP]`
* **[Keyboard GPT](https://github.com/Mino260806/KeyboardGPT) ⭐ 704 | 🐛 20 | 🌐 Java | 📅 2025-08-18** - Lets you integrate Generative AI like ChatGPT in keyboard. `FOSS` `[LSP]`
* **[Rboard Theme Manager](https://github.com/DerTyp7214/RboardThemeManagerV3) ⚠️ Archived** - A customizable manager app for Google Gboard that allows users to download, apply, and manage various themes and sound settings. `FOSS` `[LSP]`
* **[⭐ GPhotosUnlimited](https://github.com/Rev4N1/GPhotosUnlimited) ⭐ 354 | 🐛 1 | 🌐 C++ | 📅 2026-09-04** - A Zygisk module which gives unlimited Google Photos storage. `FOSS` `[M]` `[K]`
* **[Deekseep](https://github.com/lllucccian/Deekseep) ⭐ 280 | 🐛 3 | 🌐 Java | 📅 2026-08-28** - Adds account, chat, image, interface, and local API tools to the official DeepSeek Android app. `FOSS` `[LSP]`
* **[Spotify Plus](https://github.com/LeNerd46/SpotifyPlus) ⭐ 220 | 🐛 11 | 🌐 Java | 📅 2026-08-31** - Adds beautiful lyrics to Spotify. `FOSS` `[LSP]`
* **[Xposed Translate Text](https://github.com/tianci-sh/XPTranslateText) ⭐ 187 | 🐛 13 | 🌐 Java | 📅 2025-12-16** - Translate text by MLKit / gemini2.0 / google api. `FOSS` `[LSP]`
* **[Breeno Source Changer](https://github.com/Xposed-Modules-Repo/com.niki.breeno.openai/tree/main) ⭐ 159 | 🐛 5 | 📅 2026-09-03** - Allows ColorOS's Breeno Assistant to change its AI model source and customize large language model (LLM) APIs. `FOSS` `[LSP]`
* **[Nexus](https://github.com/niki914/agentic-nexus) ⭐ 139 | 🐛 28 | 🌐 Kotlin | 📅 2026-09-04** - Plug your own model into your phone's voice assistant. `Proprietary` `[LSP]`
* **[GboardHook](https://github.com/chenyue404/GboardHook) ⭐ 135 | 🐛 2 | 🌐 Kotlin | 📅 2026-06-14** - Modifies the number of clipboard items displayed and their expiration time. `FOSS` `[LSP]`
* **[E-Government Liberator](https://github.com/Crazyphil/digitales-amt-liberator) ⭐ 111 | 🐛 15 | 🌐 Kotlin | 📅 2025-01-12** - Removes root and bootloader checks from e-government apps. `FOSS` `[LSP]`
* **[AmznKiller](https://github.com/hxreborn/amznkiller) ⭐ 86 | 🐛 2 | 🌐 Kotlin | 📅 2026-09-04** - Hides sponsored content and ads in the Amazon Shopping app. `FOSS` `[LSP]`
* **[KGPT](https://github.com/eluea/KGPT) ⭐ 86 | 🐛 6 | 🌐 Java | 📅 2026-08-25** - LSPosed Module to integrate Generative AI like ChatGPT in keyboard. `FOSS` `[LSP]`
* **[Play Store Adblock](https://github.com/hxreborn/playstore-adblock) ⭐ 85 | 🐛 5 | 🌐 Kotlin | 📅 2026-09-03** - Xposed module to remove sponsored listings and ads from the Google Play Store. `FOSS` `[LSP]`
* **[XposedPhotosFix](https://github.com/RevealedSoulEven/XposedPhotosFIX) ⭐ 72 | 🐛 0 | 🌐 Java | 📅 2026-08-05** - Prevents Google Photos app from merging all folders into Camera and creates separate albums for each folder, useful for backups. `FOSS` `[LSP]`
* **[Yandex Maps Patcher](https://github.com/Xposed-Modules-Repo/ru.bluecat.yandexmapspatcher) ⭐ 65 | 🐛 0 | 📅 2026-07-26** - Hides ads and intrusive services in the Yandex Maps app. `Proprietary` `[LSP]`
* **[F\*\*k Solid Explorer](https://github.com/fzer0x/dev.fzer0x.fucksolidexplorer) ⭐ 41 | 🐛 0 | 🌐 Kotlin | 📅 2026-01-23** - Unlock premium features and remove advertisements from Solid Explorer. `FOSS` `[LSP]`
* **[Gboard Material Expressive Black](https://github.com/hxreborn/gboard-material-expressive-black) ⭐ 36 | 🐛 8 | 🌐 Kotlin | 📅 2026-08-01** - Enables pitch black Gboard background on Android 16 dynamic theme. `FOSS` `[LSP]`
* **[Spicy EX](https://github.com/amarinne/spicy-ex) ⭐ 23 | 🐛 1 | 🌐 Java | 📅 2026-09-04** - Adds Spicy lyrics in Spotify along with translation and much more UI features. `FOSS` `[LSP]`
* **[KeyFlux](https://github.com/NawafCode/KeyFlux) ⭐ 22 | 🐛 3 | 🌐 Kotlin | 📅 2026-07-02** - Customize Google Gboard, exposing selected hidden features, and adding clipboard-related enhancements. `FOSS` `[LSP]`
* **[EDS NG Crack](https://github.com/dumbasPL/EDS-NG-crack) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2025-10-03** - Unlocks all features in [EDS NG](https://play.google.com/store/apps/details?id=com.sovworks.projecteds\&hl=en_US). `FOSS` `[M]`
* **[NSG Tweaks](https://github.com/h3nnes/nsg-tweaks) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2026-08-27** - Extends [NSG (QuickTest) ↗](https://play.google.com/store/apps/details?id=com.qtrun.QuickTest) with additional columns, rows, signaling tools, and log-replay improvements. `Proprietary` `[LSP]`
* **[G-News Control](https://github.com/mango0oo/G-News-Control) ⭐ 15 | 🐛 1 | 📅 2025-09-22** - Magisk / KernelSU module for control the Google News on the home screen. `Proprietary` `[M]` `[K]`
* **[Yandex Music Downloader](https://github.com/errorman-awful/YMDownloaderXposed) ⭐ 13 | 🐛 4 | 📅 2025-12-11** - Download flac Music from Yandex Music app. `Proprietary` `[LSP]`
* **[Timeline Unlocker](https://github.com/SherlockChiang/ReLocationReportEnabler) ⭐ 9 | 🐛 8 | 🌐 Java | 📅 2026-08-29** - Lets GMS Location History / Timeline be enabled on devices whose SIM is registered in a region where Google has restricted the feature. `FOSS` `[LSP]`
* **[LSpot](https://codeberg.org/dapsvi/LSpot)** - Blocks ads in Spotify by intercepting OkHttp requests to ad endpoints. `FOSS` `[LSP]`

### Social Media Mods

#### Bilibili

* **[BBZQ](https://github.com/HSSkyBoy/BBZQ) ⭐ 433 | 🐛 15 | 🌐 Kotlin | 📅 2026-09-02** - Removes unnecessary content, optimizes the core experience, and provide various practical functions. `FOSS` `[LSP]`

#### Discord

* **[Revenge](https://github.com/revenge-mod/revenge-bundle-next) ⭐ 172 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-31** - Revenge is a client modification for Discord Android. `FOSS`
* **[Kettu](https://github.com/C0C0B01/KettuXposed) ⭐ 48 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-02** - A Discord mobile app client modification continuing Bunny's mission. `FOSS` `[LSP]`

#### Facebook

* **[Chat Head Enabler](https://github.com/NeonOrbit/ChatHeadEnabler) ⭐ 100 | 🐛 1 | 🌐 Java | 📅 2025-12-06** - Lets you choose between chat head and bubble in Facebook Messenger. `FOSS` `[LSP]`
* **[Facebook App Ads Remover](https://github.com/Xposed-Modules-Repo/tn.loukious.facebookappadsremover) ⭐ 58 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-29** - Removes ads from Facebook app. `FOSS` `[LSP]`

#### Instagram

* **[InstaEclipse](https://github.com/ReSo7200/InstaEclipse/) ⭐ 1,421 | 🐛 20 | 🌐 Java | 📅 2026-07-24** - Adds Features like Developer Options, Ghost Mode, Ad-Free browsing, and Distraction-Free Mode to Instagram. `FOSS` `[LSP]`

#### Line

* **[Knot](https://github.com/2b-zipper/Knot) ⭐ 119 | 🐛 2 | 🌐 Java | 📅 2026-09-03** - Message privacy, notification tweaks & Screen display & UI mods for Line. `FOSS` `[LSP]`

#### QQ

* **[QAuxiliary](https://github.com/cinit/QAuxiliary) ⭐ 5,730 | 🐛 270 | 🌐 Java | 📅 2026-09-04** - Xposed module based on QNotified. `FOSS` `[LSP]`
* **[XAutoDaily](https://github.com/LuckyPray/XAutoDaily) ⭐ 1,582 | 🐛 37 | 🌐 Kotlin | 📅 2026-08-25** - Various tweaks for QQ. `FOSS` `[LSP]`
* **[QFun](https://github.com/oneQAQone/QFun) ⭐ 254 | 🐛 1 | 🌐 Java | 📅 2026-09-02** - Functionality enhancement module developed based on the Xposed framework. `FOSS` `[LSP]`
* **[TCQT Module](https://github.com/callng/TCQT) ⭐ 230 | 🐛 4 | 🌐 Kotlin | 📅 2026-09-04** - An Xposed module designed for Android QQ/TIM clients, which is used to intercept and retain messages that would otherwise be "retracted". `FOSS` `[LSP]`
* **[NewQStory](https://github.com/Xposed-Modules-Repo/lin.xposed/) ⭐ 154 | 🐛 0 | 📅 2026-06-20** - Xposed QQ module. `Proprietary` `[LSP]`

#### Reddit

> \[!IMPORTANT]
>
> All Reddit patches require: [Morphe App ↗](https://morphe.software/)

* **[Morphe Reddit Patches](https://github.com/MorpheApp/morphe-patches#-patches-list) ⭐ 3,515 | 🐛 464 | 🌐 Java | 📅 2026-09-04** - Various patches for reddit. `FOSS`
* **[Patcheddit](https://github.com/wchill/patcheddit) ⭐ 783 | 🐛 49 | 🌐 Kotlin | 📅 2026-05-03** - Custom patches with features like view: deleted Reddit posts & comments,Banned subreddits etc. `FOSS`
* **[Adobo Patches](https://github.com/jkennethcarino/adobo/) ⭐ 247 | 🐛 10 | 🌐 Kotlin | 📅 2026-08-31** - Various patches for reddit app. `FOSS`

#### Telegram

* **[TMoe](https://github.com/cinit/TMoe) ⭐ 1,429 | 🐛 20 | 🌐 Java | 📅 2026-07-19** - Adds various tweaks to various Telegram clients. `FOSS` `[LSP]`
* **[Killergram](https://github.com/shatyuka/Killergram) ⭐ 587 | 🐛 0 | 🌐 Java | 📅 2026-08-24** - Remove sponsored messages of Telegram. `FOSS` `[LSP]`
* **[TeleVip](https://github.com/Xposed-Modules-Repo/com.my.televip/) ⭐ 328 | 🐛 0 | 📅 2026-07-11** - A module for modifying Telegram with hide seen status, unlocking channel restrictions etc. `Proprietary` `[LSP]`
* **[Telegami](https://github.com/aoya111/Telegami) ⭐ 229 | 🐛 36 | 🌐 Kotlin | 📅 2026-09-04** - Various tweaks for Telegram. `FOSS` `[LSP]`
* **[Telegram Speed Hook](https://github.com/araafroyall/Telegram-Speed-Hook) ⭐ 158 | 🐛 0 | 🌐 Java | 📅 2026-08-12** - Increase Telegram files/media downloading speed. `FOSS` `[LSP]`
* **[Telegram Tweaks](https://github.com/Xposed-Modules-Repo/ru.mike.sidestories) ⭐ 32 | 🐛 1 | 📅 2026-06-29** - Remove action bar stories in the Telegram messenger (+block unmute button). `Proprietary` `[LSP]`
* **[GramSieve](https://github.com/Xposed-Modules-Repo/com.tianqianguai.gramsieve) ⭐ 27 | 🐛 0 | 🌐 Java | 📅 2026-09-03** - Message filtering, host-settings integration, anti-recall, anti-edit/edit interception etc. `Proprietary` `[LSP]`

#### TikTok

* **[Douyin Enhancer](https://github.com/twyora/DouyinEnhancer) ⭐ 106 | 🐛 4 | 🌐 Kotlin | 📅 2026-09-04** - Adds minor quality-of-life features to Douyin (Chinese TikTok). `FOSS` `[LSP]`
* **[Toki](https://github.com/MeiYongAI/Toki) ⭐ 69 | 🐛 4 | 🌐 Java | 📅 2026-08-19** - Adds various tweaks to TikTok app. `FOSS` `[LSP]`
* **[TikTok AntiBurn](https://github.com/0mnr0/TikTokAntiBurn) ⭐ 48 | 🐛 2 | 🌐 Java | 📅 2026-08-30** - Overlap the TikTok app elements to prevent the screen from burning out. `FOSS` `[LSP]`

#### WeChat

* **[WeChat Auxiliary](https://github.com/HdShare/WAuxiliary_Public) ⭐ 3,989 | 🐛 12 | 🌐 Kotlin | 📅 2026-05-31** - Various tweaks for WeChat. `Proprietary` `[LSP]`
* **[MaskWechat](https://github.com/Mingyueyixi/MaskWechat) ⭐ 512 | 🐛 34 | 🌐 Kotlin | 📅 2025-06-21** - Hide the chat records of specific users to prevent private chats from being peeked by third parties. `FOSS` `[LSP]`
* **[WePadBridge](https://github.com/libingtong/WePadBridge) ⭐ 8 | 🐛 1 | 🌐 Kotlin | 📅 2025-09-01** - Enables tablet interface and features in WeChat Work mobile app. `FOSS` `[LSP]`
* **[NewMiko](https://modules.lsposed.org/module/im.mingxi.miko/)** - Various tweaks related to  WeChat app. `Proprietary` `[LSP]`

#### Weibo

* **[WeiboHelper](https://github.com/Xposed-Modules-Repo/com.skyhand.sinahelper) ⭐ 274 | 🐛 1 | 📅 2025-06-23** - Remove all available advertisements and recommendations from Weibo. `Proprietary` `[LSP]`

#### WhatsApp

* **[⭐ WA Enhancer](https://github.com/Dev4Mod/WaEnhancer) ⭐ 1,682 | 🐛 246 | 🌐 Kotlin | 📅 2026-09-01** - Enhances your WhatsApp experience. `FOSS` `[LSP]`
* **[WA Enhancer X](https://github.com/Xposed-Modules-Repo/com.waenhancer) ⭐ 36 | 🐛 0 | 📅 2026-09-02** - Fork of WA Enhancer with additional features. `Proprietary` `[LSP]`
* **[WAPlus](https://github.com/RevealedSoulEven/WAPlusXposed) ⭐ 35 | 🐛 0 | 🌐 Kotlin | 📅 2026-06-29** - Unlock WhatsApp Plus Features. `FOSS` `[LSP]`
* **[WaThemer](https://github.com/ayane-04/wathemer) ⭐ 9 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-03** - Themes WhatsApp with custom colors, chat bubble shapes, wallpapers, fonts, icons, system bars and a Liquid Glass mode. Requires Android 12+. `FOSS` `[LSP]`

#### X/Twitter

* **[⭐ Piko Patches](https://github.com/crimera/piko) ⭐ 5,094 | 🐛 243 | 🌐 Java | 📅 2026-09-04** - Morphe patches for twitter with features like hide promoted tweets, hide promoted accounts, hide promoted trends, hide "who to follow" etc. `FOSS`
* **[Re:X](https://github.com/Xposed-Modules-Repo/one.dot.rex) ⭐ 181 | 🐛 0 | 📅 2026-08-30** -  Tweaks for the new X / Twitter app. `Proprietary` `[LSP]`

> \[!TIP]
> Also check out [App Patchers section](#app-patchers)

### Browser Mods

* **[BetterVia](https://github.com/JiGuroLGC/BetterVia) ⭐ 1,279 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-25** - Bypass whitelist restrictions, Screenshot protection, Block components, One-tap theme switching etc. `FOSS` `[LSP]`
* **[⭐ ChromeXt](https://github.com/JingMatrix/ChromeXt) ⭐ 1,133 | 🐛 28 | 🌐 Kotlin | 📅 2026-08-20** - UserScript and DevTools support for Chromium-based and WebView-based browsers. `FOSS` `[LSP]`
* **[EdgeX](https://github.com/SoClear/EdgeX) ⭐ 145 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-01** - An Xposed module for Microsoft Edge on Android, designed to enhance your browsing experience with UI tweaks and functional improvements. `FOSS` `[LSP]`
* **[FoldDevtools](https://github.com/achyuki/FoldDevtools) ⭐ 44 | 🐛 1 | 🌐 Kotlin | 📅 2025-11-04** - Using chrome devtools to debug webview on Android. `FOSS` `[LSP]`
* **[Fxxk-MiBrowser](https://github.com/DuhMatt/Fxxk-MiBrowser) ⭐ 31 | 🐛 1 | 🌐 Kotlin | 📅 2026-09-04** - Redirects forced Xiaomi Browser links to the system default browser. `FOSS` `[LSP]`

### YouTube & Media Mods

* **[NexAlloy](https://github.com/NexAlloy/NexAlloy) ⭐ 2,933 | 🐛 4 | 🌐 Kotlin | 📅 2026-09-04** - YouTube, YT Music block ads, background playback, sponsorblock and much more. Also unlocks premium features of Strava and Photomath. Unlimited Google Photos backup. `FOSS` `[LSP]`
* **[PolyglotYT](https://github.com/Dr-TSNG/PolyglotYT) ⭐ 180 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-15** - Immersive translation Xposed module for YouTube app. `FOSS` `[LSP]`
* **[GlassMic](https://github.com/lm060719/io.mo.glassmic) ⭐ 58 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-30** - Lets you route an imported audio file into target recording apps through AudioRecord/AAudio hooks. `FOSS` `[LSP]`
* **[OnePlus 8 Series and 9R Camera Unlocker](https://github.com/Magisk-Modules-Alt-Repo/oneplus-8series-9r-camera-unlocker) ⭐ 22 | 🐛 0 | 🌐 Shell | 📅 2025-06-23** - Enables 48MP RAW10 capture support, both on the main (8/8T/9R) and ultra wide (8 Pro) lenses and much more. `FOSS` `[M]`
* **[xCam](https://github.com/hazbu/xCam) ⭐ 22 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-14** - Replace live camera feeds and actual photo captures with virtual media sources. `FOSS` `[LSP]`
* **[VideoSpeed](https://github.com/MarsGao/io.github.MarsGao.speed) ⭐ 20 | 🐛 0 | 🌐 Java | 📅 2026-08-30** - An Xposed module for adjusting the playback speed of videos across multiple applications. `FOSS` `[LSP]`
* **[XAudioCapture](https://github.com/Xposed-Modules-Repo/io.github.wzhy.xaudiocapture) ⭐ 17 | 🐛 0 | 📅 2025-05-11** - Lets you capture any audio stream you desire, bypassing these restrictions. `Proprietary` `[LSP]`

### Signature & Verification

* **[⭐ Core Patch N](https://github.com/LSPosed/CorePatch) ⭐ 3,322 | 🐛 10 | 🌐 Kotlin | 📅 2026-07-26** - Disable signature verification For Android. `FOSS` `[LSP]`
* **[⭐ Pairipfix](https://github.com/ahmedmani/pairipfix) ⭐ 659 | 🐛 20 | 🌐 Java | 📅 2026-04-20** - Bypasses the "Get this app from Play" screen that appears when installing Android apps as an APK instead of from the Google Play Store. `FOSS` `[LSP]`
* **[F\*\*k Google License](https://github.com/JiGuroLGC/FuckGoogleLicense) ⭐ 211 | 🐛 0 | 🌐 Java | 📅 2026-08-16** - Bypass Google Service License Verification. `FOSS` `[LSP]`
* **[Apk Protection Patch](https://github.com/Mods-Center/Apk-Protection-Patch) ⭐ 205 | 🐛 10 | 📅 2025-08-12** - Removes signature verification restrictions on AOSP and OEM ROMs (HyperOS, ColorOS, etc.), allowing installation of modified APKs. `Proprietary` `[M]` `[K]`
* **[XSpoofSignatures](https://github.com/rushiiMachine/XSpoofSignatures) ⭐ 85 | 🐛 0 | 🌐 Java | 📅 2025-03-19** - Spoof package signatures. `FOSS` `[LSP]`

[↑ Back to top](#table-of-contents)

***

## Storage & Data

### File Managers

* **[Material Files](https://github.com/zhanghai/MaterialFiles) ⭐ 8,851 | 🐛 628 | 🌐 Kotlin | 📅 2026-04-06** - Modern file manager with root capabilities. `FOSS` | [🌱](https://f-droid.org/packages/me.zhanghai.android.files)| [▶️](https://play.google.com/store/apps/details?id=me.zhanghai.android.files)
* **[AnExplorer](https://github.com/1hakr/AnExplorer) ⭐ 2,022 | 🐛 36 | 🌐 Java | 📅 2026-06-02** - A simple, Small, Fast and Efficient File Explorer. `FOSS` | [▶️](https://play.google.com/store/apps/details?id=dev.dworks.apps.anexplorer)
* **[Fossify File Manager](https://github.com/FossifyOrg/File-Manager) ⭐ 1,740 | 🐛 95 | 🌐 Kotlin | 📅 2026-09-01** - Easy app for managing your files without ads, respecting your privacy and security. `FOSS` | [🌱](https://f-droid.org/packages/org.fossify.filemanager/) | [▶️](https://play.google.com/store/apps/details?id=org.fossify.filemanager)
* **[NoStorageRestrict](https://github.com/Xposed-Modules-Repo/com.github.dan.nostoragerestrict) ⭐ 514 | 🐛 3 | 🌐 Java | 📅 2026-07-29** - Removes the restriction when selecting folders (Sdcard, Download, data and obb) through the file manager on Android 11 and higher. `FOSS`
* **[Remember My Sort](https://github.com/hxreborn/remember-my-sort) ⭐ 101 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-07** - Forces the native Android file picker to remember your sorting preferences. `FOSS` `[LSP]` | [🌱](https://apt.izzysoft.de/packages/eu.hxreborn.remembermysort)
* **[Sortify](https://github.com/xCaptaiN09/Sortify) ⭐ 37 | 🐛 0 | 🌐 Shell | 📅 2026-01-19** - Automatically organizes files in your Download folder. `FOSS` `[M]` `[K]`
* **[⭐ MiXplorer](https://mixplorer.com/)** - Feature-rich file manager. `Proprietary`
* **[File Manager](https://play.google.com/store/apps/details?id=com.alphainventor.filemanager\&hl=en)** - Easy and powerful file explorer for Android devices. It’s free, fast and full-featured. Because of its simple UI, it’s extremely easy to use. `Proprietary`
* **[File Manager - File Browser](https://play.google.com/store/apps/details?id=com.alc.filemanager)** - Manage your files (file explorer) like you do on your desktop or laptop using Multiple Select, Cut/Copy/Paste, Move, Create, Delete, Rename, Search etc. `Proprietary`
* **[MT Manager](https://mt2.cn/)** - File Management and Reverse Engineering Tool for Android. `Proprietary`
* **[Root Explorer](https://play.google.com/store/apps/details?id=com.speedsoftware.rootexplorer)** - File manager with root access. `Proprietary`
* **[RS File Manager File Explorer](https://play.google.com/store/apps/details?id=com.rs.explorer.filemanager)** - Free, Safe, Simple, Manage your files efficiently and easily with RS File Manager. `Proprietary`
* **[Solid Explorer](https://play.google.com/store/apps/details?id=pl.solidexplorer2)** - Powerful file manager with root support. `Proprietary`
* **[Total Commander](https://play.google.com/store/apps/details?id=com.ghisler.android.TotalCommander)** - A feature rich file manager for Android. For  a better experience, please read [this](https://www.ghisler.ch/board/viewforum.php?f=22). `Proprietary`
* **[ZArchiver](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver)** - A program for archive management (including managing of application backups in archives). `Proprietary`

### Backup & Restore

* **[DataBackup](https://github.com/XayahSuSuSu/Android-DataBackup) ⭐ 7,310 | 🐛 190 | 🌐 Kotlin | 📅 2026-08-29** - DataBackup for Android 7.0+. `FOSS` | [🌱](https://f-droid.org/zh_Hans/packages/com.xayah.databackup.foss/)
* **[Neo Backup](https://github.com/NeoApplications/Neo-Backup) ⭐ 3,794 | 🐛 242 | 🌐 Kotlin | 📅 2026-05-03** - Powerful open-source backup solution. `FOSS` | [🌱](https://f-droid.org/packages/com.machiav3lli.backup/)
* **[Restoid](https://github.com/hddq/restoid) ⭐ 168 | 🐛 22 | 🌐 Kotlin | 📅 2026-09-03** - modern, root-based Android app backup tool powered by restic. `FOSS`
* **[⭐ Swift Backup](https://play.google.com/store/apps/details?id=org.swiftapps.swiftbackup)** - Modern backup solution with cloud support. `Proprietary`
* **[DiskDigger](https://play.google.com/store/apps/details?id=com.defianttech.diskdigger)** - A powerful data recovery tool for Android devices. `Proprietary`
* **[Dumpster: Photo/Video Recovery](https://play.google.com/store/apps/details?id=com.baloota.dumpster)** - You can recover deleted videos, restore photos, undelete recently deleted apps, and other files. `Proprietary`

### Cleaning

* **[⭐ SD Maid 2/SE](https://github.com/d4rken-org/sdmaid-se) ⭐ 7,451 | 🐛 13 | 🌐 Kotlin | 📅 2026-09-04** - A file management tool for Android that specializes in maintenance. Its core purpose is freeing up space and removing unwanted data. `FOSS` | [🌱](https://f-droid.org/en/packages/eu.darken.sdmse/) | [▶️](https://play.google.com/store/apps/details?id=eu.darken.sdmse)
* **[Cleaner Royall](https://github.com/araafroyall/Cleaner-Royall) ⭐ 241 | 🐛 0 | 🌐 Shell | 📅 2026-09-04** - A lightweight but ultra-fast and powerful cleaner for Android. `Proprietary` `[LSP]`
* **[AutoPurge Pro](https://github.com/S123123sd/SmartClear) ⭐ 59 | 🐛 0 | 🌐 Shell | 📅 2025-03-01** - Junk cleaning automation tool that provides deep cleaning and resource management capabilities for Android devices. `FOSS` `[M]` `[K]`
* **[CZero](https://github.com/Xocio/CZero) ⭐ 50 | 🐛 1 | 📅 2026-09-01** - Cleans the cache of frequently used apps, and adds background suppression, empty-folder cleanup, and F2FS garbage collection. `FOSS` `[M]` `[K]`
* **[ClearBox](https://github.com/FLYCOM-E/ClearBox) ⭐ 38 | 🐛 1 | 🌐 C | 📅 2026-09-03** - Can delete all software caches, installation packages, compressed packages, garbage, empty folders etc. `Proprietary` `[M]` `[K]`
* **[Basic Cleaner](https://github.com/WeirdMidas/BasicCleaner) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2025-09-17** - A magisk/KSU module that applies a set of cleanups and fixups every 7-15-30 days. `FOSS` `[M]` `[K]`
* **[Cache Cleaner Widget](https://gitlab.com/Zinaro/CacheCleanerWidget)** - A root-based widget with no UI that clears all app caches in one tap. `FOSS` | [🌱](https://f-droid.org/packages/com.zinaro.cachecleanerwidget/)

### File & Partition Tools

* **[Partition Backup](https://github.com/rhythmcache/partition-backup) ⭐ 77 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-23** - This Utility Allows You To Save Android Device Partition. `FOSS` `[M]`
* **[USB Mass Storage](https://github.com/Enginex0/UsbMassStorage) ⭐ 74 | 🐛 2 | 🌐 Kotlin | 📅 2026-04-02** - Turn Your Phone into a USB Drive.
* **[SD Flasher](https://github.com/theblazehen/sd_flasher) ⭐ 8 | 🐛 0 | 🌐 Kotlin | 📅 2025-12-28** - Flash disk images (.img, .img.gz, .img.xz, .zip) directly to SD cards from your Android device. `FOSS`

[↑ Back to top](#table-of-contents)

***

## UI & Customization

> \[!TIP]
> Must check [ROM & OEM customization](#system-ui-framework) section for more theming and customization options.

### Themes & Visual Mods

* **[Iconify](https://github.com/Mahmud0808/Iconify) ⭐ 3,156 | 🐛 99 | 🌐 Kotlin | 📅 2026-08-30** - Customize your Android 12+ device easily. `FOSS` `[M]`
* **[ColorBlendr](https://github.com/Mahmud0808/ColorBlendr) ⭐ 2,430 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-03** - Customize Material You colors of your device. `FOSS` | [🌱](https://f-droid.org/en/packages/com.drdisagree.colorblendr/)
* **[HyperLight](https://github.com/KiminonawaResa/HyperLight#english) ⭐ 722 | 🐛 45 | 📅 2026-08-25** - Completes the highlight blur effects for HyperOS 3, bringing a unified visual experience to the desktop, notification shade, and control center. `FOSS` `[LSP]`
* **[Global Icon Pack](https://github.com/RichardLuo0/global-icon-pack-android) ⭐ 410 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-25** - Apply icon packs globally. `FOSS` `[LSP]`
* **[HyperOS Theme Manager](https://github.com/Mods-Center/HyperOS-Theme-Manager) ⭐ 190 | 🐛 13 | 📅 2026-08-10** - Multi-theme servers, premium themes, AI wallpapers, third-party imports, super icons/widgets etc. `Proprietary` `[M]` `[K]`
* **[Monetify](https://github.com/KaeruShi/Monetify) ⭐ 38 | 🐛 1 | 🌐 Kotlin | 📅 2026-06-22** - Customize third-party apps seamlessly to match your device style. `FOSS` `[LSP]`
* **[Lite Blur Control Center For HyperOS2](https://github.com/fakerieh/Lite-Blur-Control-Center-For-HyperOS2) ⭐ 19 | 🐛 1 | 🌐 Shell | 📅 2026-05-16** - Control Center Blur for HyperOS2 but LIGHTER. `FOSS` `[M]`
* **[Project Themer](https://play.google.com/store/apps/details?id=com.drsants.eggproject)** - Provides tools and features for rooted devices. `Proprietary` `[M]`

### Launchers & Home Screen

* **[Activity Manager](https://github.com/sdex/ActivityManager) ⭐ 1,306 | 🐛 16 | 🌐 Kotlin | 📅 2026-07-25** - Discover the activities of installed applications, run them, and create shortcuts. `FOSS` | [🌱](https://f-droid.org/packages/com.activitymanager/)
* **[Pixel Launcher Mods](https://github.com/KieronQuinn/PixelLauncherMods/) ⭐ 1,303 | 🐛 7 | 🌐 Kotlin | 📅 2025-10-30** - Mods for enhancing the Pixel Launcher experience. `FOSS`
* **[Google Shortcuts Launcher](https://github.com/WSTxda/Google-Shortcuts-Launcher) ⭐ 701 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-30** - Easily access essential Google apps features directly from your launcher app drawer. `FOSS`
* **[⭐ Lawnchair](https://github.com/Goooler/LawnchairRelease/) ⭐ 557 | 🐛 1 | 🌐 Java | 📅 2026-08-24** - A customizable launcher offering a Pixel-like experience. `FOSS`
* **[Pixel Launcher Enhanced](https://github.com/Mahmud0808/PixelLauncherEnhanced) ⭐ 521 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-02** - Unlock a variety of exciting features including customizing the look to adding more functionality and many more. `FOSS` `[LSP]`
* **[HyperOS Launcher](https://github.com/Mods-Center/HyperOS-Launcher#hyperos-launcher-v5) ⭐ 393 | 🐛 63 | 📅 2026-09-01** - Enhanced HyperOS Launcher with features from high-end devices, including customizable app drawer, icon packs, and more. `Proprietary` `[M]` `[K]`
* **[HyperOS App Vault](https://github.com/Mods-Center/HyperOS-App-Vault) ⭐ 60 | 🐛 5 | 📅 2026-08-10** - Enhanced HyperOS App Vault with unlocked widgets, high-end device features, blur adjustments, and scrolling animations. `Proprietary` `[M]` `[K]`
* **[NovaInstaller](https://github.com/Minionguyjpro/NovaInstaller/) ⭐ 57 | 🐛 2 | 🌐 Shell | 📅 2025-03-31** - Installs Nova Launcher to /system/app/ on Android. `FOSS`
* **[OnePlusPlusLauncher](https://github.com/wizpizz/OnePlusPlusLauncher) ⭐ 54 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-15** - An XPosed module for the System Launcher on OnePlus' OxygenOS 15, providing extra useful features. `FOSS` `[LSP]`
* **[Launcher3 QuickLaunch](https://github.com/hddq/launcher3-quicklaunch) ⭐ 2 | 🐛 4 | 🌐 Java | 📅 2026-09-02** - Lets you press Enter in Launcher3's app drawer search to instantly launch the first search result. `FOSS` `[LSP]`
* **[Root Activity Launcher](https://play.google.com/store/apps/details?id=tk.zwander.rootactivitylauncher)** - Launch activities directly from your home screen with root access. `Proprietary`

### Status Bar & Navigation

* **[NavTweaks](https://github.com/Magisk-Modules-Alt-Repo/HideNavBar) ⭐ 803 | 🐛 28 | 🌐 JavaScript | 📅 2026-06-23** - Fullscreen/Immersive Gesture Tweaks for Android 10-14. `FOSS` `[M]`
* **[Lyricon](https://github.com/tomakino/lyricon) ⭐ 743 | 🐛 38 | 🌐 Kotlin | 📅 2026-08-30** - An Android status bar lyric enhancement tool based on the Xposed framework. `FOSS` `[LSP]`
* **[LyricProvider](https://github.com/tomakino/LyricProvider/tree/master) ⭐ 375 | 🐛 45 | 🌐 Kotlin | 📅 2026-08-26** - A lyric provider for Lyricon. `FOSS` `[LSP]`
* **[MiNavBarImmerse](https://github.com/Ianzb/MiNavBarImmerse) ⭐ 197 | 🐛 0 | 🌐 Python | 📅 2026-08-26** - Optimizes the Xiaomi NavBar immersion by replacing the NavBar configuration file of third-party applications built into Xiaomi HyperOS 2.2. `FOSS` `[LSP]`
* **[QS Boundless Tiles](https://github.com/hxreborn/qs-boundless-tiles) ⭐ 33 | 🐛 7 | 🌐 Kotlin | 📅 2026-09-01** - Keeps third-party Quick Settings tiles responsive on Android 13+. `FOSS` `[LSP]`
* **[Hide Navbar Keyboard](https://github.com/UNKNUW/Hide-Navbar-Keyboard) ⭐ 12 | 🐛 0 | 📅 2025-04-26** - Hide navbar when keyboard appears. Supports Android 10 -15+. `FOSS` `[M]`

### Gestures & Controls

* **[Volume Key Track Control Module](https://github.com/Hepolise/VolumeKeyTrackControlModule) ⭐ 85 | 🐛 1 | 🌐 Kotlin | 📅 2026-09-01** - Allows to skip and play/pause track with volume keys. `FOSS` `[LSP]`
* **[Hide App from Recent](https://github.com/Young-Lord/hideRecent) ⭐ 81 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-07** - Hide any app from recent task list. `FOSS` `[LSP]`
* **[Recents](https://github.com/tymwitko/Recents) ⭐ 68 | 🐛 2 | 🌐 Kotlin | 📅 2026-09-03** - Launcher-agnostic "Recents" menu for Android. `FOSS` `[LSP]`
* **[Three-Finger-Screenshot](https://github.com/hxreborn/three-finger-swipe) ⭐ 40 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-28**- Standalone LSPosed implementation of three-finger swipe. `FOSS` `[LSP]`
* **[OPPO/OnePlus side button enhancement](https://github.com/ItosEO/OplusKey) ⭐ 39 | 🐛 2 | 🌐 C++ | 📅 2025-11-02** - Customize the side button behavior on Oppo and OnePlus devices. `Proprietary` `[M]`
* **[Ogesture](https://github.com/tanujnotes/ogesture) ⭐ 25 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-20** - Use gesture navigation with third-party launchers on any Android phone. `FOSS` `[LSP]`
* **[Multi Finger Gesture X](https://github.com/EliLei/MultiFingerGestureX) ⭐ 11 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-08** - An LSPosed/Xposed module that adds 3+ finger gesture support to Android 15+. `FOSS` `[LSP]`
* **[Volume Scroll](https://github.com/farfromrefug/VolumeScroll) ⭐ 7 | 🐛 0 | 🌐 Kotlin | 📅 2025-10-09** - Android app to scroll using volume keys. `FOSS` `[M]`

### Fonts & Emojis

* **[Magisk-iOS-Emoji](https://github.com/Keinta15/Magisk-iOS-Emoji) ⭐ 391 | 🐛 16 | 🌐 Shell | 📅 2026-06-25** - Systemlessly replaces the emoji font with iOS Emoji. `FOSS` `[M]`
* **[MakeFontsGreatAgain](https://github.com/Numbersf/MakeFontsGreatAgain) ⭐ 305 | 🐛 10 | 🌐 C | 📅 2026-09-03** - System-wide Font Overrider with Unique GMS Masking & Multi-Range Unicode Filter. `FOSS` `[M]` `[K]`
* **[Magisk Fonts](https://github.com/JingMatrix/MagiskFonts) ⭐ 76 | 🐛 0 | 🌐 Shell | 📅 2025-01-20** - Add custom fonts to Android for system-wide usage. `FOSS` `[M]`
* **[FontLoader](https://github.com/JingMatrix/FontLoader) ⭐ 69 | 🐛 0 | 🌐 C++ | 📅 2025-07-23** - Modifying fonts is a common scenario using the Magisk module. `FOSS` `[M]`
* **[Unicode Font Set](https://github.com/Losketch/UnicodeFontSet-magisk-module/blob/main/README.en.md) ⭐ 69 | 🐛 1 | 🌐 Shell | 📅 2026-09-04** - Installs a comprehensive Unicode font set and configuration files via the Magisk framework. `FOSS` `[M]`
* **[FontCraft Pro](https://github.com/RipperHybrid/FontCraft) ⭐ 49 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-13** - Stylish fonts & emojis for a personalized experience. `FOSS` `[M]` `[K]`
* **[KernelSU-iOS-Emoji](https://github.com/n4bi10p/Ios-emoji) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2026-07-13** - Systemlessly replaces emoji font with iOS Emoji. `FOSS` `[K]`
* **[EvilFont](https://github.com/dedeadend/EvilFont) ⭐ 26 | 🐛 0 | 🌐 Shell | 📅 2026-08-11** - Cange your Arabic/Persian font to Teshrin + IOS emojis. `FOSS` `[M]` `[K]`
* **[MiSans](https://github.com/adivenxnataly/MiSans) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2025-02-18** - Enhance your font devices with MiSans. `FOSS` `[M]`
* **[JetBrains Font](https://github.com/Mars-Wave/jetbrains-font-magisk-module) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2026-03-25** - Make your phone prettier with jetbrains mono and magisk. `FOSS` `[M]`
* **[OneUI Emoji Pack](https://github.com/aloozchips/OneUIEmojiPack) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2026-05-30** - Systemlessly replaces the AOSP emoji pack with the OneUI emoji pack. `FOSS` `[M]` `[K]`
* **[Magisk-Minecraft-Font](https://github.com/DethByte64/Magisk-Minecraft-Font) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-05-26** - A Magisk Module that changes your default font to the Minecraft font. `FOSS` `[M]`
* **[Emoji Replacer](https://play.google.com/work/apps/details?id=com.htetz.emojireplacer)** - Swap system emojis with styles from iOS 16.4, Samsung, Google, JoyPixels, Facebook, Twemoji etc. `Proprietary`
* **[Font Manager](https://play.google.com/store/apps/details?id=com.androidacy.fontmanager)** - A great font and emoji changer by Androidacy. `Proprietary`
* **[G-Font Installer](https://xdaforums.com/t/development-magisk-module-g-font-installer.4617743/)** - Install Official Google font that is used in most Google apps like Google play and Google Pixel phones right to your phone. `Proprietary` `[M]`
* **[Nastaliq Urdu Font](https://xdaforums.com/t/module-font-nastaliq-urdu-font.4645787/)** - Nastaleeq Font Module for Urdu Users. `FOSS` `[M]`
* **[Twemoji-Remastered](https://codeberg.org/Snowy/Twemoji-Remastered)** - Systemlessly replaces your phone emojis with Twemoji (Twitter Emoji). `FOSS` `[M]`
* **[zFont 3](https://play.google.com/store/apps/details?id=com.htetznaing.zfont2\&hl=en)** - Change custom font styles on Samsung, Vivo, iQOO, LG, Huawei, Honor, OnePlus, ASUS, OPPO, Realme, Xiaomi, Tecno, and Infinix devices. `Proprietary`

### Notifications

* **[HyperIsland](https://github.com/1812z/HyperIsland/blob/main/README_EN.md) ⭐ 480 | 🐛 7 | 🌐 Kotlin | 📅 2026-09-04** - Dynamic Island-style notifications for HyperOS 3, powered by LSPosed. `FOSS` `[LSP]`
* **[Punch-hole Download Progress](https://github.com/hxreborn/punch-hole-download-progress) ⭐ 235 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-29** - Displays download progress as an animated ring around the camera cutout. `FOSS` `[LSP]` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/eu.hxreborn.phdp)
* **[Notification Icon Fix](https://github.com/Xposed-Modules-Repo/io.github.howard20181.notificationiconfix/) ⭐ 80 | 🐛 10 | 📅 2026-03-22** - A module for AOSP, MIUI and HyperOS. Using an algorithm to convert white notification icons into recognizable icons. `FOSS` `[LSP]`
* **[Auto Expand Notifications](https://github.com/kvmy666/-AutoExpandNotifications) ⭐ 34 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-18** - Notification Tweaks for OxygenOS. `FOSS` `[LSP]`
* **[Notification Code](https://gitlab.com/n00byara/NotificationCode)** - Automatically extracting authentication codes and other useful information from notifications. `FOSS` `[LSP]`

### Lockscreen & AOD

* **[AlwaysOn](https://github.com/Domi04151309/AlwaysOn) ⭐ 231 | 🐛 23 | 🌐 Kotlin | 📅 2025-06-23** - Adds an always-on display with various customization options regarding watch face, behavior, and background. `FOSS` `[LSP]`
* **[ColorOS Live Lyrics Bridge](https://github.com/Andrea-lyz/ColorOS-Live-Lyrics-Bridge) ⭐ 163 | 🐛 7 | 🌐 Java | 📅 2026-09-01** - Bridges timed lyrics from supported players into the ColorOS/OPlus lock-screen lyric pipeline. `FOSS` `[LSP]`
* **[HyperOS AOD](https://github.com/Mods-Center/HyperOS-AOD) ⭐ 57 | 🐛 6 | 📅 2025-12-12** - Enhanced HyperOS AOD and Lock Screen Editor app with unlocked features. `Proprietary` `[M]` `[K]`
* **[HyperGlow](https://github.com/amarinne/hyperglow) ⭐ 8 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-01** - Animated lock screen and always-on display lyrics for HyperOS 3. `FOSS` `[LSP]`

### Screen & Display

* **[Adaptive Theme: Auto Dark Mode by Ambient Light](https://github.com/xLexip/Adaptive-Theme) ⭐ 219 | 🐛 5 | 🌐 Kotlin | 📅 2026-09-04** - Automatically switches between Light and Dark mode using the ambient light sensor. `FOSS` | [▶️](https://play.google.com/store/apps/details?id=dev.lexip.hecate)
* **[Anti Brightness Change](https://github.com/binarynoise/XposedModulets) ⭐ 217 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-03** - Prevents every app from changing the screen brightness. `FOSS` `[LSP]` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/com.programminghoch10.AntiBrightnessChange)
* **[Pseudo DC Dimming](https://github.com/dantmnf/PseudoDCDimming) ⭐ 106 | 🐛 13 | 🌐 Java | 📅 2026-05-27** - Enable alternative dimming mode (likely DC-like) on low brightness for some OLED displays by using software brightness gain. `FOSS` `[LSP]`
* **[DPIS](https://github.com/Kwensiu/DPIS) ⭐ 95 | 🐛 15 | 🌐 Java | 📅 2026-09-04** - LSPosed module for per-app interface scale, smallest width, and font size tuning. `FOSS` `[LSP]`
* **[DarQ Fork](https://github.com/Arora-Sir/DarQ) ⭐ 89 | 🐛 1 | 🌐 Kotlin | 📅 2026-09-04** - Provides a per-app selectable force dark option for Android 10 and above. `FOSS`
* **[Pointer Replacer](https://github.com/thesandipv/pointer_replacer) ⭐ 27 | 🐛 20 | 🌐 Kotlin | 📅 2026-09-04** - Replaces a dot appears when user touch the screen \[Require Show Touches to be enabled in Developer Options]. `FOSS` `[LSP]`
* **[PureShot](https://github.com/kazutoiris/PureShot) ⭐ 24 | 🐛 1 | 🌐 Java | 📅 2026-08-01** - Hide status bar, navigation bar, popups, PiP, toast & more. `FOSS` `[LSP]`
* **[Rotation Suggestions Closed](https://github.com/Astoritin/RotationSuggestionsClosed) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2025-12-28** - Stop showing rotation suggestion button as rotating screen. `FOSS` `[M]`

[↑ Back to top](#table-of-contents)

***

## Audio & Media

### Audio Enhancement

* **[ViPER4Android FX Redesign](https://github.com/WSTxda/ViperFX-RE-Releases) ⚠️ Archived** - Allows improving the audio quality by offering features such as equalizer settings, surround sound effects, bass boost, and more. `Proprietary` `[M]`
* **[JamesDSP](https://github.com/james34602/JamesDSPManager) ⭐ 936 | 🐛 35 | 🌐 C | 📅 2025-06-18** - Audio DSP effects built on the Android system framework layer. This repository contains a pack of high-quality DSP algorithms specialized for audio processing. `FOSS` `[M]`
* **[⭐ ViPERFX\_RE](https://github.com/likelikeslike/ViPERFX_RE) ⭐ 305 | 🐛 2 | 🌐 C | 📅 2026-08-11** - A fork of ViPER4Android FX with a redesigned UI and additional features. `FOSS` `[M]` `[K]`
* **[NLSound](https://github.com/Briclyaz/NLSound_module_QCom) ⭐ 293 | 🐛 2 | 🌐 Shell | 📅 2025-05-05** - Magisk module for improving audio and microphone quality in your Snapdragon SoC device. `FOSS` `[M]`
* **[Audio Modification Library Ryuki Mod](https://github.com/reiryuki/Audio-Modification-Library-Ryuki-Mod-Magisk-Module) ⭐ 284 | 🐛 0 | 🌐 Shell | 📅 2026-08-01** - Enables supported audio mods to share the same needed files, such as audio\_effects. `FOSS` `[M]`

### Audio Control

* **[LibrePods](https://github.com/kavishdevar/librepods) ⭐ 29,708 | 🐛 280 | 🌐 Kotlin | 📅 2026-09-01** - Unlocks Apple's exclusive premium AirPods features on non-Apple devices. `FOSS` `[LSP]` `[M]` `[K]`
* **[Audio jitter silencer](https://github.com/Magisk-Modules-Alt-Repo/audio-jitter-silencer) ⭐ 142 | 🐛 0 | 🌐 Shell | 📅 2026-06-21** - For avoiding distortion on all digital audio outputs, it disables audio jitter generators (w\.r.t. battery draining and optimizations, and wireless connectivity). `FOSS` `[M]`
* **[DisableAudioFocus](https://github.com/auag0/DisableAudioFocus) ⭐ 133 | 🐛 6 | 🌐 Kotlin | 📅 2025-11-17** - Allows you to disable audio focus, enabling you to play multiple videos and audios simultaneously. `FOSS` `[LSP]`
* **[SonyPods](https://github.com/Mercury000/SonyPods) ⭐ 26 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-04** - System-level Sony headphone control for HyperOS devices. `FOSS` `[LSP]`
* **[HuaweiPods](https://github.com/Nshpiter/HuaweiPods) ⭐ 16 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-02** - Huawei audio device integration for Xiaomi HyperOS. `FOSS` `[LSP]`

### Audio Effects

* **[Audio Misc Settings](https://github.com/Magisk-Modules-Alt-Repo/audio-misc-settings) ⭐ 341 | 🐛 0 | 🌐 Shell | 📅 2026-09-02** - For setting miscellaneous audio configuration values (media audio volume steps (100 steps), raising the resampling quality, disabling the effects framework, etc.) `FOSS` `[M]`
* **[Hi-Res Audio Enabler](https://github.com/reiryuki/Hi-Res-Audio-Enabler-Magisk-Module) ⭐ 208 | 🐛 0 | 🌐 Shell | 📅 2026-08-01** - Enables high resolution 24 or 32-bit width audio output if device is supported. `FOSS` `[M]`
* **[Hifi-maximizer-mod](https://github.com/yzyhk904/hifi-maximizer-mod) ⭐ 194 | 🐛 1 | 🌐 Shell | 📅 2026-08-31** - Maximize the digital audio fidelity by reducing jitters on audio outputs (USB DACs, Bluetooth a2dp, DLNA, etc.) `FOSS` `[M]`
* **[High Performance DAC](https://github.com/ahkehra/high_perf_dac) ⭐ 93 | 🐛 2 | 🌐 Shell | 📅 2026-01-08** - Kernel-level audio tuning module for Qualcomm devices, providing enhanced audio quality and performance. `FOSS` `[K]`
* **[Audio SampleRate Changer](https://github.com/Magisk-Modules-Alt-Repo/audio-samplerate-changer) ⭐ 90 | 🐛 0 | 🌐 Shell | 📅 2026-08-31** - A Magisk module changing audio sample rates at the system-wide mixer for the best Hi-Fi experience. `FOSS` `[M]`
* **[DSP AudioFix](https://github.com/ahmed-alnassif/DSP-AudioFix) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2026-02-28** - A simple fix for distorted audio on Xiaomi/MediaTek devices with Awinic smart amps. `FOSS` `[M]` `[K]`

[↑ Back to top](#table-of-contents)

***

## Network & Connectivity

### DNS & Network Filtering

* **[AdGuardHome for Root](https://github.com/twoone-3/AdGuardHomeForRoot/blob/main/README_en.md#adguardhome-for-root) ⭐ 1,384 | 🐛 11 | 🌐 Shell | 📅 2026-08-25** - A module to easily execute AdGuardHome on Android. `FOSS` `[M]`
* **[personalDNSfilter](https://github.com/IngoZenz/personaldnsfilter) ⭐ 929 | 🐛 65 | 🌐 Java | 📅 2026-08-05** - A DNS filter proxy that provides local filtering of ads, malware, and tracking servers, supporting secure DNS protocols like DOH and DOT for enhanced privacy. `FOSS` | [🌱](https://f-droid.org/packages/dnsfilter.android/)
* **[Pi-hole-for-Android](https://github.com/DesktopECHO/Pi-hole-for-Android) ⭐ 652 | 🐛 1 | 🌐 Shell | 📅 2025-12-26** - Pi-hole/Unbound Raspbian APK installer for Android 5.0+ devices. `FOSS`
* **[DNS Toggle](https://github.com/ELowry/DNSToggle) ⭐ 106 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-02** - A tiny Android app that allows you to easily toggle your phone's Private DNS through the Quick Settings panel. `FOSS`
* **[ForceDNS Cloudflare](https://github.com/LuferOS/forcedns_Magisk-kernelsu) ⭐ 14 | 🐛 3 | 🌐 Shell | 📅 2026-05-03** - Forces all standard DNS traffic (port 53) to use 1.1.1.1 via iptables. Overrides network DNS. `FOSS` `[M]` `[K]`

### VPN & Proxy

* **[FlClash](https://github.com/chen08209/FlClash) ⭐ 50,931 | 🐛 515 | 🌐 Dart | 📅 2026-09-04** - A multi-platform proxy client based on ClashMeta, simple and easy to use, open-source and ad-free. `FOSS`
* **[VPN Hotspot](https://github.com/Mygod/VPNHotspot) ⭐ 6,395 | 🐛 24 | 🌐 Kotlin | 📅 2026-09-04** - Share your VPN connection over hotspot or repeater. `FOSS`
* **[Box for Root](https://github.com/taamarin/box_for_magisk) ⭐ 2,508 | 🐛 85 | 🌐 Shell | 📅 2025-10-21** - Box for Root (BFR) is a Magisk, KernelSU, APatch, module that provides a suite of proxy tools, including clash, sing-box, v2ray, hysteria and xray. It allows you to configure a transparent proxy on Android devices with root access. `FOSS` `[M]` `[K]`
* **[Surfing](https://github.com/GitMetaio/Surfing) ⭐ 2,377 | 🐛 80 | 🌐 Shell | 📅 2026-09-04** - Magisk and KernelSU modules for Clash/mihomo, sing-box, v2ray, xray, hysteria services. `FOSS` `[M]` `[K]`
* **[Box4Magisk / KernelSU / APatch](https://github.com/CHIZI-0618/box4magisk) ⭐ 1,895 | 🐛 5 | 🌐 Shell | 📅 2026-04-10** - Deploy multiple proxy cores on Android devices, including clash, mihomo, sing-box, v2ray, xray, and hysteria. `FOSS` `[M]` `[K]`
* **[NetProxy-Magisk](https://github.com/Fanju6/NetProxy-Magisk) ⭐ 1,162 | 🐛 25 | 🌐 Go | 📅 2026-09-04** - Magisk proxy module based on Xray kernel, supports one-click start/stop transparent proxy. `FOSS` `[M]`
* **[VPN Hide](https://github.com/okhsunrog/vpnhide) ⭐ 538 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-26** - Hide active VPN from selected Android apps (kernel module + LSPosed + Zygisk) `FOSS` `[M]` `[K]`
* **[ZDT-D Root Module](https://github.com/GAME-OVER-op/ZDT-D) ⭐ 273 | 🐛 6 | 🌐 Kotlin | 📅 2026-09-02** - Module for traffic routing, DPI bypass, proxy chaining, DNS control, and per-app network management. `FOSS` `[M]` `[K]`
* **[zapret for Magisk](https://github.com/sevcator/zapret-magisk) ⭐ 156 | 🐛 1 | 🌐 Shell | 📅 2026-08-30** - DPI bypass on Android with additional features. `FOSS` `[M]`
* **[ZeroTier for Magisk](https://github.com/eventlOwOp/zerotier-magisk) ⭐ 144 | 🐛 7 | 🌐 HTML | 📅 2025-08-13** - Run zerotier in the background after booting with no conflicts with other Android VPN services. Use Android App to control ZeroTier. `FOSS` `[M]`
* **[SAM](https://github.com/5MayRain/SAM) ⭐ 141 | 🐛 10 | 🌐 HTML | 📅 2026-08-30** - A module combining SmartDNS, AdGuardHome, and mihomo, suitable for Magisk and KernelSU. `FOSS` `[M]` `[K]`
* **[Happwner](https://github.com/Omegaplexx/Happwner) ⭐ 110 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-21** - Exporte Happ subscriptions to other VPN clients. `FOSS` `[LSP]`
* **[NoVPNDetect Enhanced](https://github.com/BlueCat300/NoVPNDetectEnhanced/) ⭐ 89 | 🐛 1 | 🌐 Kotlin | 📅 2026-05-03** - An enhanced version of NoVPNDetect that prevents apps from detecting VPN usage by modifying system properties and network configurations. `FOSS` `[LSP]`
* **[NoVPNDetect](https://github.com/RuslanUC/NoVPNDetect) ⭐ 82 | 🐛 2 | 🌐 Kotlin | 📅 2026-04-12** - Prevents some apps from detecting your phone is connected to a VPN. `FOSS` `[LSP]`
* **[Aurora](https://github.com/Tkocean/Aurora) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2026-07-01** - This project deploys sing-box, mihome proxies via Magisk, KernelSU, or APatch. `FOSS` `[M]` `[K]`

### Network Tools

* **[MagicNet](https://github.com/LIghtJUNction/MagicNet#english-summary) ⭐ 162 | 🐛 2 | 🌐 Shell | 📅 2026-09-04** - Module for device-side traffic governance that enforce network rules below the app layer instead of relying on every app to respect a proxy setting. `FOSS` `[M]` `[K]`
* **[TCP Optimiser Module](https://github.com/fatalcoder524/TCP_Optimiser_Module) ⭐ 150 | 🐛 4 | 🌐 JavaScript | 📅 2026-07-01** - Change tcp congestion algorithm based on current active internet type and some network enhancements. `FOSS` `[M]` `[K]`
* **[SimbaDroid](https://github.com/buttercookie42/SimbaDroid) ⭐ 108 | 🐛 9 | 🌐 Java | 📅 2025-10-21** - A simple SMB file server for Android. `FOSS` | [🌱](https://f-droid.org/packages/de.buttercookie.simbadroid)
* **[Magisk LAN Auto Switch](https://github.com/NewFuture/magisk-modules/tree/main/magisk-lan-auto-switch) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2025-05-22** - Automatically switch LAN and WiFi based on eth0 connection status. `FOSS` `[M]`
* **[Hosts Manager Lite](https://play.google.com/store/apps/details?id=awais.hostsmanager.lite)** - Advanced /etc/hosts editor. `Proprietary`
* **[Network Utilities](https://play.google.com/store/apps/details?id=com.myprog.netutils)** - Application contains a set of tools for networks diagnostics. `Proprietary`

### Wi-Fi & Mobile Data

* **[Network Switch](https://github.com/aunchagaonkar/NetworkSwitch#installation) ⭐ 459 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-20** - Modern Android app for 4G/5G network mode switching. `FOSS` | [🌱](https://apt.izzysoft.de/packages/com.supernova.networkswitch)
* **[WiFi Password Manager](https://github.com/Khh-vu/wifi-password-manager) ⭐ 294 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-29** - Simple app to manage WiFi passwords. `FOSS` | [🌱](https://apt.izzysoft.de/packages/io.github.wifi_password_manager)
* **[VirtualAP](https://github.com/ravindu644/VirtualAP) ⭐ 76 | 🐛 2 | 🌐 Kotlin | 📅 2026-07-16** - Turn a rooted Android phone into Wi-Fi access point with static gateway, selectable upstream (mobile data, Wi-Fi, Ethernet, or a VPN tunnel) etc. `FOSS` `[LSP]`
* **[WiFi Password Viewer for MMRL](https://github.com/Googlers-Repo/wpd) ⭐ 40 | 🐛 2 | 🌐 Kotlin | 📅 2025-09-09** - WiFi Password Viewer for MMRL. `FOSS`
* **[Hyper 5G Switch](https://github.com/buffcow/Hyper5GSwitch) ⭐ 35 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-27** - Add a 5G switch to the mobile network panel, only for devices that support 5G net and equipped with HyperOS. `FOSS` `[LSP]`
* **[Wi‑Fi Passwords Exporter](https://github.com/mlm-games/wifi-exporter) ⭐ 33 | 🐛 2 | 🌐 Rust | 📅 2026-08-31** - Android app that exports wifi passwords. `FOSS`
* **[Nothing EUICC Force Enabler](https://github.com/reindex-ot/nothing-euicc#note-english) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2026-02-14** - Forcibly enables eSIM on Nothing devices that do not officially support it. `FOSS` `[M]`

### Bluetooth & NFC

* **[NFCGate](https://github.com/nfcgate/nfcgate) ⭐ 2,353 | 🐛 12 | 🌐 Java | 📅 2026-07-20** - Android application meant to capture, analyze, or modify NFC traffic. `FOSS` `[LSP]` | [🌱](https://f-droid.org/packages/de.tu_darmstadt.seemoo.nfcgate/)
* **[onHit](https://github.com/0penPublic/onHit) ⭐ 83 | 🐛 4 | 🌐 Kotlin | 📅 2026-09-04** - Trigger Android NFC events without a physical tag by Xposed. `FOSS` `[LSP]`
* **[KonamikU](https://github.com/C-F0x/KonamikU) ⭐ 37 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-24** - Extend NFC Capabilities of your device. `FOSS` `[LSP]`
* **[NFC Card Emulator Pro (Root)](https://play.google.com/store/apps/details?id=com.yuanwofei.cardemulator.pro)** - NFC card emulator for access cards, elevator cards, meal cards, school cards, library cards, and other IC cards. `Proprietary`

### Location & GPS

* **[XposedFakeLocation](https://github.com/noobexon1/XposedFakeLocation) ⭐ 671 | 🐛 9 | 🌐 Kotlin | 📅 2026-08-02** - Allows you to spoof your device's location globally or for specific apps without using "mock location" from the developer options. `FOSS` `[LSP]`
* **[Hide Mock Location](https://github.com/auag0/HideMockLocation) ⭐ 364 | 🐛 13 | 🌐 Kotlin | 📅 2026-05-12** - Hide Mock Location Settings. `FOSS` `[LSP]`
* **[GPS Setter](https://github.com/jqssun/android-gps-setter) ⭐ 281 | 🐛 0 | 🌐 Kotlin | 📅 2025-03-05** - Allows to mock locations for any specific app or entire system. `FOSS` `[LSP]` | [🌱](https://f-droid.org/packages/io.github.jqssun.gpssetter)
* **[Location Joystick](https://github.com/fzer0x/LocationJoystick) ⭐ 161 | 🐛 1 | 📅 2026-05-30** - Realtime Location Spoofer by using a Overlay Joystick to control the mock location. `Proprietary` `[LSP]`
* **[HLocation](https://github.com/sparr-sherrya/hlocation-release) ⭐ 59 | 🐛 4 | 🌐 Kotlin | 📅 2026-09-02** - Location spoofing framework that synchronizes fake GPS and related environment signals across system and app processes for more consistent location virtualization. `FOSS` `[LSP]`
* **[Location Indicator Whitelist](https://github.com/gilbsgilbs/LocationIndicatorWhitelist) ⭐ 53 | 🐛 9 | 🌐 Kotlin | 📅 2026-09-03** - Prevents applications from spamming the annoying location notification dot on Android 12 +. `FOSS` `[LSP]`
* **[AnyWhere](https://github.com/cxOrz/AnyWhere) ⭐ 22 | 🐛 0 | 🌐 Java | 📅 2026-09-02** - Location simulation tool for debugging LBS applications and for users to test geolocation functionality. `FOSS` `[LSP]`
* **[LocationMax](https://github.com/Xposed-Modules-Repo/com.huaMax) ⭐ 13 | 🐛 0 | 📅 2026-07-30** - Location simulation module for rooted Android devices using LSPosed/Xposed. `Proprietary` `[LSP]`

> \[!TIP]
> For ad blocking at network level, combine these tools with our [ad blockers](#ad-tracker-blocking). See the [ad blocking guide](./docs/general-guides/android-adblocking.md).

[↑ Back to top](#table-of-contents)

***

## Gaming

> \[!TIP]
> For overall device performance tuning, see [Performance and Optimization](#performance-optimization). For CPU/GPU management, see [Kernel Management](#kernel-management).

### Gaming Optimization

* **[AsoulOpt](https://github.com/nakixii/Magisk_AsoulOpt) ⭐ 2,688 | 🐛 0 | 🌐 Shell | 📅 2026-08-09** - Game threads tweaker for Android, suitable for mainstream games and some niche games. `FOSS` `[M]`
* **[Uperf-Game-Turbo](https://github.com/yinwanxi/Uperf-Game-Turbo) ⭐ 1,533 | 🐛 0 | 🌐 Shell | 📅 2026-07-31** - Userspace performance controller for Android. `FOSS` `[M]`
* **[Encore Tweaks](https://github.com/Rem01Gaming/encore) ⭐ 508 | 🐛 4 | 🌐 C++ | 📅 2026-08-16** - Enhance device performance during gaming sessions, while keeping battery life optimized for normal use. `Proprietary` `[M]`
* **[MIUIPerfSaver](https://github.com/rdtoy/MIUIPerfSaver) ⭐ 211 | 🐛 0 | 🌐 Kotlin | 📅 2025-08-30** - Remove MIUI's performance limit, run app at maximum FPS. `FOSS` `[LSP]`
* **[FPS Limitations Patcher](https://github.com/Mods-Center/FPS-Limitation-Patcher) ⭐ 38 | 🐛 3 | 📅 2025-11-16** - Removes FPS limitations in system apps and games on HyperOS. `Proprietary` `[M]` `[K]`
* **[FPS Unlocker](https://github.com/yadavnikhil03/GameUnlocker#fps-unlocker) ⭐ 38 | 🐛 10 | 🌐 C++ | 📅 2026-08-03** - Enables 90 FPS options in BGMI and PUBG and other Games as well for smoother gameplay on low-end devices. `FOSS` `[M]`
* **[EnCorinVest](https://github.com/LoggingNewMemory/EnCorinVest) ⚠️ Archived** - Performance Module, Collaboration between CorinXMTKVest and Encore Tweaks. `FOSS` `[M]`
* **[GameResChange](https://github.com/Xposed-Modules-Repo/com.game.reschange) ⭐ 19 | 🐛 0 | 🌐 Kotlin | 📅 2025-06-08** - Change the resolution of any app/game on Android 13+. `Proprietary` `[LSP]`
* **[PerfGame](https://github.com/adivenxnataly/PerfGame) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-15** - Enable custom resolution and frame-rate mechanism for your games. `FOSS` `[M]`

### Game Modifications & Tools

* **[Boosteroid+](https://github.com/nitanmarcel/BoosteroidPlus) ⭐ 13 | 🐛 0 | 🌐 Kotlin | 📅 2025-03-28** - Customize advanced settings for the Boosteroid app, including frame rate, bitrate, and resolution options. `FOSS` `[LSP]`
* **[JoyCon Droid](https://joycondroid.gitbook.io/joycondroid)** - Allows you to turn your Android device into a controller for your Nintendo Switch. `FOSS`

[↑ Back to top](#table-of-contents)

***

## Developer & Power User

### Terminal & Shell

* **[⭐ Termux](https://github.com/termux/termux-app) ⭐ 60,313 | 🐛 604 | 🌐 Java | 📅 2026-08-24** - A terminal emulator application for Android OS extendible by variety of packages. `FOSS` | [🌱](https://f-droid.org/en/packages/com.termux)
* **[aShell You](https://github.com/DP-Hridayan/aShellYou) ⭐ 2,292 | 🐛 36 | 🌐 Kotlin | 📅 2026-09-04** - Android shell utility app with Material Design 3 UI, letting you run ADB, root and shell commands. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/in.hridayan.ashell)
* **[Termux-Root-Recovery-Tool](https://github.com/Ishu43642/Termux-Root-Recovery-Tool) ⭐ 263 | 🐛 5 | 🌐 Shell | 📅 2026-03-17** - Install GSi Rom , Flashing Fastboot Rom, install Twrp Recovery, Boot.img & vbmeta.img files. `FOSS`
* **[TermuxRootMods](https://github.com/rompelhd/TermuxRootMods) ⭐ 180 | 🐛 1 | 🌐 C++ | 📅 2026-05-12** - A Magisk module that enhances the Termux experience for rooted devices. `FOSS` `[M]`
* **[Android 16 Linux Terminal VM Persistence](https://github.com/DigijEth/VM_Magisk_Module) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2026-06-30** - Keeps Androids Linux terminal running in the background. `FOSS` `[M]`

### ADB & Debugging

* **[LADB](https://github.com/tytydraco/LADB) ⭐ 2,397 | 🐛 53 | 🌐 Kotlin | 📅 2026-07-26** - Local ADB shell. `FOSS` | [▶️](https://play.google.com/store/apps/details?id=com.draco.ladb)
* **[Wireless ADB Switch](https://github.com/Smooth-E/wireless-adb-switch) ⭐ 678 | 🐛 11 | 🌐 Kotlin | 📅 2026-05-26** - Quickly enable or disable Android's Wireless Debugging feature. Includes widgets and a quick settings tile for convenience. `FOSS` | [🌱](https://f-droid.org/ru/packages/com.smoothie.wirelessDebuggingSwitch)
* **[ADB Root](https://github.com/evdenis/adb_root) ⭐ 508 | 🐛 2 | 🌐 Shell | 📅 2026-06-19** - A Magisk module that runs the adbd daemon as root and skips USB authentication. `FOSS` `[M]`
* **[Magisk-WiFiADB](https://github.com/mrh929/magisk-wifiadb) ⭐ 267 | 🐛 4 | 🌐 Shell | 📅 2025-05-05** - Enable WiFi ADB automatically. `FOSS` `[M]`
* **[Debug Assistant](https://github.com/ThePedroo/DebugAssistant) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2026-02-06** - The simplest yet powerful logcat capture system as Magisk module. `FOSS` `[M]`
* **[Android-ADB-over-WiFi](https://github.com/warren-bank/Android-ADB-over-WiFi) ⭐ 24 | 🐛 2 | 🌐 Java | 📅 2026-02-04** - Toggles a rooted device's Android Debug Bridge daemon (adbd) between USB and WiFi mode. `FOSS` `[LSP]`
* **[Hotspot Wireless Debugging](https://github.com/droserasprout/io.drsr.hotspotadb) ⭐ 16 | 🐛 4 | 🌐 Kotlin | 📅 2026-07-18** - Xposed module to allow Wireless Debugging over Wi-Fi Hotspot. `FOSS` `[LSP]`
* **[Log Catcher](https://github.com/hxreborn/Log-Catcher) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15** - Captures logcat and kernel messages during startup and archives them as timestamped tarballs after unlock. `FOSS` `[M]` `[K]`

### Developer Tools

* **[Shizuku](https://github.com/RikkaApps/Shizuku) ⭐ 29,747 | 🐛 560 | 🌐 Kotlin | 📅 2025-06-18** - Use system APIs directly with ADB/root privileges. `FOSS` | [🌱](https://apt.izzysoft.de/fdroid/index/apk/moe.shizuku.privileged.api) | [▶️](https://play.google.com/store/search?q=shizuku\&c=apps)
* **[⭐ Shizuku Fork](https://github.com/thedjchi/Shizuku) ⭐ 5,525 | 🐛 70 | 🌐 Kotlin | 📅 2026-07-15** - Shizuku fork with automatic Shizuku startup, automation, and recovery features. `FOSS`
* **[Shevery](https://github.com/HmnDev-Tech/shevery) ⭐ 964 | 🐛 5 | 🌐 Kotlin | 📅 2026-09-04** - Based on shizuku with Jetpack Compose, Material 3, and compatibility enhancements. `FOSS`
* **[SELinux Permissive](https://github.com/evdenis/selinux_permissive) ⭐ 263 | 🐛 1 | 🌐 Shell | 📅 2026-03-31** - Magisk Module that switches SELinux to permissive mode. `FOSS` `[M]`
* **[Dhizuku API for Xposed](https://github.com/iamr0s/Dhizuku-API-Xposed) ⭐ 136 | 🐛 1 | 🌐 Kotlin | 📅 2026-09-02** - Force applications to support Dhizuku. `FOSS` `[LSP]`
* **[Zygisk-Loader](https://github.com/HanSoBored/Zygisk-Loader) ⭐ 107 | 🐛 0 | 🌐 C | 📅 2026-08-16** - Module for hot-swapping native libraries into Android applications without rebooting. `FOSS` `[K]`
* **[KSU Toolkit](https://github.com/backslashxx/ksu_toolkit) ⭐ 105 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-30** - Small extensions on top of KernelSU for testing and debugging purposes. `FOSS` `[K]`
* **[Py2Droid](https://github.com/Mrakorez/py2droid) ⭐ 72 | 🐛 0 | 🌐 Python | 📅 2026-08-06** - Install Python 3 on Android, including the standard library (STDLIB). `FOSS` `[M]`
* **[Bluetooth Hook](https://github.com/jingyu233/bluetoothhook#english) ⭐ 60 | 🐛 6 | 🌐 Kotlin | 📅 2025-12-22** - Inject virtual BLE devices into Android system Bluetooth scan results, facilitating Bluetooth application debugging for developers. `FOSS` `[LSP]`
* **[AndroidSpect](https://github.com/thecybersandeep/androidspect) ⭐ 31 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-23** - Live runtime audit for installed Android apps, serves a browser dashboard. `FOSS` `[LSP]`
* **[DuckPolicy](https://github.com/Xposed-Modules-Repo/com.strawing.duckdevicepolicy) ⭐ 26 | 🐛 0 | 📅 2026-07-20** - Makes apps see no device-policy restrictions on your own device. `Proprietary` `[LSP]`
* **[SideWire](https://github.com/mzggr0914/SideWire-KernelSU) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2026-09-02** - Native bridge for controlling rooted Android devices from Windows, macOS, or Linux. `FOSS` `[K]`

### Linux Environments

* **[⭐ Droidspaces](https://github.com/ravindu644/Droidspaces-OSS) ⭐ 1,851 | 🐛 1 | 🌐 Kotlin | 📅 2026-09-01** - Run full Linux environments on top of Android, with complete init system support. `FOSS`
* **[Chroot Distro](https://github.com/Magisk-Modules-Alt-Repo/chroot-distro) ⭐ 487 | 🐛 29 | 🌐 Shell | 📅 2025-12-18** - Install Gnu/Linux distributions on Android. `FOSS` `[M]`
* **[DebDroid](https://github.com/NICUP14/DebDroid) ⭐ 268 | 🐛 1 | 🌐 Shell | 📅 2026-06-06** - Debian Container Runtime for Android. `FOSS`
* **[Ubuntu Chroot](https://github.com/ravindu644/Ubuntu-Chroot) ⭐ 154 | 🐛 0 | 🌐 Python | 📅 2026-03-23** - Run Ubuntu 24.04 on Android With full Hardware Access and pure namespace isolation. `FOSS` `[M]` `[K]`
* **[Magisk Docker](https://github.com/mgksu/dockerd) ⭐ 123 | 🐛 10 | 🌐 Shell | 📅 2025-08-03** - Magisk and KernelSU module for running Docker on rooted Android devices. `FOSS` `[M]` `[K]`
* **[Boot Nethunter](https://github.com/cipherswami/boot-nethunter) ⭐ 60 | 🐛 0 | 🌐 Shell | 📅 2026-07-15** - Boots Kali-Chroot (one Installed with Nethunter apk) in Termux. `FOSS`
* **[Trixie.apk](https://github.com/DesktopECHO/trixie.apk) ⭐ 52 | 🐛 0 | 🌐 Java | 📅 2025-11-21** - Debian 13 (Trixie) Server/Desktop container for rooted Android 5.0+ devices. `FOSS`
* **[Auto-Linux](https://github.com/HanSoBored/Auto-Linux) ⭐ 24 | 🐛 1 | 🌐 Go | 📅 2026-06-15** - A TUI application to install and manage Linux (chroot) environments on rooted Android devices. `FOSS`

### Automation

* **[crond4Android](https://github.com/powerAn2020/crond4android) ⭐ 34 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-07** - Cron daemon for scheduled jobs on KernelSU, APatch, and Magisk. `FOSS` `[M]` `[K]`
* **[⭐ MacroDroid](https://play.google.com/store/search?q=macrodroid\&c=apps)** - Easy to use automation app. `Proprietary`
* **[⭐ Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)** - An advanced and powerful automation app. `Proprietary`
* **[Automate](https://play.google.com/store/apps/details?id=com.llamalab.automate)** - Lets you create custom automation workflows using flowcharts, enabling seamless management of tasks, files, and device settings. `Proprietary`

### Hardware & Sensors

* **[USB HID Client](https://github.com/Arian04/android-hid-client) ⭐ 433 | 🐛 18 | 🌐 Kotlin | 📅 2026-08-31** - Use your phone as a keyboard and mouse without any software on the other end. `FOSS` | [🌱](https://apt.izzysoft.de/packages/me.arianb.usb_hid_client)
* **[GyroHook Project](https://github.com/AFan4724/GyroHook) ⭐ 62 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-25** - Allows users to modify the gyroscope sensor data of Android devices. `FOSS` `[M]`
* **[HID Gadget Module](https://github.com/kelexine/hid-gadget-module) ⭐ 39 | 🐛 0 | 🌐 C | 📅 2026-08-05** - Enables Human Interface Device (HID) emulation/support on Android Devices. `FOSS` `[M]`
* **[OnePlus Flash Control](https://github.com/Bartixxx32/Opflashcontrol-app) ⭐ 31 | 🐛 8 | 🌐 Kotlin | 📅 2026-06-26** - Precise control over the brightness of the dual-tone and quad-tone LED flashes for OnePlus devices. `FOSS`

[↑ Back to top](#table-of-contents)

***

## General Utilities

### Sync & File Transfer

* **[Rclone Magisk Module](https://github.com/NewFuture/rclone-fuse3-magisk) ⭐ 68 | 🐛 7 | 🌐 Shell | 📅 2026-08-02** - Integrates Rclone with FUSE support into Android, allowing you to manage remote storage mounts seamlessly. `FOSS` `[M]`
* **[Rsync Magisk](https://github.com/KatelynTheStargazer/rsync-magisk) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-10-30** - Static rsync binary for Magisk-based file sync and backup workflows. `FOSS` `[M]`

### Reboot & Power

* **[RebootNya](https://github.com/daisukiKaffuChino/RebootNya) ⭐ 259 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-20** - A simple yet advanced reboot utility for Android devices. `FOSS`
* **[Advanced Power Menu](https://github.com/Xposed-Modules-Repo/com.sui.advancedpowermenu) ⭐ 11 | 🐛 0 | 📅 2026-08-27** - Provides a highly compatible extended advanced power menu. `Proprietary` `[LSP]`

### Sharing & Intent Tools

* **[⭐ CleanShare](https://github.com/hxreborn/cleanshare) ⭐ 113 | 🐛 11 | 🌐 Kotlin | 📅 2026-09-01** - Removes Direct Share's suggested contact/conversation shortcuts from Android's Share Sheet. `FOSS` `[LSP]`
* **[No Photo Picker API](https://github.com/yureitzk/NoPhotoPickerAPI) ⭐ 52 | 🐛 0 | 🌐 Kotlin | 📅 2026-02-19** - Bypasses the Android Photo Picker API and lets apps use the classic document/file picker. `FOSS` `[LSP]`
* **[ClipVault](https://github.com/kaduvert/AClipBoardManager) ⭐ 12 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-28** - Android ClipBoard Manager using LSPosed / Magisk. `FOSS` `[M]` `[K]` `[LSP]`

### Communication & Messaging

* **[Basic Call Recorder](https://github.com/chenxiaolong/BCR) ⭐ 2,895 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-20** - A Basic Call Recorder for rooted Android devices. Also check out [GUI for BCR ↗](https://github.com/nicorac/bcr-gui) ⭐ 354 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-31. `FOSS` `[M]` `[K]`
* **[XposedForwardSms](https://github.com/XiaoMiHongZhaJi/XposedForwardSms) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2025-07-28** - Forward text messages. `FOSS` `[LSP]`
* **[Contacts Sync](https://play.google.com/store/apps/details?id=com.lb.contacts_sync)** - Uses root to sync your address book with high-quality contacts photos from WhatsApp. `Proprietary`
* **[XposedSmsCode](https://gitlab.com/magisk3171/XposedSmsCode)** - Recognize SMS verification codes and copy them to the clipboard, or automatically input verification codes. `FOSS` `[LSP]`

### General Toolboxes

* **[⭐ Essentials](https://github.com/sameerasw/essentials) ⭐ 2,839 | 🐛 83 | 🌐 Kotlin | 📅 2026-09-04** - Multi-purpose tweaks for display, notifications and alerts, security and privacy, sound and haptics, and app freezing. `FOSS`
* **[UotanToolbox NT](https://github.com/Uotan-Dev/UotanToolboxNT) ⭐ 2,686 | 🐛 4 | 🌐 C# | 📅 2026-08-30** - A modern toolbox for Android power users and geeks. `FOSS`
* **[SwitchAI - Switch AI Digital Assistant](https://github.com/WSTxda/SwitchAI) ⭐ 1,426 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-30** - Easily select, start, and manage your preferred AI digital assistants. `FOSS`
* **[Zygisk Sui](https://github.com/XiaoTong6666/Sui) ⭐ 661 | 🐛 3 | 🌐 Java | 📅 2026-09-04** - Modern superuser interface (SUI) implementation for Android. `FOSS` `[M]` `[K]`
* **[APatch Utilities](https://github.com/lzghzr/APatch_kpm) ⭐ 426 | 🐛 1 | 🌐 C | 📅 2026-06-06** - Collection of utility modules for APatch. `FOSS`
* **[XposedModulets](https://github.com/binarynoise/XposedModulets) ⭐ 217 | 🐛 3 | 🌐 Kotlin | 📅 2026-09-03** - A collection of many small useful Xposed Modules. `FOSS` `[LSP]`
* **[KernelSU Grant Toast](https://github.com/NativeStar/KernelSUGrantToast) ⭐ 51 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-29** - Make KernelSU show a root granted toast like Magisk. `FOSS` `[K]`
* **[GreaseMilkyway](https://play.google.com/store/apps/details?id=net.kollnig.greasemilkyway)** - Android accessibility service designed to help people with attention-related conditions (such as ADHD) manage their digital environment and focus on what matters. `FOSS` `[LSP]`
* **[System Tools Android](https://play.google.com/store/apps/details?id=com.redhome.sta)** - A system utility suite with many small tools for finer system work, including root utilities. `Proprietary`

> \[!TIP]
> If you are looking for classic root managers and module managers, start with [Root Management](#root-module-management). If you need shell commands or Linux tooling, see [Terminal and Shell Tools](#terminal-shell).

[↑ Back to top](#table-of-contents)

***

<div align="center">
<br>

# Resources and Help

[![X (formerly Twitter) Follow](https://img.shields.io/badge/%20%20-Follow%20US-blue?logo=X\&logoColor=white\&style=for-the-badge\&label=​)](https://x.com/awsm_and_root)

</div>

### Official Channels

| Platform         | Purpose                       | Link                                                                                                                      |
| :--------------- | :---------------------------- | :------------------------------------------------------------------------------------------------------------------------ |
| 🌐 **Website**   | Browse apps, modules & guides | [awesome-android-root.zhoe.org](https://awesome-android-root.zhoe.org)                                                    |
| 📂 **GitHub**    | Source, discussions & issues  | [GitHub Repo](https://github.com/awesome-android-root/awesome-android-root) ⭐ 4,460 \| 🐛 1 \| 🌐 Python \| 📅 2026-09-04 |
| 𝕏 **X/Twitter** | Updates & news                | [@awsm\_and\_root](https://x.com/awsm_and_root)                                                                           |

### Quick Help Paths

* First time here? Start at the [Introduction](#introduction) & [The 4-Step Rooting Process](#the-4-step-rooting-roadmap)
* Unsure about a term? Open the [Glossary](#glossary)
* Want tools? Jump to [Root Apps and Modules](#root-apps-and-modules)
* Need a walkthrough? Browse the [Rooting Guides Index](./docs/rooting-guides/index.md)
* Common questions? Check the FAQs: [faqs.md](./docs/faqs.md)

### Resource Hub

> Extended references & external reading: [resources.md](./docs/resources.md)

### Contribute and Participate

* 🐛 Report [issues](https://github.com/awesome-android-root/awesome-android-root/issues) ⭐ 4,460 | 🐛 1 | 🌐 Python | 📅 2026-09-04
* ⭐ Star the repo (boosts discovery)
* 💡 Suggest new apps/modules
* 🧹 Improve formatting / dead link cleanup

> 📝 Read [contributing guide](docs/contributing.md) before major PRs

***

## Legal and Safety

> \[!IMPORTANT]
> **Educational reference only. Proceed at your own risk.**
> Rooting can void warranty, break security (Knox/Integrity), and lockout banking/DRM apps. **Avoid proceeding** if this is a mission-critical device or if you lack a verified backup.

### 🛠️ Pre-Flash Checklist

* [ ] **Backups:** Full app data and internal storage images.
* [ ] **Firmware:** Matching factory boot/vbmeta images on hand.
* [ ] **Tools:** Latest `platform-tools` (ADB/Fastboot) installed.
* [ ] **Access:** Alternate path available (Custom Recovery or 2nd device).

### 🛡️ Risk Mitigation

* **Systemless First:** Favor Magisk/KernelSU over invasive system partition mods.
* **One at a Time:** Change one variable and test before moving to the next.
* **Clean Rollback:** Keep pristine copies of original `boot` and `vbmeta` images.
* **Module Safety:** Check "Open Issues" and avoid overlapping mods (e.g., multiple ad-blockers).

<div align="center">

*Respect licenses, ToS, and local laws. Do not use root to unlawfully bypass paid features.*

<br>
</div>

[↑ Back to top](#table-of-contents)

***

<div align="center">

**⚡ Built with ❤️ by [Awesome Android Root](https://github.com/awesome-android-root/awesome-android-root) ⭐ 4,460 | 🐛 1 | 🌐 Python | 📅 2026-09-04**

</div>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
