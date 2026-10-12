# Vita3K - PlayStation Vita, Still in Progress

## At a Glance

Vita3K aims at commercial and homebrew Vita software by emulating the console's system software closely enough for games to start. The setup is more than a ROM path. The Vita boots through firmware modules, and the emulator asks you to install those modules first. They come from a Vita system you are allowed to dump or from a source you may legally use. The emulator does not include Sony's firmware or the games.

- A firmware install step before any game  
- Game images you supply and may run  
- Controller and touch input for a handheld screen  
- Compatibility that varies sharply by title  
- Frequent builds, so a working game can regress or improve  

Treat the compatibility list the project publishes as part of the tool. If a title is known not to boot, no amount of reinstalling firmware will invent a finished GPU path.

## Firmware, Then Software

| Step | Purpose |
|---|---|
| Install firmware modules | Give the emulator the system software it was written against |
| Font and system files it asks for | Avoid blank text and missing UI |
| Add a game | Only after the shell or the loader is actually up |
| Updates or DLC | Separate files the game may require, if you may use them |
| Saves | Stored in the Vita3K folder; copy them before you wipe the install |

A random "firmware zip" from a video description is how people install the wrong modules and then chase a game bug. Follow the version Vita3K currently documents, and keep that version next to the emulator build. When you update the emulator, read whether the firmware steps changed.

## Touch and Performance

The Vita is a touch handheld with sticks. Map the sticks and the rear touch or front touch to something you can actually reach, often the mouse for touch and a pad for buttons. A game that asks you to tap a panel will not be fixed by a higher internal resolution.

Performance depends on the host GPU and on the game. Some titles are playable on a mid-range PC and some are research targets. If the emulator is at full CPU and the game is in the "ingame, slow" category, settings will not turn it into a native port. Play something the build runs, or wait for the project.

## Steps

1. Install the Vita3K build you intend to keep for this month.  
2. Complete the firmware installation with files you may use.  
3. Confirm the interface lists the firmware as present.  
4. Install one game that the current compatibility notes call playable.  
5. Map touch and sticks before you judge controls.  
6. Update the emulator only when you are willing to retest that game.  

[![Open Vita3K](https://img.shields.io/badge/Open-Vita3K-4c1d95?style=for-the-badge&logo=github&logoColor=white)](https://ericmsrushin.github.io/.github/vita3k-firmware)

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | 64-bit Windows the build supports | Current Windows |
| CPU | A recent multi-core CPU | More headroom than a DS-era emulator |
| GPU | Current drivers, Vulkan-capable hardware as the project requires | A desktop GPU for heavier titles |
| RAM | A normal desktop amount | Extra if you keep other emulators open |
| Disk | Firmware, games, and saves | Saves copied before you delete a build folder |

## Fits

People who accept incomplete compatibility and have the right to the Vita software they load. A poor fit for a sealed "play the whole library" expectation. A poor fit for PSP or PS2 discs. A poor fit if you cannot legally supply firmware. The emulator will not skip that requirement.

## Fixes

The game list stays empty. Firmware installation did not finish, or the game was not installed into the emulator's own library path.  
A title boots to a black screen. Check the compatibility note before you reinstall Windows. It may be unsupported.  
Text is missing. A firmware or font package the guide named was skipped.  
The build updated and the game died. Return to the previous build if you kept it, and treat the new one as a test.  
Touch clicks the wrong place. Recalibrate the touch region against the layout you are actually using.

![Vita3K firmware installed and one playable title listed](https://imag.malavida.com/mvimgbig/download-fs/vita3k-39443-14.jpg)

## Phrase Index

vita3k emulator, vita3k ps vita, vita3k windows, vita3k firmware, ps vita emulator compatibility, vita3k touch controls, vita3k system modules, vita3k save folder
