<div align="center">

# 🎮 Spoof GT 50 Pro

**Turn your rooted Android device into an Infinix GT 50 Pro — unlock FPS up to 144.**

![Version](https://img.shields.io/badge/version-v1.0.0-blue?style=for-the-badge)
![Author](https://img.shields.io/badge/author-Sabbir%20Senpai-purple?style=for-the-badge)
![Credit](https://img.shields.io/badge/credit-ShelbyProject-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Magisk%20%7C%20KernelSU%20%7C%20APatch-red?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

</div>

---

## ✨ Features

- 🎭 **Full Device Spoof** → Infinix GT 50 Pro (X6891)
- 🔓 **FPS Unlock** up to **144Hz**
- 🧹 **Auto Cache Cleanup** on install
- 🎨 **Beautiful Flashing UI** (styled terminal output)
- ⚡ **Lightweight** — zero bloat, zero background service
- 🛡️ **Safe & Reversible** — disable module & reboot to restore
- 🔧 Compatible with **Magisk / KernelSU / APatch**

---

## 📱 Target Spoof Profile

| Property | Value |
|----------|-------|
| Brand | `INFINIX` |
| Manufacturer | `INFINIX` |
| Model | `Infinix X6891` |
| Device | `Infinix-X6891` |
| Codename | `X6891-OP` |
| FPS Unlock | up to `144Hz` |
| Anti-Crack Support | `Yes` |

---

## 🚀 Installation

### Requirements
- Rooted device with **Magisk v20.4+**, **KernelSU**, or **APatch**
- Android 8.0 or higher

### Steps
1. Download the latest `.zip` from [**Releases**](../../releases/latest)
2. Open **Magisk / KernelSU / APatch** app
3. Navigate to **Modules → Install from storage**
4. Select the downloaded zip file
5. Wait until the flashing UI completes
6. **Reboot** your device

---

## ✅ Verify Installation

After reboot, open **Termux** or **ADB shell** and run:

```sh
getprop ro.product.model
getprop ro.product.brand
getprop ro.product.device
```

Expected output:

```
INFINIX X6891
INFINIX GT 50 Pro
```

---

## 🖥️ Flashing Preview

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
    ██████╗ ███████╗██╗   ██╗███████╗██████╗
    ██╔══██╗██╔════╝██║   ██║██╔════╝██╔══██╗
    ██║  ██║█████╗  ██║   ██║███████╗██████╔╝
    ██║  ██║██╔══╝  ╚██╗ ██╔╝╚════██║██╔═══╝
    ██████╔╝███████╗ ╚████╔╝ ███████║██║
    ╚═════╝ ╚══════╝  ╚═══╝  ╚══════╝╚═╝

        >>  SPOOF GT 50 PRO  <<
          Unlock • Spoof • Dominate
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

 [1/3] Cleaning junk & package cache...
       ✓ /data/system/package_cache/*  cleared
────────────────────────────────────────────
 [2/3] Injecting GT 50 Pro spoofed props...
       ✓ ro.product.model         → Infinix X6891
────────────────────────────────────────────
 [3/3] Finalizing module...
       ✓ Module ready to boot
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

   ╔═════════════════════════════════╗
          ✅   INSTALL  SUCCESSFUL   ✅     
   ╚═════════════════════════════════╝

   🎨 Module by  : Sabbir Senpai
   💡 Concept by : ShelbyProject 🤟
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 🗑️ Uninstall

1. Open **Magisk / KernelSU / APatch**
2. Disable or remove **Spoof GT 50 Pro**
3. **Reboot** device

> ✅ Cache rebuilds automatically. No data loss. All spoofed props revert to original.

---

## 📁 Module Structure

```
Spoof-GT50Pro/
├── META-INF/com/google/android/
│   ├── update-binary
│   └── updater-script
├── customize.sh
├── module.prop
├── system.prop
├── update.json
├── README.md
├── CHANGELOG.md
└── LICENSE
```

---

## 🙏 Credits

- 💡 **Original Idea & Concept** → **ShelbyProject** 🤟
- 🎨 **Module Development** → **Sabbir Senpai**

---

## ⚠️ Disclaimer

> This module is provided for **educational and personal use only**.
> The author is **not responsible** for any device damage, brick, data loss,
> or account ban caused by misuse.
> **Use at your own risk.**

---

<div align="center">

**Made with ❤️ by Sabbir Senpai**

⭐ **Star this repo if it helped you!**

</div>