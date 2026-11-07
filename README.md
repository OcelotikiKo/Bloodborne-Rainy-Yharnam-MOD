# Rainy Yharnam – Bloodborne Rain Mod

**Version 0.9.0** · **For Bloodborne Native** · **By OcelotikiKo**

*The night is dark, the streets are wet, and the hunt continues.*

Rainy Yharnam is an atmosphere-focused mod for **Bloodborne Native** that gives Central Yharnam a darker, rainier appearance. It combines storm clouds inspired by the Fishing Hamlet, a full moon, colder nighttime lighting and rain in selected areas, while preserving the warm glow of Yharnam's lamps.

**Links:** [GitHub repository](https://github.com/OcelotikiKo/Bloodborne-Rainy-Yharnam-MOD) · [Author's Nexus Mods profile](https://www.nexusmods.com/profile/OcelotikiKo/mods)

> **Release status:** Experimental. Rain does **not** cover all outdoor locations. The final v0.9.0 combination has passed package checks, but the combined build has **not** yet been fully verified in-game. See [Known limitations](#known-limitations).

---

## English

### Features

- **Dark, cloudy sky** – the Fishing Hamlet cloud textures replace Central Yharnam's original sky variants.
- **Full moon** – a visible, ordinary full moon against the night clouds.
- **Nighttime atmosphere** – colder directional lighting, fog and color settings, without the original warm sunlight in the tested night-lighting setup.
- **Preserved local lighting** – lamps and other local light sources retain their characteristic glow.
- **Rain in selected areas** – multiple rain-effect placements across previously tested sections of Central Yharnam.
- **Focused on visuals** – does not intentionally replace NPCs, enemies, items, story events or save files.

### Requirements

- **Bloodborne 1.09** – resources checked against **CUSA03173**.
- **Bloodborne Native** with the built-in **Mods & patches** feature. The package structure was checked against Native **1.9.7**.
- Your own game installation. The game and Bloodborne Native are **not included**.

**shadPS4 compatibility has not been tested** with this package.

### Installation

1. Close Bloodborne completely and extract the downloaded ZIP.
2. Copy the complete `Bloodborne_Yharnam_Rain_v0.9.0` folder into the `mods` folder used by Bloodborne Native. The resulting structure should look like:

   ```text
   <Bloodborne Native>/
   └── mods/
       └── Bloodborne_Yharnam_Rain_v0.9.0/
           └── dvdroot_ps4/
               └── map/
                   └── ...
   ```

3. If Native uses a custom mod directory, use that directory instead. **Do not overwrite the original game files.**
4. Run **Play Bloodborne.exe**, open **Mods & patches**, enable mod loading globally and enable **Rainy Yharnam**.
5. Disable older test builds of this mod and other mods that overwrite the same MSB, SFX, sky, texture, GPARAM or BTL resources. Use **only one** Rainy Yharnam version at a time.
6. Start the game through Native's regular Play button. Offline play is recommended.

The mod uses Native's mod overlay and does not include save files or personal configuration overrides.

### Uninstallation

Close the game, then disable Rainy Yharnam in **Mods & patches** or delete **only** its folder from Native's mods directory. Your original game files and saves do not need to be deleted or restored.

### Known limitations

- **Rain coverage is incomplete.** Some outdoor parts of Central Yharnam remain dry, including areas around the main street and bridge routes.
- The B2 bridge and M1 street variants were observed separately. Their **combined v0.9.0 package** passed static checks but has **not yet been confirmed visually in a single game session**.
- Weather consistency across all story phases, transitions and reloads has not been exhaustively verified.
- Rain behaviour under roofs and indoors is not fully verified.
- Shared `m24` assets may affect adjacent loaded areas; Cathedral Ward and Old Yharnam are **not** advertised as separately supported rainy areas.
- No new rain sound was added. The final combined build's performance has not been measured.

For an initial check, inspect the clouds, moon, lamps and absence of sunlight, then walk through the clinic-to-lamp route, the bridge and the main street. Some rain boundaries are expected.

### Package integrity

The included `manifest.json` describes **44 game resource files** with SHA-256 hashes. `SHA256SUMS.txt` may additionally cover documentation and the manifest. Files with identical contents in different sky slots are intentional story-phase replacements – **do not remove them as duplicates**.

If any packaged file, including this README, is changed after generating `SHA256SUMS.txt`, **regenerate the checksum list before distributing the ZIP**.

---

## Русский

### О моде

**Rainy Yharnam** – атмосферный мод для **Bloodborne Native**, превращающий Центральный Ярнам в более мрачный, дождливый город. Вместо оригинального неба используются тяжёлые облака из Рыбацкой деревни, на небе видна полная луна, освещение становится холоднее, а на части улиц идёт дождь. При этом сохраняется тёплый свет фонарей.

Мод не предназначен для изменения врагов, NPC, предметов, сюжетных событий или сохранений.

### Особенности

- Тёмное пасмурное небо и полная луна.
- Холодное ночное освещение без прежней солнечной засветки в проверенной конфигурации.
- Сохранённое локальное освещение фонарей.
- Дождь на нескольких проверенных участках Центрального Ярнама.
- Изменения атмосферы без намеренной переработки геймплея.

### Требования

- **Bloodborne 1.09** (ресурсы проверены на **CUSA03173**).
- **Bloodborne Native** с разделом **Mods & patches**; структура пакета сверена с Native **1.9.7**.
- Собственная установленная игра. Bloodborne и Native **не входят** в архив.

**Совместимость с shadPS4 не проверена.**

### Установка

1. Полностью закройте игру и распакуйте ZIP-архив.
2. Перенесите папку `Bloodborne_Yharnam_Rain_v0.9.0` целиком в каталог `mods` вашего Bloodborne Native. Внутри должна находиться папка `dvdroot_ps4/map/...`.
3. Если в Native указан другой каталог модов, используйте его. **Не заменяйте оригинальные файлы игры.**
4. Запустите **Play Bloodborne.exe**, откройте **Mods & patches**, включите общий переключатель модов и **Rainy Yharnam**.
5. Выключите старые тестовые версии Rainy Yharnam и другие моды, конфликтующие с MSB, SFX, текстурами неба, GPARAM или BTL.
6. Запускайте игру обычной кнопкой Native. Рекомендуется офлайн-режим.

### Как удалить

Закройте игру. Отключите мод в **Mods & patches** или удалите только папку `Bloodborne_Yharnam_Rain_v0.9.0` из каталога модов. Оригинальные файлы и сохранения трогать не нужно.

### Известные ограничения

- Дождь **не покрывает всю локацию**: на некоторых открытых участках, в том числе возле главной улицы и моста, остаются сухие зоны.
- Варианты B2 (мост) и M1 (улица) проверялись в игре по отдельности. Их объединение в v0.9.0 прошло статические проверки, но **совместный результат в игре пока не подтверждён**.
- Все сюжетные фазы, перезагрузки и переходы не были исчерпывающе проверены.
- Корректность дождя под крышами и в помещениях пока не гарантируется.
- Общие ресурсы `m24` могут затрагивать соседние загружаемые участки. Дождь в Cathedral Ward и Old Yharnam отдельно не заявлен.
- Новый звук дождя не добавлен; производительность финальной объединённой сборки не измерялась.

В `manifest.json` перечислены **44 игровых ресурса** и их хеши SHA-256. Одинаковые по содержимому файлы неба в разных слотах необходимы для замены сюжетных вариантов, удалять их не нужно. После редактирования README или других файлов пакета **обновите `SHA256SUMS.txt`** перед публикацией.

---

## Author / Автор

**Mod developer:** **OcelotikiKo**

- **GitHub:** https://github.com/OcelotikiKo/Bloodborne-Rainy-Yharnam-MOD
- **Nexus Mods:** https://www.nexusmods.com/profile/OcelotikiKo/mods

## Credits / Благодарности

- **Bloodborne**, its name, world and original game assets – **FromSoftware** and **Sony Interactive Entertainment**.
- **Bloodborne Native** – its respective developers and contributors.

This is an unofficial fan-made mod and is not affiliated with or endorsed by FromSoftware or Sony Interactive Entertainment.

*May the good blood guide your way.*
