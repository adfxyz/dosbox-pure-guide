# Video Settings

## Emulated Graphics Chip

Allows you to select the graphics mode to use. By default, the most advanced mode, [SVGA](https://en.wikipedia.org/wiki/Super_VGA), is used. However, some older games may require switching to modes such as [CGA](https://en.wikipedia.org/wiki/Color_Graphics_Adapter) or [EGA](https://en.wikipedia.org/wiki/Enhanced_Graphics_Adapter). Other supported modes include [Hercules](https://en.wikipedia.org/wiki/Hercules_Graphics_Card), [Tandy](https://en.wikipedia.org/wiki/Tandy_Graphics_Adapter), and [PCjr](https://en.wikipedia.org/wiki/IBM_PCjr).

## SVGA Mode

Specifies the graphics card emulated for SVGA mode. By default, the [S3 Trio64](https://en.wikipedia.org/wiki/S3_Trio) is selected, which works well for most games.

## SVGA Memory Size

Defines the amount of [video memory](https://en.wikipedia.org/wiki/Video_random-access_memory) available to the emulated graphics card.

## 3dfx Voodoo Emulation

Enables emulation of the [3dfx Voodoo](https://en.wikipedia.org/wiki/3dfx#Voodoo_Graphics_PCI) accelerator and allows setting its video memory size.

## 3dfx Voodoo Performance

Configures the performance mode of the 3dfx Voodoo accelerator. By default, the `Software Multi Threaded` mode is used, where emulation is handled by the CPU across multiple threads.

Depending on your version of DOSBox Pure, the `Hardware OpenGL` mode may also be available. This mode uses your primary GPU for 3D emulation, significantly improving 3D graphics performance, enhancing rendering quality, and unlocking additional features.

## 3dfx Voodoo OpenGL Scaling

Controls 3D graphics scaling when using the `Hardware OpenGL` mode. Works in conjunction with [scaling options set in RetroArch](../../retroarch/video.md).

**Example:** If the game resolution is set to `640x480`, the `Hardware OpenGL` scaling is set to `2x`, and RetroArch's scaling is also set to `2x`, the 3D scene will be rendered at `1280x960` resolution and then upscaled to `2560x1920`.

## 3dfx Voodoo Gamma Correction

Adjusts the brightness of 3D graphics when using the `Hardware OpenGL` mode.

## Aspect Ratio Correction

Corrects the aspect ratio to maintain a 4:3 proportion, mimicking the display proportions of older [CRT](https://en.wikipedia.org/wiki/Cathode-ray_tube) monitors. Enabling this is recommended for preserving the original visual experience.

## Overscan Border Size

Adds a border around the edges of the screen. Some games use the border to display additional information with colored edges.