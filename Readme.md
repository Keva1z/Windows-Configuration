# Windows configuration

My personal Windows setup guide.

This repository contains everything I install and configure on a fresh Windows installation. Download the ZIP archive and follow this README from top to bottom.

> [Download ZIP](https://github.com/Keva1z/Windows-Configuration/archive/refs/heads/main.zip)

### Windows & Customization

- [Atlas OS](https://atlasos.net/)
- [Wallpaper](Windows/wallpaper.jpg)
    - Put it in **Windows Images folder**
    - More wallpapers in good quality. [Link](https://github.com/dharmx/walls)
- [Fonts](Windows/Fonts)
- [Cursor](Windows/Cursor/Cursor%20Dark/)

**Atlas** is windows patcher & ISO creation tool. It helps reduce background processes, telemetry, preinstalled apps and other unwanted Windows components.

### DRIVERS

Make sure to install all necessary drivers from your hardware manufacturer's website.

If you need a Wi-Fi driver, download it to a USB drive before reinstalling Windows. Atlas may preserve existing drivers, allowing you to connect to Wi-Fi after installation.

### DNS

Right-click Network settings → Ethernet → DNS settings

- **IPv4:** 8.8.8.8 **/** 8.8.4.4
- **IPv6:** 2001:4860:4860::8888 **/** 2001:4860:4860::8844

**(IPv4 & IPv6) DNS over HTTPS:** On

---

## Apps


### Bypasses & VPN

- [Zapret](https://github.com/Flowseal/zapret-discord-youtube) by Flowseal
    - Update the Windows **hosts** file.
    - Copy [list-general-user](Zapret/list-general-user.txt) into the `lists` directory.
    - Run diagnostics for all strategies and choose the one that works best for your network.
- [TG-WS](https://github.com/Flowseal/tg-ws-proxy) by Flowseal
    - In configuration turn on **Run on PC startup**
    - After installing **Telegram** double click on icon in tray
- [Happ](https://github.com/Happ-proxy/happ-desktop/releases/latest/download/setup-Happ.x64.exe)
    - Enable **fragmentation**

---

#### Windhawk

- [Windhawk](https://ramensoftware.com/downloads/windhawk_setup.exe)

Install the following mods in Windhawk:

- Windows 11 Start Menu Styler.
    - **Theme:** TransculentStartMenu
    - **Layout:** New layout + Side by Side
- Windows 11 Taskbar Styler
    - **Theme:** TransculentTaskbar

---

#### Telegram

- [Telegram](https://github.com/telegramdesktop/tdesktop)
/
[AyuGram](https://github.com/AyuGram/AyuGramDesktop)
/
[LuxuryGram](https://github.com/GofMan5/LuxuryGram)
    - [Settings](Telegram/Settings.md) for AyuGram & LuxuryGram

**LuxuryGram** is an enhanced version of **AyuGram**, featuring additional optimizations and improvements. Developed by [GofMan5](https://github.com/GofMan5).

---

#### Discord 

- [Discord](https://discord.com/api/downloads/distributions/app/installers/latest?channel=stable&platform=win&arch=x64) & 
[Vencord](https://github.com/Vencord/Installer/releases/latest/download/VencordInstaller.exe)
- [Settings](vencord/settings.json) & [theme](vencord/midnight-vencord.theme.css)

---

#### Steam

- [Steam](https://store.steampowered.com/about/)

---

#### Roblox

- [Bloxstrap](https://github.com/bloxstraplabs/bloxstrap)

---

#### Minecraft

- [Prism Launcher](https://prismlauncher.org/download/windows/)
- [Radmin VPN](https://www.radmin-vpn.com/ru/)

---

#### Autoclicker

- [Blur Autoclicker](https://github.com/Blur009/Blur-AutoClicker) by Blur009

---

#### NVIDIA App

- [NVIDIA App](https://www.nvidia.com/en-us/software/nvidia-app/)

---

## Programming

- [Git](https://git-scm.com/install/windows)
- [VSCode](https://code.visualstudio.com/)
- [uv](https://github.com/astral-sh/uv)
- [Docker](https://docs.docker.com/desktop/setup/install/windows-install/)


## Other

- [Windows Terminal Config](Windows/Terminal/settings.json)
    - **Warning:** Install it if you have git bash installed as Terminal profile.

## Post-Install

- Disable unnecessary startup applications.
- Configure display refresh rate.
- Configure your browser to your liking.
- Sign in to all your accounts.
- Clean up the Downloads folder.
- Create a system restore point.
