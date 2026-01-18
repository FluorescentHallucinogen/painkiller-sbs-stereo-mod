# PainKiller SBS (Side-by-Side) Stereo Mod

This mod adds support for native half-width SBS (side-by-side) 3D stereoscopic video rendering to the original *PainKiller* video game developed by *People Can Fly* and published by *DreamCatcher*.

![Screenshot](screenshot.png)

## Requirements

The mod requires the latest version (1.64) of *PainKiller* (*PainKiller: Heaven’s Got a Hitman*) and/or *PainKiller: Battle Out of Hell* video games.

It was tested only with [*PainKiller: Black Edition* on Steam](https://store.steampowered.com/app/39530).

## Install

1. Download the [ZIP archive with the mod](https://github.com/FluorescentHallucinogen/painkiller-sbs-stereo-mod/releases/latest/download/painkiller-sbs-stereo-mod_0.1.2.zip).

2. Place the `*.exe` and `.dll` files from the ZIP archive’s `/Bin` directory into the game’s `/Bin` directory.

## Enable

1. Open the `/Bin/config.ini` file in any text editor.

2. Add the `Cfg.VideoStereo = true` line and save the file.

## Use

Use stereo glasses or a VR headset with software that supports the Half SBS stereo mode, e.g. [Virtual Desktop](https://vrdesktop.net).

## Advanced configure

You can also change the values of `Cfg.VideoStereoSeparation` and `Cfg.VideoStereoFocusDistance` if you know what you’re doing.

## Notes

This mod is compatible with other mods that do not modify the game’s executable files.
