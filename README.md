# STALKER 2 Health Regeneration Mod

Этот мод добавляет авторегенерацию здоровья для игрока в *S.T.A.L.K.E.R. 2: Heart of Chornobyl*. Здоровье восстанавливается со скоростью 10 единиц в секунду (полное восстановление за 10 секунд при максимуме 100). Мод создан KDG.

## Установка
1. Скачайте архив мода с [Releases](https://github.com/KDGOfficial/STALKER2-HealthRegenMod/releases).
2. Распакуйте содержимое в папку `Stalker2\Content\Paks\~mods\` в каталоге игры.
   - Итоговый путь должен быть: `Stalker2\Content\Paks\~mods\GameLite\GameData\Creatures\actor.cfg`.
3. Если папки `~mods` нет, создайте её вручную.
4. Запустите игру и проверьте — здоровье должно восстанавливаться автоматически после получения урона.
## Настройка
- Откройте файл `actor.cfg` в текстовом редакторе.
- Измените значение `health_restore_speed`:
  - `10.0` — восстановление за 10 секунд (по умолчанию).
  - `2.0` — медленное восстановление (50 секунд).
  - `50.0` — почти мгновенное восстановление.

## Совместимость
- Мод протестирован на версии игры от 13 марта 2025 года.
- Возможны конфликты с другими модами, изменяющими `actor.cfg`.

## Автор
Мод создан KDG.

## Лицензия
**Лицензия MIT**
Авторское право (c) 2025 KDG

Настоящим предоставляется разрешение любому лицу, получившему копию данного программного обеспечения и связанных с ним документационных файлов (далее — "Программное обеспечение"), использовать Программное обеспечение без ограничений, включая, помимо прочего, права на использование, копирование, изменение, слияние, публикацию, распространение, сублицензирование и/или продажу копий Программного обеспечения, а также разрешать лицам, которым Программное обеспечение предоставлено, делать это при соблюдении следующих условий:

Указанное выше уведомление об авторских правах и данное уведомление о разрешении должны быть включены во все копии или значительные части Программного обеспечения.

ПРОГРАММНОЕ ОБЕСПЕЧЕНИЕ ПРЕДОСТАВЛЯЕТСЯ "КАК ЕСТЬ", БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ, ЯВНЫХ ИЛИ ПОДРАЗУМЕВАЕМЫХ, ВКЛЮЧАЯ, НО НЕ ОГРАНИЧИВАЯСЬ ГАРАНТИЯМИ ТОВАРНОЙ ПРИГОДНОСТИ, ПРИГОДНОСТИ ДЛЯ ОПРЕДЕЛЁННОЙ ЦЕЛИ И ОТСУТСТВИЯ НАРУШЕНИЙ. НИ ПРИ КАКИХ ОБСТОЯТЕЛЬСТВАХ АВТОРЫ ИЛИ ПРАВООБЛАДАТЕЛИ НЕ НЕСУТ ОТВЕТСТВЕННОСТИ ЗА ЛЮБЫЕ ПРЕТЕНЗИИ, УЩЕРБ ИЛИ ИНУЮ ОТВЕТСТВЕННОСТЬ, БУДЬ ТО В РАМКАХ ДОГОВОРА, ДЕЛИКТА ИЛИ ИНОГО, ВОЗНИКАЮЩУЮ В СВЯЗИ С ПРОГРАММНЫМ ОБЕСПЕЧЕНИЕМ, ЕГО ИСПОЛЬЗОВАНИЕМ ИЛИ ИНЫМИ ДЕЙСТВИЯМИ С НИМ.
---

# STALKER 2 Health Regeneration Mod

This mod adds health regeneration for the player in *S.T.A.L.K.E.R. 2: Heart of Chornobyl*. Health regenerates at a rate of 10 units per second (full recovery in 10 seconds with a maximum of 100). Mod created by KDG.

## Installation
1. Download the mod archive from [Releases](https://github.com/KDGOfficial/STALKER2-HealthRegenMod/releases).
2. Extract the contents to the `Stalker2\Content\Paks\~mods\` folder in your game directory.
   - The final path should be: `Stalker2\Content\Paks\~mods\GameLite\GameData\Creatures\actor.cfg`.
3. If the `~mods` folder doesn’t exist, create it manually.
4. Launch the game and test — health should regenerate automatically after taking damage.

## Customization
- Open `actor.cfg` in a text editor.
- Adjust the `health_restore_speed` value:
  - `10.0` — 10 seconds to full health (default).
  - `2.0` — slow regeneration (50 seconds).
  - `50.0` — near-instant regeneration.

## Compatibility
- Tested on the game version from March 13, 2025.
- May conflict with other mods modifying `actor.cfg`.

## Author
Mod created by KDG.

## License
**MIT License**

Copyright (c) 2025 KDG

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
