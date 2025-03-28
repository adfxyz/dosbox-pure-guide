# Настройка графики

## Emulated Graphics Chip

Здесь можно выбрать, какой графический режим будет использоваться. По умолчанию используется наиболее современный
режим [SVGA](https://ru.wikipedia.org/wiki/SVGA), но для некоторых старых игр может потребоваться переключиться
на [CGA](https://ru.wikipedia.org/wiki/CGA)
или [EGA](https://ru.wikipedia.org/wiki/EGA). Также поддерживаются
режимы [Hercules](https://ru.wikipedia.org/wiki/HGC), [Tandy](https://ru.wikipedia.org/wiki/Tandy_Graphics_Adapter) и
[PCjr](https://ru.wikipedia.org/wiki/IBM_PCjr).

## SVGA Mode

Какая графическая карта будет эмулироваться для режима SVGA. По умолчанию
выбрана [S3 Trio64](https://ru.wikipedia.org/wiki/S3_Trio#Trio64,_Trio64V+), и она подойдет для
большинства игр.

## SVGA Memory Size

Объём [видеопамяти](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D0%B4%D0%B5%D0%BE%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C) у эмулируемой видеокарты.

## 3dfx Voodoo Emulation

Включает эмуляцию ускорителя [3dfx Voodoo](https://ru.wikipedia.org/wiki/3dfx_Interactive#Voodoo), а также позволяет
выбрать для него объём видеопамяти.

## 3dfx Voodoo Performance

Настройка производительности ускорителя 3dfx Voodoo. По умолчанию используется режим `Software Multi Threaded`, в
котором эмуляция выполняется на процессоре, используя несколько потоков.

В зависимости от версии DOXBox Pure может быть доступен режим `Hardware OpenGL`, в котором для эмуляции 3D будет
использоваться ваша основная видеокарта. Это значительно увеличивает производительность при отрисовки 3D-графики, может
улучшить качество рендеринга, а также открывает некоторые дополнительные возможности.

## 3dfx Voodoo OpenGL Scaling

Масштабирование 3D-графики при использовании режима `Hardware OpenGL`. Работает совместно с [масштабированием, заданным в
настройках RetroArch](../../retroarch/video.md).

**Пример:** Допустим, в настройках игры вы выбрали разрешение `640x480`, в параметре `Hardware OpenGL` выставлено `2x`,
и в настройках масштабирования RetroArch тоже выставлено `2x`. При этом 3D-сцена будет рендерится в разрешении
`1280x960`, а затем итоговое изображение будет масштабироваться до `2560x1920`.

## 3dfx Voodoo Gamma Correction

Позволяет настроить яркость 3D графики при использовании режима `Hardware OpenGL`.

## Aspect Ratio Correction

Коррекция соотношения сторон. Рекомендуется включить, чтобы изображение всегда сохраняло пропорции 4:3, как на старых
[ЭЛТ](https://ru.wikipedia.org/wiki/%D0%9A%D0%B8%D0%BD%D0%B5%D1%81%D0%BA%D0%BE%D0%BF)-мониторах.

## Overscan Border Size

Добавить бордюр по краям изображения. Некоторые игры могут окрашивать бордюр в разные цвета, чтобы передать
дополнительную информацию.
