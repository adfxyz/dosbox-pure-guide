# Настройка звука

## Audio Sample Rate

Частота дискретизации аудио. Лучше всего оставить значение по умолчанию `48000`.

## SoundBlaster Settings

Параметры [SoundBlaster](https://ru.wikipedia.org/wiki/Sound_Blaster): `Port`, `IRQ` и `DMA`. Можно оставить значения по
умолчанию, или выбрать собственные. В любом случае, эти параметры надо запомнить, потому что они могут пригодиться при
настройке звука в играх.

## MIDI Output

Настройка MIDI-выхода.

![Меню MIDI Output](../../assets/dosbox-pure/midi.png)

### OFF

MIDI-выход отключен.

### Frontend MIDI driver

Использовать MIDI-устройство, выбранное в настройках RetroArch.

### SoundFont

Использовать [SoundFont-файл](https://en.wikipedia.org/wiki/SoundFont) для воспроизведения MIDI. SoundFont-файлы должны
иметь расширение `.sf2`. И их нужно положить в папку [System/BIOS](../../retroarch/folders.md#systembios), и тогда они
появятся в этом меню.

Скачать файлы SoundFont можно, например, [тут](https://www.philscomputerlab.com/general-midi-and-soundfonts.html).

### Roland MT-32

Использовать эмуляцию [Roland MT-32](https://en.wikipedia.org/wiki/Roland_MT-32) для воспроизведения MIDI. Для этого
нужно положить ROM-файлы для MT-32 в папку [System/BIOS](../../retroarch/folders.md#systembios).

Вам понадобится файлы `MT32_CONTROL.ROM` и `MT32_PCM.ROM`. Эти файлы можно найти в интернете.

## SoundBlaster Type

Тип эмулируемой звуковой карты SoundBlaster. `SoundBlaster 16`, `SoundBlaster Pro` и т.д.

## SoundBlaster Adlib/FM Mode

Выбор режима
эмуляции [AdLib](https://ru.wikipedia.org/wiki/AdLib#AdLib_Gold)/[FM-синтеза](https://ru.wikipedia.org/wiki/FM-%D1%81%D0%B8%D0%BD%D1%82%D0%B5%D0%B7).
Грубо говоря, определяет,
какой [тип микросхемы OPL](https://ru.wikipedia.org/wiki/%D0%9C%D0%B8%D0%BA%D1%80%D0%BE%D1%81%D1%85%D0%B5%D0%BC%D1%8B_%D0%B3%D0%B5%D0%BD%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BE%D0%B2_%D0%B7%D0%B2%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B9_%D1%87%D0%B0%D1%81%D1%82%D0%BE%D1%82%D1%8B#%D0%9C%D0%B8%D0%BA%D1%80%D0%BE%D1%81%D1%85%D0%B5%D0%BC%D1%8B_%D0%B7%D0%B2%D1%83%D0%BA%D0%BE%D0%B3%D0%B5%D0%BD%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BE%D0%B2_%D0%BD%D0%B0_%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5_%D1%84%D0%B0%D0%B7%D0%BE%D0%B2%D0%BE%D0%B9_%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8F%D1%86%D0%B8%D0%B8)
будет эмулироваться.

При выборе `Auto` режим будет автоматически выбираться в зависимости выбранного типа SoundBlaster.

## SoundBlaster Adlib Provider

Выбор эмулятора для AdLib/FM-синтеза: стандартный или [Nuked OPL3](https://github.com/nukeykt/Nuked-OPL3).

## Enable Gravis Ultrasound

Включить эмуляцию звуковой карты [Gravis Ultrasound](https://ru.wikipedia.org/wiki/Gravis_Ultrasound).

Параметры Gravis Ultrasound:

- Port: `0x240`
- IRQ: `5`
- DMA: `3`

## Enable Tandy Sound Device

Включить эмуляцию звуковой карты [Tandy](https://en.wikipedia.org/wiki/Tandy_1000).

## Swap Stereo Channels

Поменять местами левый и правый каналы.