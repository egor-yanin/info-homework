# Команда grep

## Описание

grep — это одна из наиболее часто используемых утилит в Linux. Название grep расшифровывается как Global Regular Expression Print. Эта команда предназначена для поиска строк в файлах, которые соответствуют указанному шаблону. Это мощный инструмент для поиска текста в файлах и вывода строк с нужной информацией. При этом с ее помощью можно не просто находить куски текста, но и с высокой эффективностью фильтровать вывод другой команды.

Синтаксис:
```
$ grep [опции] шаблон [<путь к файлу или папке>]
$ команда | grep [опции] шаблон
```

## Задание

### Работа с содержимым файла

1. Создайте текстовый файл text.txt, запишите в него эту поэму Шекспира:
   ```
   Music to hear, why hear'st thou music sadly?
   Sweets with sweets war not, joy delights in joy.
   Why lovest thou that which thou receivest not gladly,
   Or else receivest with pleasure thine annoy?
   If the true concord of well-tuned sounds,
   By unions married, do offend thine ear,
   They do but sweetly chide thee, who confounds
   In singleness the parts that thou shouldst bear.
   Mark how one string, sweet husband to another,
   Strikes each in each by mutual ordering,
   Resembling sire and child and happy mother
   Who all in one, one pleasing note do sing:
   Whose speechless song, being many, seeming one,
   Sings this to thee: 'thou single wilt prove none.'
   ```

2. Выведите все строки, которые содержат `sweet`;

3. Выведите все строки, которые начинаются с `S`;

4. Выведите номер строки, в которой содержится `joy`;

5. Подсчитайте, сколько раз в тексте встречается слово `thou`;

6. Выведите все строки, которые не содеражт `do`;

7. Используя регулярные выражения, выведите все строки со словами, которые начинаются и заканчиваются с `s`.

### Поиск по файловой системе

С помощью утилиты find и grep найдите все файлы формата `.jpg` в домашней папке

## Источники

1. [Команда grep в Linux](https://selectel.ru/blog/tutorials/grep-command-in-linux/)
2. [Если первого источника не хватает](https://google.com)
