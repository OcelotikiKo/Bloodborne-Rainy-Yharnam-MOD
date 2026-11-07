# Bloodborne Yharnam Rain — v0.9.0

## Русский

Ночная дождливая атмосфера Центрального Ярнама для Bloodborne Native: тёмное облачное небо Fishing Hamlet, обычная полная луна, холодное ночное освещение без солнечного засвета и дождь на проверенных участках. Тёплые фонари сохранены. Мод не заменяет NPC, врагов, предметы, сюжетные события или сохранения.

### Требования

Bloodborne 1.09 (ресурсы проверены на CUSA03173) и установленный Bloodborne Native со штатным разделом **Mods & patches**. Структура пакета проверена по установленному пакету Native 1.9.7. Поддержка shadPS4 этим пакетом не проверена. Игра и Native в комплект не входят.

### Установка

1. Завершите игру обычным способом. Распакуйте ZIP.
2. Скопируйте папку `Bloodborne_Yharnam_Rain_v0.9.0` целиком в папку `mods` установленного Native. Правильный путь: `<Bloodborne Native>/mods/Bloodborne_Yharnam_Rain_v0.9.0/dvdroot_ps4/map/...`.
3. Если в Native задан другой каталог модов, используйте его вместо `mods`. Не копируйте файлы в оригинальную папку Bloodborne и не заменяйте оригиналы.
4. Откройте обычный **Play Bloodborne.exe**, затем **Mods & patches**. Включите загрузку модов и этот мод. Если общий переключатель модов выключен, простого копирования недостаточно.
5. Отключите старые тестовые сборки Yharnam Rain и другие моды, заменяющие те же MSB, SFX, небо, текстуры, GPARAM или BTL. Используйте только одну версию Yharnam Rain.
6. Запускайте игру обычной кнопкой Native. Рекомендуется офлайн-режим.

Native использует выбранные вами обычные настройки и сохранения; пакет не содержит и не подменяет их. Штатный механизм наложения подключает ресурсы без перезаписи оригиналов.

### Отключение и удаление

После выхода из игры отключите мод в **Mods & patches** либо удалите только установленную папку `Bloodborne_Yharnam_Rain_v0.9.0` из каталога модов. Следующий запуск использует исходные ресурсы. Сохранения и папку игры удалять или восстанавливать не нужно. Для отката на другую версию включайте её отдельно, без одновременного подключения этой.

### Ограничения и статус проверки

- Дождь покрывает не все открытые участки Центрального Ярнама; остаются сухие зоны.
- Ночные ресурсы сохранены побайтно. Постоянство во всех сюжетных фазах, после всех переходов и загрузок не проверено исчерпывающе.
- Общие ресурсы m24 могут влиять на соседние загружаемые участки m24. Cathedral Ward и Old Yharnam не заявлены отдельными поддерживаемыми районами дождя.
- Новый звук дождя не добавлен. Производительность финального объединения не измерялась.

`manifest.json` перечисляет 44 игровых ресурса и их SHA-256. `SHA256SUMS.txt` также проверяет документацию и манифест. Повторяющиеся по содержимому файлы в разных sky-слотах нужны для замены сюжетных вариантов; не удаляйте их как дубликаты.

## English

Night-time rain atmosphere for Central Yharnam: dark Fishing Hamlet clouds, a normal full moon, cool night lighting without sunlight, preserved warm lamps, and rain in previously tested areas. NPCs, enemies, items, story events and saves are not replaced.

### Requirements and installation

Requires your Bloodborne 1.09 installation (resource checks use CUSA03173) and Bloodborne Native with **Mods & patches**. Package layout was checked against installed Native package 1.9.7. shadPS4 compatibility is untested. Neither the game nor Native is included.

1. Exit the game normally and extract the ZIP.
2. Copy the entire `Bloodborne_Yharnam_Rain_v0.9.0` folder into Native's `mods` folder: `<Bloodborne Native>/mods/Bloodborne_Yharnam_Rain_v0.9.0/dvdroot_ps4/map/...`.
3. If Native uses a custom mods directory, use that directory instead. Do not overwrite original game files.
4. Open **Play Bloodborne.exe**, go to **Mods & patches**, enable mods globally and enable this mod.
5. Disable all previous Yharnam Rain builds and conflicting map/SFX/sky/texture/GPARAM/BTL mods. Enable only one Yharnam Rain version.
6. Launch using Native's normal Play button; offline play is recommended.

Native keeps using your selected settings and saves. This package contains no saves or configuration overrides. Native's built-in overlay preserves original game files.

### Disable or uninstall

Exit the game, then disable the mod in **Mods & patches**, or remove only this mod's installed folder. The next launch uses the originals automatically. Do not delete saves or game files. Enable an older version separately if rolling back.

### Known limitations and verification

Rain does not cover every outdoor area. Indoor/roof exclusion is not fully verified. Bridge B2 and street M1 were visually tested separately; their v0.9.0 combination has passed static checks only and has NOT yet been tested together in game. Locked night resources are byte-identical to the accepted version; every story phase, reload and transition has not been exhaustively tested. Shared m24 resources may also affect adjacent loaded m24 areas. Cathedral Ward and Old Yharnam rain are not included as supported features. No new rain audio is added; combined-build performance is unmeasured.

For the first visual test, inspect the moon, clouds, warm lamps and absence of sunlight, then walk the clinic-to-lamp route, tested bridge sections and the main street. Record rain boundaries and roof behaviour. Do not treat package validation as gameplay confirmation.

`manifest.json` lists all 44 game payload files and SHA-256 hashes. `SHA256SUMS.txt` also covers the README and manifest. Identical contents at different sky target paths are required phase overrides, not removable backups.

## Credits / Благодарности

Bloodborne and original resources: FromSoftware / Sony. Bloodborne Native: its contributors. Requires the user's own game installation.
