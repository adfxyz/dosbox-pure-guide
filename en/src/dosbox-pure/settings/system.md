# System Settings

## Memory Size

Specifies the amount of [RAM](https://en.wikipedia.org/wiki/Random-access_memory) for the emulated computer. The default value is `16 MB`, which is suitable for most games. Some games may require increasing the memory size.

## CPU Type

Defines the type of emulated processor, which determines the [instruction set](https://en.wikipedia.org/wiki/Instruction_set_architecture) available to programs. The default setting is `Auto`, which aims to provide maximum compatibility and performance.

## CPU Core

Specifies the CPU emulation mode used by DOSBox Pure. It is recommended to select `Auto`, which dynamically chooses the best mode for maximum compatibility and performance depending on the game being run.

## OS Disk Modifications

Controls how changes to the system drive `C:` are [saved](../win9x/save-load.md) for an installed [operating system](../win9x/index.md).

This setting can be adjusted even after the operating system has been installed.

Available options:

### Keep

All changes are saved to the disk image file.

### Discard

All changes are lost upon restarting the system.

### Save Difference Per Content

A separate file is created for each game run through the installed operating system, storing all changes made to the `C:` drive. This allows you to maintain a shared base disk image of the installed system while creating unique change files for each game.

These change files are saved in the [Save Files](../../retroarch/folders.md#save-files) folder.

## Free Space in D: in OS

Defines the amount of free space available on drive `D:` in the operating system mode. The default is `1 GB`. See also [Saving Data in the OS](../win9x/save-load.md).

## Force Normal Core in OS

If the emulator crashes or experiences glitches in OS mode, you can enable this setting to force the use of the `Normal` CPU emulation mode when running the operating system.