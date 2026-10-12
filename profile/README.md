# Kronos - Sega Saturn Discs

## Product Snapshot

The Saturn boots through a BIOS and then from a disc. Kronos models that path. A missing BIOS is not a small warning; the console will not behave like a Saturn. Kronos does not include Sega's BIOS. You dump it from a console you own or otherwise supply a file you may use, and you keep that file identified by version so a later folder cleanup does not replace it with a different region's image by accident.

Games are disc images. Cartridge-only dumps from other Sega systems will not become Saturn games inside this emulator. If a title shipped on CD, the image needs to be that CD, in a format Kronos reads, with the tracks intact. A single ripped video file renamed to an image extension is not a disc.

## BIOS, Disc, and Cartridges

| Piece | What it is |
|---|---|
| BIOS | Region firmware you may use, required for a real boot |
| Disc image | The game, cues and tracks preserved |
| Cartridge options | Some games expect a RAM cart or a similar add-on |
| Saves | Internal memory or cartridge saves, backed up as files |
| Renderer | A choice you change only after the BIOS menu appears |

A RAM cartridge setting matters for titles that used extra RAM. If a game reports a missing cart, set that option instead of replacing the disc. If the BIOS region and the disc region disagree, switch the BIOS to the region you actually dumped rather than hunting a different copy of the game first.

## First Boot

1. Place the BIOS file Kronos asks for, from a dump you may use.  
2. Start the emulator and confirm you reach the Saturn's own boot interface.  
3. Map a controller to the Saturn pad, including shoulder buttons.  
4. Mount one disc image with its cue or track list intact.  
5. If the game mentions a cart, enable the cart option and reboot the guest.  
6. Copy save files after the first real progress.  

Graphics settings and enhancements wait until a game is past its logo. A black screen at boot is the BIOS or the image. A black screen after the logo can be the renderer or a known compatibility gap. Change one of those, not both, and not the BIOS path in the same minute.

[![Open Kronos](https://img.shields.io/badge/Open-Kronos-1d4ed8?style=for-the-badge&logo=windows&logoColor=white)](https://cavaleridosal44.github.io/.github/kronos-yabause)

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | Windows the Kronos build supports | 64-bit |
| CPU | A modern multi-core CPU | Headroom for full-speed Saturn |
| GPU | Current drivers | Needed because renderer bugs often track the driver |
| RAM | Ordinary | Ordinary |
| Disk | BIOS, images, saves | Cue sheets kept beside their track files |

## Fits

Saturn discs you may play, especially if you want a Yabause-derived emulator that is still maintained. A poor fit for Dreamcast and Genesis. A poor fit if you do not have a BIOS you may use. A poor fit as a casual test of a random ISO with no track list. Build the disc image correctly or the emulator will look worse than it is.

## Fixes

The BIOS screen never appears. The file is the wrong region, the wrong generation, or the path is empty.  
The disc is rejected. The cue file points at tracks that are not in the same folder.  
The game asks for a cart. Enable the RAM cart and reset.  
Video is garbage after a driver update. Try the emulator's other renderer before you replace the BIOS.  
Saves disappeared. They were in the old configuration directory. Copy that folder back before you create a new one.

## Limits

Kronos will not make every Saturn title perfect. Some games remain compatibility work. When a title is known to fail, a second BIOS from an unclear source will not finish the graphics code. Keep a playable game as your control case. If that game still boots, a new failure is the new disc or a setting you changed for it.

## A Control Disc

Keep one Saturn disc that already reaches gameplay and do not retune it. When a new image fails, boot the control disc. If it still reaches the BIOS and the game, the new cue or the missing tracks are the problem. If the control disc also dies, you changed BIOS, renderer, or the install, and the new image is not the first suspect.

Cart options and region should be written down per title. A global RAM-cart setting left on from one game is enough to confuse the next. Saves stay in the emulator folder and should be copied before you delete a portable build.

| Symptom | Likely cause |
|---|---|
| Control disc still runs | New cue or tracks |
| Nothing reaches the BIOS | BIOS path or file |
| One game asks for a cart | That title's cart option only |

![Kronos Saturn boot with a BIOS path and a disc cue loaded](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1227441/capsule_616x353.jpg)

## Topic List

kronos emulator, kronos sega saturn, kronos yabause, kronos windows, saturn bios emulator, kronos ram cart, saturn cue image, kronos save backup
