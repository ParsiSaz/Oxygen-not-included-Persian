<div align="center">

# 🧪 Oxygen Not Included | Persian Localization (پارسی‌ساز اکسیژن)
### *Official ParsiSaz Community Translation & Mod Package for Klei's Oxygen Not Included*

<br/>

[![ParsiSaz Portal](https://img.shields.io/badge/🌐_Documentation_Portal-parsisaz.github.io%2Fparsisaz-00f2fe?style=for-the-badge&logo=googlechrome)](https://parsisaz.github.io/parsisaz/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![Locale](https://img.shields.io/badge/Locale-fa__IR-emerald?style=for-the-badge)](#-project-structure)
[![Maintainer](https://img.shields.io/badge/Maintained_by-Danial_Pahlavan-blue?style=for-the-badge&logo=github)](https://github.com/DanialPahlavan)

</div>

---

## 📖 Overview
This repository contains the Persian community translation and typography package for **Oxygen Not Included** (by Klei Entertainment), organized following the **ParsiSaz 2026 Game Localization Architecture (L10N-STD-2026)**.

---

## 🗂️ Project Structure (L10N-STD-2026)

```
Oxygen-not-included-Persian/
├── loc/                           # Decoupled Core Localization Data
│   ├── fa-IR/                     # Standard BCP-47 Persian String Tables
│   │   ├── strings.po             # Editable Gettext PO translation file
│   │   └── strings.mo             # Compiled high-performance binary catalog
│   ├── templates/                 # Master extraction template
│   └── glossaries/                # Chemistry & colony management glossary
├── game_assets/                   # Drop-in Engine Structure
│   └── strings/                   # Klei mod directory layout
├── HISTORY.md                     # Semantic Versioning Changelog
├── README.md                      # Project documentation
├── mod_info.yaml                  # Klei mod manifest metadata
└── LICENSE                        # GNU General Public License v3
```

---

## 🚀 Installation Instructions

### Method 1: Drop-in Local Mod
1. Download this repository as a ZIP archive.
2. Extract the archive into your Klei mod directory:
   ```text
   %userprofile%\Documents\Klei\OxygenNotIncluded\mods\Local\OxygenNotIncluded_Persian\
   ```
3. Ensure `strings/strings.po` exists inside that folder.
4. Launch the game, navigate to **Mods** in the main menu, and enable **OxygenNotIncluded_Persian**.
5. Restart the game to enjoy full Persian dialogues, tooltips, and colony alerts!

---

## 🌐 Central Documentation & Bug Reports
For more details on engine hurdles, reverse engineering, and other games in the ecosystem:
👉 **[Open ParsiSaz Live Portal](https://parsisaz.github.io/parsisaz/)**