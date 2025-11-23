# NiklasCFW Pack by **[Woody-NX](https://github.com/Woody-NX)**

![](http://cdn.niklascfw.de/files/nyx20250421_160911.png)

### NiklasCFW Pack ist ein vollständiges Custom Firmware Setup für Nintendo Switch mit Fokus auf Benutzerfreundlichkeit und deutsche Lokalisierung.

### [NiklasCFW Pack](https://github.com/Woody-NX/NiklasCFW_Pack/releases) unterstützt alle HOS-Versionen, einschließlich 20.5.0

## Features von NiklasCFW Pack

* **Vollständiges CFW-Setup** - Sofort einsatzbereit mit allen wichtigen Tools
* **Deutsche Lokalisierung** - Ultrahand Overlay und viele Apps auf Deutsch
* **Umfangreiche Tool-Sammlung** - 20+ vorinstallierte Homebrew-Apps
* **Vorkonfigurierte Module** - Alle wichtigen sysmodules bereits eingerichtet
* **Moderne UI** - Sphaira als Homebrew Menu mit Theme-Support
* **Sicherheitsfeatures** - DNS-MitM, sys-patch und mehr
* **Regelmäßige Updates** - Aktive Community und kontinuierliche Entwicklung
* **Modulare Struktur** - Einfaches Hinzufügen/Entfernen von Komponenten

## Inhalt von NiklasCFW Pack

### **1. Core CFW Komponenten**
1. **[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)** - Custom Firmware für Nintendo Switch
2. **[Hekate](https://github.com/CTCaer/hekate)** - Bootloader mit grafischer Oberfläche
3. **[sys-patch](https://github.com/impeeza/sys-patch)** - System-Patches für unsigned Software
4. **[UltraHand](https://github.com/ppkantorski/Ultrahand-Overlay)** - Overlay-Menü

### **2. Installierte Payloads**
* **[Lockpick RCM Pro](https://github.com/sthetix/Lockpick_RCM_Pro)** - Console Keys extrahieren
* **[TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer)** - Low-Level Dateimanager
* **[hwfly_toolbox](https://github.com/ITotalJustice/hwfly_toolbox)** - Hardware-Toolbox
* **[Instinct_toolbox](https://github.com/ITotalJustice/Instinct_toolbox)** - Instinct Modchip Toolbox
* **[PicoFly_Toolbox](https://github.com/ITotalJustice/PicoFly_toolbox)** - PicoFly Modchip Toolbox

### **3. Installierte Homebrew Apps**
* **[Sphaira](https://github.com/ITotalJustice/sphaira)** - Modernes Homebrew Menu
* **[DBI](https://github.com/rashevskyv/DBI)** - Dateimanager, Save Manager und Installer
* **[Daybreak](https://github.com/Atmosphere-NX/Atmosphere)** - HOS Update Tool
* **[JKSV](https://github.com/J-D-K/JKSV)** - Save Manager
* **[EdiZon](https://github.com/WerWolv/EdiZon)** - Cheat Engine
* **[Linkalho](https://github.com/rdmrocha/linkalho)** - Account Linking
* **[NX-Activity-Log](https://github.com/tallbl0nde/NX-Activity-Log)** - Activity Logger
* **[nxdumptool](https://github.com/DarkMatterCore/nxdumptool)** - Game Dumper
* **[NXGallery](https://github.com/joel16/NXGallery)** - Media Gallery
* **[Chiaki](https://github.com/thestr4ng3r/chiaki)** - PlayStation Remote Play
* **[SimpleModManager](https://github.com/AmazingAidan/SimpleModManager)** - Mod Manager
* **[SimpleModDownloader](https://github.com/AmazingAidan/SimpleModDownloader)** - Mod Downloader
* **[Switch_themes_Installer](https://github.com/exelix11/SwitchThemeInjector)** - Theme Installer
* **[Sys-Clk Manager](https://github.com/redraz/sys-clk-manager)** - Overclocking Manager
* **[Breeze](https://github.com/tallbl0nde/Breeze)** - Cheat Manager
* **[DNS_mitm Tester](https://github.com/ITotalJustice/DNS_mitm_Tester)** - DNS Test Tool
* **[ldnmitm_config](https://github.com/spacemeowx2/ldn_mitm)** - Local Network Config

### **4. Installierte Module**
* **[sys-clk](https://github.com/ppkantorski/sys-clk)** - CPU, Memory und GPU Overclocking
* **[nx-ovlloader](https://github.com/ppkantorski/nx-ovlloader)** - Overlay Loader
* **[Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay)** - Overlay-Menü System
  - **Status Monitor** - Real-time System Parameter Monitoring
  - **sys-clk Overlay** - Overclocking Control
  - **EdiZon Overlay** - Cheat Management
  - **sys-patch Overlay** - Patch Management
  - **Battery Charge Info** - Battery Status
  - **ldnmitm Config** - Local Network Configuration
  - **sysmodules** - Module Management

### **5. Konfiguration & Themes**
* **Deutsche Lokalisierung** - Ultrahand auf Deutsch konfiguriert
* **MonochromeDark Theme** - Standard Theme für Ultrahand
* **Sphaira Themes** - Custom Homebrew Menu Themes
* **Boot Logos** - Verschiedene Boot-Logos (Android, Ubuntu, Fedora, etc.)
* **Hekate Konfiguration** - Vorkonfigurierte Boot-Optionen

### **6. Sicherheitsfeatures**
* **DNS-MitM** - DNS Redirection für Blocking
* **sys-patch** - Automatische System-Patches
* **External Bluetooth DB** - Shared Bluetooth Database
* **USB 3.0 Force** - Erweiterte USB Performance
* **Report Cleanup** - Automatische Log-Bereinigung

## Installation

1. **SD-Karte vorbereiten** - Formatieren als FAT32 oder exFAT
2. **Dateien kopieren** - Alle Dateien auf die SD-Karte kopieren
3. **Payload laden** - Hekate oder Fusee über RCM laden
4. **Konfiguration** - Optional: Einstellungen in `config/` anpassen

## Verwendung

### **Boot-Optionen:**
- **CFW-EmuMMC** - Custom Firmware mit EmuMMC
- **OFW** - Original Firmware (Backup)
- **TegraExplorer** - Dateisystem-Explorer
- **Lockpick RCM** - Keys extrahieren

### **Overlay-Menü:**
- **L+R+PLUS** - Ultrahand Overlay öffnen

### **Homebrew Menu:**
- **Album** - Sphaira Homebrew Menu öffnen

## Lizenz

Die verwendeten Programme unterliegen ihren jeweiligen Lizenzen. NiklasCFW Pack selbst steht unter der MIT-Lizenz.

**[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE):**
* [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)

## Credits

* **Atmosphere Team** - Custom Firmware
* **CTCaer** - Hekate Bootloader
* **ppkantorski** - Ultrahand Overlay & sys-clk
* **ITotalJustice** - Viele Homebrew Apps
* **WerWolv** - Tesla Menu & EdiZon
* **Sthetix** - LockPick RCM PRO 
* **Woody-NX** - NiklasCFW Pack Creator

## Support

Falls Ihnen das Projekt gefällt und Sie es unterstützen möchten:

* **Discord:** [NiklasCFW Modding Community](https://discord.gg/5rMJ4fWQT3)
* **YouTube:** [NiklasCFW Channel](https://www.youtube.com/@NiklasCFW)
* **GitHub:** [Woody-NX](https://github.com/Woody-NX)
* **Wiki:** [NiklasCFW Wiki](https://docs.niklascfw.de)
---

<div align="center">
  
[![Aktuelle Version](https://img.shields.io/github/v/release/Woody-NX/NiklasCFW_Pack?style=for-the-badge&label=NiklasCFW%20Pack%20Version&labelColor=7d7d7d&color=00d2d0)](https://github.com/Woody-NX/NiklasCFW_Pack/releases/latest)
[![Firmware](https://img.shields.io/github/v/release/THZoria/NX_Firmware?display_name=release&filter=*21.0.0&style=for-the-badge&label=Kompatibel%20mit%20FW&labelColor=7d7d7d&color=00d2d0)](https://github.com/THZoria/NX_Firmware/releases/tag/21.0.0)
[![Atmosphere Version](https://img.shields.io/github/v/release/Atmosphere-NX/Atmosphere?include_prereleases&filter=1.10.0-prerelease&style=for-the-badge&label=Atmosphere%20Version&labelColor=7d7d7d&color=00d2d0)](https://github.com/Atmosphere-NX/Atmosphere/releases/tag/1.10.0-prerelease)

[![Release Datum](https://img.shields.io/github/release-date/Woody-NX/NiklasCFW_Pack?display_date=published_at&style=for-the-badge&label=Released%20%20&labelColor=7d7d7d&color=00d2d0)](https://github.com/Woody-NX/NiklasCFW_Pack/releases)
[![NiklasCFW_Pack Downloads](https://img.shields.io/github/downloads/Woody-NX/NiklasCFW_Pack/total?style=for-the-badge&label=NiklasCFW%20Pack%20Downloads&labelColor=7d7d7d&color=00d2d0)](https://github.com/Woody-NX/NiklasCFW_Pack/releases)

# **Socials** 
[![Discord](https://img.shields.io/discord/733728731432091648?style=for-the-badge&logo=discord&logoColor=ffffff&logoSize=auto&label=NiklasCFW%20Modding%20Community&labelColor=7d7d7d&color=00d2d0)](https://discord.gg/5rMJ4fWQT3)

[![YouTube Channel](https://img.shields.io/youtube/channel/subscribers/UCdEkFmAShnlE15CCimAwnYg?style=for-the-badge&logo=youtube&logoSize=auto&label=NiklasCFW&labelColor=7d7d7d&color=00d2d0)](https://www.youtube.com/@NiklasCFW)

</div>
