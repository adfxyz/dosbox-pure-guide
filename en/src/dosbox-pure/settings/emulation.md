# Emulation Settings

The `Core Options` → `Emulation` menu contains general settings related to emulation.

## Force 60FPS Output

Forces output at 60 frames per second. Enable this if you encounter issues with vertical synchronization.

## Show Performance Statistics

Displays performance statistics at the top of the screen. There are two modes: simple and detailed.

![Example of performance statistics in simple mode](../../assets/dosbox-pure/stats-simple.png)  
![Example of performance statistics in detailed mode](../../assets/dosbox-pure/stats-detailed.png)

## Save States Support

Enables support for saving and loading game states, as well as the rewind feature. See the chapter on [Saving and Loading](../save-load.md#saving-and-loading-game-state-with-saveload-state) for more details.

## Loading of dosbox.conf

Automatically loads a `dosbox.conf` settings file when starting a game. Two options are available: load the `dosbox.conf` file from the game's folder or archive, or load a `.conf` file with the same name as the game. Disabled by default.

## Start Menu

Allows you to configure when the DOSBox Pure start menu is displayed. By default, it is shown at core startup (before launching a game) and after exiting a game.
