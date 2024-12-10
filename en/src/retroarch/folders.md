# System Folders

RetroArch stores its data in several folders. Here are some that might be useful when working with DOSBox Pure:

## System/BIOS

This folder contains system files. Place SoundFont files or ROM files for the Roland MT-32 here if you want to enable [MIDI emulation](../dosbox-pure/settings/audio.md#midi-output). It also stores system disk images used by `DBP` for [installing an operating system](../dosbox-pure/win9x/index.md).

## Configuration Files

This folder is where `DBP` saves its settings. It also stores [game-specific configurations for DBP](../dosbox-pure/per-game-settings.md).

## Save Files

This folder contains save data created by the games themselves.  

If you [run](../dosbox-pure/run-games.md) a game from an [archive or disk image](../dosbox-pure/roms.md), archives with data written to the `C:` drive by the game will be created here. See also [Save and Load](../dosbox-pure/save-load.md#saving-changes-to-the-c-drive).

Additionally, files with changes made to the `C:` drive will be saved here for [an installed operating system](../dosbox-pure/win9x/save-load.md) if you use the [Save Difference Per Content](../dosbox-pure/settings/system.md#os-disk-modifications) mode.

## Save States

This folder stores game states saved through the RetroArch [Save / Load State](../dosbox-pure/save-load.md#saving-and-loading-game-state-with-saveload-state) feature.

## Cores

This folder contains emulator cores used by RetroArch (see [Installing DOSBox Pure](../dosbox-pure/install.md)).

## Video Shaders

A folder for additional [shaders](../dosbox-pure/shaders.md) to enhance graphics.

## File Browser

This folder is the default location RetroArch will open when you select `Load Content`. You can place game archives here.

The exact location of these folders depends on your device, operating system, and how RetroArch was installed.  
You can check their locations under the `Settings / Directory` section, where you can also change their paths.

Once you’re familiar with system folders, you can proceed to [configuring graphics](./video.md) in RetroArch.