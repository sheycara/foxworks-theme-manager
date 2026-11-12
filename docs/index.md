---
title: Vulphexis Theme Manager
---

# Vulphexis Theme Manager

Apply and restore Windows desktop themes. Choose which parts to use, including wallpaper, colors, icons, mouse pointers, and sounds.

## Download v1.0.2 for Windows x64

- **Installer.** Run Setup, then open Vulphexis Theme Manager from Start. [Download the installer](https://github.com/sheycara/foxworks-theme-manager/releases/download/V1.0.2/Vulphexis_Theme_Manager_Setup_v1.0.2.exe)
- **Portable ZIP.** Extract the entire ZIP. Keep the `_internal` folder beside `FoxWorksThemeManager.exe`, then run the executable. [Download the portable ZIP](https://github.com/sheycara/foxworks-theme-manager/releases/download/V1.0.2/Vulphexis_Theme_Manager_Windows_x64_v1.0.2.zip)

## SHA-256 checksums

- Installer: `A5A30C7C44880E91CE3BF3B878AB55F45E722A819F4144D76810B7CD581B22D7`
- Portable ZIP: `8A2735D1C0F71B158BA47ED989F266C7B8EB803C033B7FDC94A3524E3180AC63`

[Release notes](https://github.com/sheycara/foxworks-theme-manager/releases/tag/V1.0.2) · [Previous release under the FoxWorks name](https://github.com/sheycara/foxworks-theme-manager/releases/tag/v1.0.1)

## Third-party licenses and source

The application includes Qt, PySide6, and Shiboken under the GNU LGPL v3. Both downloads include license texts and third-party notices in the `licenses` folder, including the Mesa llvmpipe and LLVM notices for Qt's software OpenGL fallback. [Qt 6.12.0 source](https://download.qt.io/archive/qt/6.12/6.12.0/) · [PySide6 and Shiboken 6.12.0 source](https://download.qt.io/official_releases/QtForPython/pyside6/PySide6-6.12.0-src/)

To use compatible replacement libraries, close Vulphexis Theme Manager and work in a writable copy of the extracted portable folder. Back up `_internal/PySide6` and replace the relevant Windows x64 DLLs and plugins at their existing paths. Keep interdependent DLLs and PySide bindings compatible. Reopen `FoxWorksThemeManager.exe` and restore the backed-up files if the app fails to open.
