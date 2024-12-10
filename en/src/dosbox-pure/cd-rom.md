# Disc-Based Games

`DOSBox Pure` supports running games from CD images in `.iso` or `.bin/.cue` formats.

To run a disc-based game, simply select the disc image via the `Load Content` menu.

If the disc image is successfully mounted, you’ll see a message at the top of the `DBP` menu, such as `EJECT IMAGE_NAME.cue`. Below this, you’ll find the files from the image, accessible via the `D:` drive.

In most cases, disc-based games need to be installed onto the `C:` drive first. See [Running Games](./run-games.md#installing-and-configuring-games) for details.

> [!NOTE]  
> The disc image can also be inside a `.zip` archive. If you open the archive through the `Load Content` menu, `DBP` will automatically mount the disc image.

## Multi-Disc Games

`DOSBox Pure` can mount only one disc image at a time. If a game requires multiple discs, you’ll need to switch discs manually as needed.

It is highly recommended to store all disc images for a game in a single `.zip` archive. The following instructions assume this setup.

To switch discs:

1. Open the `Quick Menu` (`F1`).
2. Select `Disk Control`.
3. Select `Eject Disk` to eject the current disc.
4. Select `Current Disk Index`.
5. You’ll see a list of images from the archive. Choose the desired disc image.
6. Select `Insert Disk`.

## Floppy Disk Games

Games on floppy disk images (files with extensions `.img`, `.ima`, `.dsk`) are mounted in `DOSBox Pure` as floppies inserted into the `A:` drive. You can interact with them just like CD images.