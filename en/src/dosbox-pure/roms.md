# Game Images / Game Archives

To run games with `DBP`, you'll need the games themselves. Game archives are typically found in one of the following formats:

- A copy of an installed game: this is a folder with a pre-installed game copied from the `C:` drive.
- A copy of files from the installation disk: this is also a folder containing files, typically including one named something like `install` or `setup`.
- Floppy disk images: these usually have extensions like `.img`, `.ima`, or `.dsk`.
- CD-ROM images: these usually come as a single `.iso` file or as a pair of `.cue` and `.bin` files.

Whatever form the game takes, it can (but doesn’t have to) be packed into a `.zip` archive before being run through `DBP`.

DOS games typically consist of many files, and packing them into a single archive creates an equivalent of a `ROM` file used in console emulators.

Depending on the files in the archive, `DBP` will handle them differently:

1. Regular files and folders will be mounted as the `C:` drive in the emulated system.
2. Floppy disk images will be mounted as floppies in the `A:` drive.
3. CD-ROM images will be mounted as CDs in the `D:` drive. See also [Disc-based Games](./cd-rom.md).

An archive can include all these types of files, and `DBP` will automatically determine how to mount them.

It’s best to organize all game archives in a folder that will open by default when selecting the `Load Content` option in RetroArch (see the section on [System Folders](../retroarch/folders.md#file-browser)).