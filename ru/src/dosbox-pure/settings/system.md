# Системные настройки

## Memory Size

Объём [оперативной памяти](https://ru.wikipedia.org/wiki/%D0%9E%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D0%B0%D1%8F_%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C) для эмулируемого компьютера. По умолчанию установлено `16 MB`, что подойдёт для большинства
игр. Для некоторых игр может потребоваться увеличить объём памяти.

## CPU Type

Тип эмулируемого процессора, который определяет [набор инструкций](https://ru.wikipedia.org/wiki/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4), доступных программам. По умолчанию выбран режим
`Auto`, который старается обеспечить максимальную совместимость и производительность.

## CPU Core

Режим эмуляции процессора, который будет использоваться в DOSBox Pure. Рекомендуется выбрать `Auto` — тогда режим будет
выбираться автоматически, чтобы обеспечить максимальную совместимость и производительность, в зависимости от запускаемой
игры.

## OS Disk Modifications

Определяет, каким образом будут [сохраняться изменения](../win9x/save-load.md) в системном диске `C:` для
установленной [операционной системы](../win9x/index.md).

Эту настройку можно менять уже после того, как операционная система была установлена.

Доступные варианты:

### Keep

Все изменения сохраняются в файл с образом диска.

### Discard

Все изменения теряются при перезапуске системы.

### Save Difference Per Content

Для каждой игры, запущенной через установленную операционную систему, будет создаваться отдельный файл, в который будет
записываться все изменения на диске `C:`. Это позволяет создать один общий образ системного диска с установленной
системой, и для каждой игры создавать свой собственный файл с изменениями.

Эти файлы с изменениями будут сохраняться в папке [Save Files](../../retroarch/folders.md#save-files).

## Free Space in D: in OS

Объём свободного места на диске `D:` в режиме операционной системы. По умолчанию установлено `1 Gb`. См.
также [Сохранение данных в ОС](../win9x/save-load.md).

## Force Normal Core in OS

Если в режиме ОС эмулятор зависает или глючит, то можно попробовать включить эту настройку, чтобы принудительной
использовать режим `Normal` для эмуляции процессора при запуске операционной системы.