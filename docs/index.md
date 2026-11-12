---
title: Vulphexis Theme Manager
---

# Vulphexis Theme Manager

Apply and restore Windows desktop themes. Choose which parts to use, including wallpaper, colors, icons, mouse pointers, and sounds.

## Download v1.0.1 for Windows x64

Version 1.0.1 was released under the FoxWorks Theme Manager name.

- **Installer.** Run Setup, then open FoxWorks Theme Manager from Start. [Download the installer](https://github.com/sheycara/foxworks-theme-manager/releases/download/v1.0.1/FoxWorks_Theme_Manager_Setup_v1.0.1.exe)
- **Portable ZIP.** Extract the entire ZIP. Keep the `_internal` folder beside `FoxWorksThemeManager.exe`, then run the executable. [Download the portable ZIP](https://github.com/sheycara/foxworks-theme-manager/releases/download/v1.0.1/FoxWorks_Theme_Manager_Windows_x64_v1.0.1.zip)

## SHA-256 checksums

- Installer: `1F996AC7E0767CEE83DCF8FB98767F863F79E347D68B49B86FA644F45CC5ADFE`
- Portable ZIP: `747338D601CB577D3276954F3302F61AF6CFB12516E538D87330796F97C9E4E8`

## Third-party licenses and source

The application includes Qt, PySide6, and Shiboken under the GNU LGPL v3. Both downloads include license texts and third-party notices in the `licenses` folder, including the Mesa llvmpipe and LLVM notices for Qt's software OpenGL fallback. [Qt 6.12.0 source](https://download.qt.io/archive/qt/6.12/6.12.0/) � [PySide6 and Shiboken 6.12.0 source](https://download.qt.io/official_releases/QtForPython/pyside6/PySide6-6.12.0-src/)

To use compatible replacement libraries, close FoxWorks and work in a writable copy of the extracted portable folder. Back up `_internal/PySide6` and replace the relevant Windows x64 DLLs and plugins at their existing paths. Keep interdependent DLLs and PySide bindings compatible. Reopen `FoxWorksThemeManager.exe` and restore the backed-up files if the app fails to open.
