<div align="center">

# 🔘 Minimap Button Frame

[![Documentation](https://img.shields.io/badge/📖_Docs-GitHub_Pages-2ea44f?style=for-the-badge)](https://xurkon.github.io/PA-MinimapButtonFrame/)

<img src="https://img.shields.io/badge/WoW-3.3.5a-blue?style=for-the-badge&logo=battle.net&logoColor=white" alt="WoW 3.3.5a">
<img src="https://img.shields.io/badge/Version-3.1.5-green?style=for-the-badge" alt="Version 3.1.5">
<img src="https://img.shields.io/badge/Project-Ascension-purple?style=for-the-badge" alt="Project Ascension">

[![Patreon](https://img.shields.io/badge/Patreon-Support-orange?style=for-the-badge&logo=patreon)](https://patreon.com/Xurkon)
[![PayPal](https://img.shields.io/badge/PayPal-Donate-blue?style=for-the-badge&logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=kancerous@gmail.com)

**Collects minimap addon buttons and organizes them into a movable, customizable frame**

<br>

<img src="https://img.shields.io/badge/Localized-9%20Languages-informational?style=flat-square" alt="Localization">

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 📦 Button Collection

- Automatically gathers minimap buttons
- Manual add/remove with `/mbf add` and `/mbf remove`
- Alphabetical or custom sorting
- Supports up to 50 buttons per row/column

</td>
<td width="50%">

### 🎨 Customization

- Movable and resizable frame
- Customizable background color
- Modular button skins
- Multiple anchor positions
- Grow buttons up/down option

</td>
</tr>
<tr>
<td width="50%">

### 🔌 Addon Integration

- **ElvUI** - Seamless integration toggle
- **LDB** - LibDataBroker support
- Profile system for settings
- Protected icon exclusions

</td>
<td width="50%">

### 🌍 Localization

- English, German, French
- Spanish (ES/MX), Korean
- Russian, Chinese (CN/TW)

</td>
</tr>
</table>

---

## 📦 Installation

1. Download the latest release
2. Extract to `Interface/AddOns/MinimapButtonFrame`
3. Restart WoW or `/reload`

---

## 🎮 Usage

### Slash Commands

| Command | Description |
|---------|-------------|
| `/mbf` | Display command options |
| `/mbf add [button]` | Add button under cursor (or named) |
| `/mbf remove [button]` | Remove button from frame |
| `/mbf show` | Show the MBF frame |
| `/mbf hide` | Hide the MBF frame |
| `/mbf config` | Open configuration |
| `/mbf info` | Show info about object under cursor |

### Minimap Button

| Action | Result |
|--------|--------|
| **Left-click** | Show/hide the frame |
| **Shift-click** | Open config screen |
| **Right-click + drag** | Move the minimap button |

---

## 🔧 ElvUI Integration

MBF includes seamless ElvUI integration:

- **MBF Controls Buttons**: Default mode - MBF manages all minimap buttons
- **ElvUI Controls Buttons**: Toggle in MBF settings → Plugins to let ElvUI's Button Grabber take over
- Both addons offer reload prompts when switching control

---

## 📜 Changelog

<details open>
<summary><b>v3.1.x</b> - Project Ascension Updates</summary>

### v3.1.7

- ✨ ElvUI's Button Grabber now auto-enabled when switching to ElvUI control
- 🔄 Updated popup message to confirm auto-enable

### v3.1.6

- 🔧 SkinPack addon now auto-disabled when switching to ElvUI button control

### v3.1.5

- 🔧 Fixed quest icon pins (pfQuest etc.) no longer collected into MBF
- ➕ Added pfQuest minimap pin frames to icon exclusion list
- 🔄 Improved detection of non-button minimap elements

### v3.1.4

- ➕ MBF options grey out when ElvUI's Button Grabber is in control
- ➕ Warning message in MBF settings when ElvUI controls buttons
- ➕ ElvUI popup to disable MBF when enabling Button Grabber

### v3.1.3

- ➕ Added "Plugins" submenu in MBF options for addon integrations
- ➕ ElvUI Integration toggle: "Let ElvUI Control Buttons"
- ➕ Popup when toggling to ElvUI offers to disable MBF addon

### v3.1.2

- 🔧 Fixed ElvUI minimap panels no longer hide when MBF is hidden
- 🔄 Added all 8 ElvUI MiniPanel frames to protection list

### v3.1.1

- 🔧 Fixed ElvUI drag conflict - MBF drags independently
- 🔧 Fixed anchor chain issues with MMHolder and ElvUI
- ➕ New ElvUI integration toggle in Maps → Minimap → Buttons
- 🔄 Removed debug print statements

</details>

<details>
<summary><b>v3.0.x - v3.1.0</b></summary>

### v3.1.0

- 🔧 Fixed initial profile set to default
- 🔧 Fixed MinimapButtonFrame.lua:1332 error
- ➕ Added grow buttons up option
- ➕ Added MBF anchor position selection

### v3.0.x

- ✨ Redesigned config screens using Ace3
- ➕ New title bar drag system
- ➕ Profile support
- ➕ Custom button sorting

</details>

<details>
<summary><b>Earlier Versions</b></summary>

See `Readme.txt` for full version history from v0.9 to v2.4

</details>

---

## ⚠️ Known Issues

- **MetaMap**: Incompatible due to continual position resetting
- **SexyMap**: Disable all minimap icon control for best results
- **Enchantrix / onRaid**: Cannot grab buttons without names

---

## 👥 Credits

<table>
<tr>
<td align="center">
<b>Bachlott</b><br>
<sub>Original Author</sub>
</td>
<td align="center">
<b>Xurkon</b><br>
<sub>Project Ascension Updates</sub>
</td>
</tr>
</table>

---

<div align="center">

**Made for [Project Ascension](https://ascension.gg)**

<sub>This addon is open source and provided as-is. Not affiliated with Blizzard Entertainment.</sub>

</div>

[Documentation](docs/index.html)
