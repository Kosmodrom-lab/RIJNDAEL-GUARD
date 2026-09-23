# RIJNDAEL GUARD v2.56 (32-BIT)

![Platform](https://img.shields.io/badge/Platform-Windows%207%20%7C%208%20%7C%2010%20%7C%2011-blue)
![Language](https://img.shields.io/badge/Language-IWBasic%202.5-orange)
![License](https://img.shields.io/badge/License-Freeware-green)
![Status](https://img.shields.io/badge/Status-Single--File%20Portable-brightgreen)

> Compact, high-performance security tool providing hardware-accelerated 256-Bit CFB Rijndael encryption, integrated ZLIB stream compression, and SSD-friendly Win32 block streaming file shredding in a fully self-contained single executable.

---

## 📋 Overview

| Attribute | Details |
| :--- | :--- |
| **Version** | v2.56 (32-Bit) |
| **Release Date** | September 2026 |
| **Language** | Native IWBasic 2.5 |
| **Platform** | Windows 7 / 8 / 10 / 11 (x86/x64) |
| **Category** | Security / File Encryption & Shredding Utility |
| **Author** | Yannick Dalissier |
| **Status** | Freeware / Single-File Portable Executable |

---

## ✨ Key Features

* **Cipher Engine:** True 256-Bit CFB Rijndael encryption with **AES-NI hardware acceleration** detection.
* **Key Derivation:** 1000-Iteration PBKDF2-style key stretching with static salt and dual-offset header marker verification (`RGUARD256`).
* **Compression:** Real-time ZLIB stream compression/expansion via chunked streaming (`zlib.dll` integration).
* **Secure Shredder:** High-speed 1 MB Win32 block streaming sanitization (zero-fill) with explicit file truncation.
* **Memory Security:** Hardened RAM protection with explicit zero-fill buffer clearing via `WipeBuffer`.
* **Resource Architecture:** 100% clean single-file script architecture — binary PNG assets embedded via native `DATA` byte statements and decoded through GDI+ memory streams (`IStream`).
* **UI & Navigation:** 
  * Dual-buffered Win32 GDI/GDI+ skinned canvas with smooth sliding 3-panel stage viewport (`[About] <-> [Main] <-> [Help]`).
  * Overflow-safe real-time progress bar with integrated status marquee text.
  * Custom inline HTML parser for documentation rendering and vertical credit scrolling.
* **Configuration:** Native INI parser (`R256.ini`) for automatic persistence of window positioning, session options, and user preferences.
* **Accelerators:** Full keyboard shortcuts (`Ctrl+A`, `Ctrl+H`, `Ctrl+M`, `Ctrl+B`, `Ctrl+P`, `Ctrl+R`, `ESC`).

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `ESC` | Instantly slide back to Main Control Panel |
| `Ctrl+A` | Switch Viewport to About Screen |
| `Ctrl+H` | Switch Viewport to Help Screen |
| `Ctrl+B` | Open File Browse Dialog |
| `Ctrl+P` | Execute Protect File |
| `Ctrl+R` | Execute Restore File |
| `Ctrl+M` | Open Mail Client (Subject: R256) |
| `PageUp` / `PageDown` | Fast vertical viewport scrolling |
| `Up` / `Down` Arrows | Fine incremental line scrolling |

---

> **100% Single-File Portable — No Installation Required — Zero Storage Footprint**
