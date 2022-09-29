# Синтаксис языка Markdown.

## Блочные элементы:

### Параграфы и разрывы строк

Чтобы создать параграф, нужно отделить строку текста одной или более пустой строкой.

### Заголовки

Чтобы создать заголовок, нужно в начале строки поставить символ (#), либо написать заголовок и на следующей строке поставить символы (=) или (-).

### Цитаты

Для обозначения цитат используется знак (>) - первый уровень цитирования, (>>) - второй уровень цитирования, (>>>) - третий уровень цитирования. Например:

> Первый уровень

>> Второй уровень

>>> Третий уровень

### Списки

Есть 2 вида списков: нумерованные и ненумерованные.

Для ненумерованных списков используются следующие символы: (*), (+) и (-). Например:

* Использован символ (*);
+ Использован символ (+);
- Использован символ (-);

Символы взаимозаменяемы.

Для нумерованных списков используются числа с точкой.

1. Элемент 1;
2. Элемент 2;
3. Элемент 3.

### Блоки кода

Для создания блока кода нужно каждую строку параграфа начинать с отступа, состоящего из 4-х пробелов, либо одного символа табуляции.

### Горизонтальые (разделительные) линии

Чтобы создать горизонтальную линию нужно поместить три или более символы (_), либо (*) на отдельной строке. Например:

Первая часть текста (разделено *)
***
Вторая часть текста (разделено _)
___
Третья часть текста

## Строчные элементы:

### Ссылки

Чтобы поставить ссылку, нужно взять URL в угловые скобки. E-mail - аналогично. Например:

[http://1234/com]

Если вставлять ссылку с анкором, то текст ссылки заключается в квадратные скобки, а адрес страницы в круглые. Например:

[Это ссылка](http://1234.com)

### Выделение теста

Чтобы текст написать жирным, нужно заключить его в (**) или (__). Например:

**Пример 1** - использованы (**)

__Пример 2__ - использованы (__)

Чтобы написать текст курсивом, нужно заключить его в (*) или (_). Например:

*Пример 1* - использованы (*)

_Пример 2_ - использованы (_)

Чтобы зачеркнуть текст, нужно заключить текст в символы (~~). Например:

~~Пример 1~~

### Кодовые фрагменты строк

Чтобы отметить фрагмент строки, содержащий код, необходимо заключить его в элементы (`)

### Изображения

Чтобы вставить изображение, нужно написать следующее: ![текст](имя изображения.jpg). Пример:

![текст](картинка.jpg)

# Команды Markdown

1. git - команда, которая берет на себя вопросы контроля версий над проектом.

2. commit - фиксация(сохранение).

3. add - добавить.

4. log - список команд (коммитов).

5. init - создаст скрытый репозиторий (папку).

6. diff - разница, отличие.

7. branch - ветка.

8. checkout - переход к коммиту.

9. branch -d имя ветки - удалить ветку.

10. log --graph - список коммитов.

# Инструкция по работе с удаленным репозиторием:

1. push - перенести все изменения в удаленный репозиторий.

2. pull - команда, которая отвечает за скачивание данных с сервера.

3. clone - клонирование удаленного репозитория.

4. remote - отображение удаленных репозиториев.

5. fork - ответвление репозитория первоисточника для его локальных изменений и создания pull request.