# Українська локалізація — Dressmaker

Фанатський переклад Dressmaker (Cozy Lives) українською. Мод — плагін BepInEx 5, що додає в гру мову
«Українська»; оригінальні файли гри не змінюються. Перекладено весь текст гри, вивіску, афішу й шапку
газети перемальовано українською.

Переклад безкоштовний і таким лишиться. Якщо він припав до душі, можна кинути монету
в скарбничку: **https://send.monobank.ua/jar/8ZddSdGUd7**

## Встановлення

Завантажте останній архів на сторінці [Releases](https://github.com/furmonenko/dressmaker-ukrainian/releases).

1. Відкрийте теку гри (Steam: правою кнопкою по грі → «Керувати» → «Переглянути локальні файли»).
2. Розпакуйте туди весь архів, щоб `winhttp.dll` і тека `BepInEx` опинилися поруч із `Dressmaker.exe`.
3. Запустіть гру й виберіть у налаштуваннях мову **«Українська»**. На українській Windows гра ввімкне її сама.
4. Перший запуск довший за звичайний: BepInEx готується. Далі гра стартує як завжди.

Steam Deck / Linux: у параметрах запуску гри впишіть `WINEDLLOVERRIDES="winhttp=n,b" %command%`.

Видалити мод: прибрати теку `BepInEx\plugins\DressmakerUkrainian`. Разом із BepInEx — також теку `BepInEx`
і файли `winhttp.dll`, `doorstop_config.ini`, `.doorstop_version`, `changelog.txt`.

Мови «Українська» немає в списку — перевірте, що `winhttp.dll` лежить поруч із `Dressmaker.exe`, а тека
`BepInEx\plugins\DressmakerUkrainian` на місці. Після оновлення гри частина текстів може лишитися
англійською до наступного випуску перекладу.

## Помилки й побажання

Одруківки, кострубаті фрази, написи, що не влізли: [Issues](https://github.com/furmonenko/dressmaker-ukrainian/issues),
бажано зі знімком екрана.

## Ліцензія

Текст перекладу — CC BY-NC-SA 4.0 ([`LICENSE.md`](LICENSE.md)). Шрифти EB Garamond, Philosopher, Marmelad,
Nunito, Literata — SIL Open Font License. BepInEx — LGPL-2.1. Файлів гри в архіві немає.

Переклад не пов’язаний із Cozy Lives. Dressmaker належить її власникам.
