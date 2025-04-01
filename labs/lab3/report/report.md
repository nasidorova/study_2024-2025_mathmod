---
## Front matter
title: "Отчёт по лабораторной работе 1"
subtitle: "Работа с Git"
author: "Наталья Андреевна Сидорова"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Выполнение лабораторной работы

Настроила параметры установки окончания строк, отображения unicode, создала страницу html "Hello World!", и создала репозиторий (рис. [-@fig:001]).

![Подготовка к созданию проекта](image/1.jpg){#fig:001 width=70%}

Добавила теги  (рис. [-@fig:002]).

![Код страницы](image/2.jpg){#fig:002 width=70%}

Добавила файл через файл, а не через терминал(рис. [-@fig:003]).

![Добавление комментария](image/3.jpg){#fig:003 width=70%}

Добавила файл в главную ветку(рис. [-@fig:004]).

![Добавление файла](image/4.jpg){#fig:004 width=70%}

Добавила заголовок в html файл(рис. [-@fig:005]).

![Появление заголовка](image/5.jpg){#fig:005 width=70%}

Добавила изменения в ветку(рис. [-@fig:006]).

![Добавление изменений](image/6.jpg){#fig:006 width=70%}

Просмотрела логи(рис. [-@fig:007]).

![Логи](image/7.jpg){#fig:007 width=70%}

Переключалась между версиями файла(рис. [-@fig:008]).

![Версии файла](image/8.jpg){#fig:008 width=70%}

Добавила теги к версиям файла(рис. [-@fig:009]).

![Теги файла](image/9.jpg){#fig:009 width=70%}

Добавила нежелательный комментарий(рис. [-@fig:010]).

![Комментарий в коде](image/10.jpg){#fig:010 width=70%}

Добавила нежелательный комментарий в заголовке кода(рис. [-@fig:011]).

![Нежелательный комментарий](image/11.jpg){#fig:011 width=70%}

Проиндексировала и отправила эти изменения (рис. [-@fig:012]).

![Индексация изменений](image/12.jpg){#fig:012 width=70%}

Сбрасывала буферную зону(рис. [-@fig:013]).

![Сброс буфера](image/13.jpg){#fig:013 width=70%}

Сбрасывала версию моего файла(рис. [-@fig:014]).

![Сброс изменений файла](image/14.jpg){#fig:014 width=70%}

Удалила тег(рис. [-@fig:015]).

![Удаление тега](image/15.jpg){#fig:015 width=70%}

Добавила ссылку рна себя в файле(рис. [-@fig:016]).

![Ссылка на автора](image/16.jpg){#fig:016 width=70%}

Отправила изменения на гит(рис. [-@fig:017]).

![Отправка изменений](image/17.jpg){#fig:017 width=70%}

Создала новый файл html в новом каталоге lib, который определяет размер окна(рис. [-@fig:018]).

![Новый файл](image/18.jpg){#fig:018 width=70%}

Просматривала свои каталоги в репозитории(рис. [-@fig:019]).

![Мои каталоги](image/19.jpg){#fig:019 width=70%}

Добавление стилей(рис. [-@fig:020]).

![Цвет](image/20.jpg){#fig:020 width=70%}

Просматривала файлы через хэш (рис. [-@fig:021]).

![Просмотр через хэш](image/21.jpg){#fig:021 width=70%}

Изменения второго файла(рис. [-@fig:022]).

![Добавление стиля в файл](image/22.jpg){#fig:022 width=70%}

Произошло разделение ветки(рис. [-@fig:023]).

![Разделение ветки](image/23.jpg){#fig:023 width=70%}

Объединила ветки (рис. [-@fig:024]).

![Объединение](image/24.jpg){#fig:024 width=70%}

Убрала стили из файла в одной из веток(рис. [-@fig:025]).

![Создание конфликта](image/25.jpg){#fig:025 width=70%}

Ветки разделились(рис. [-@fig:026]).

![Разделение](image/26.jpg){#fig:026 width=70%}

Конфликт веток показан в файле(рис. [-@fig:027]).

![Конфликт](image/27.jpg){#fig:027 width=70%}

Вручную убрала конфликт в файле(рис. [-@fig:028]).

![Решение конфликта](image/28.jpg){#fig:028 width=70%}

Ветки разделены, но без конфликта (рис. [-@fig:029]).

![Ветки не конфликтуют](image/29.jpg){#fig:029 width=70%}

Добавила файл README(рис. [-@fig:030]).

![Новый файл](image/30.jpg){#fig:030 width=70%}

Объединила ветки в одну(рис. [-@fig:031]).

![Соединение веток](image/31.jpg){#fig:031 width=70%}

Склонировала каталог, появилась origin ветка(рис. [-@fig:032]).

![origin ветка](image/32.jpg){#fig:032 width=70%}

Изменила файл(рис. [-@fig:033]).

![Содержимое файла](image/33.jpg){#fig:033 width=70%}

Слияние извлеченных изменений(рис. [-@fig:034]).

![слияние репозиториев](image/34.jpg){#fig:034 width=70%}

Создание чистого репозитория(рис. [-@fig:035]).

![Чистый репозиторий](image/35.jpg){#fig:035 width=70%}

изменила файл README(рис. [-@fig:036]).

![Последнее изменение файла](image/36.jpg){#fig:036 width=70%}

Извлечение общих изменений(рис. [-@fig:037]).

![Общие изменения](image/37.jpg){#fig:037 width=70%}

# Выводы

В ходе выполнения работы я приобрела навыки работы с Git.

# Список литературы{.unnumbered}

::: {#refs}
:::
