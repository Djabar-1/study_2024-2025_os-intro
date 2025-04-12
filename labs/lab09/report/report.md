---
## Front matter
title: "Лабораторная работа №9"
subtitle: "Операционные системы"
author: "Юсуфов Джабар Артикович"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.


# Выполнение лабораторной работы

Создаю файл text.txt и запускаю mc (рис. [-@fig:001]).

![Создание файла](image/1.png){#fig:001 width=70%}

Открыл файл с помощью встроенного редактора (рис. [-@fig:002]).

![Открытие файла](image/2.png){#fig:002 width=70%}

Вставил текст в файл из Интернета (рис. [-@fig:003]).

![Вставка текста в файл](image/3.png){#fig:003 width=70%}

Удалил строку текста (рис. [-@fig:004]).

![Удаление строки текста](image/4.png){#fig:004 width=70%}

Выделил и скопировал строку (рис. [-@fig:005]).

![Выделение и копирование текста](image/5.png){#fig:005 width=70%}

Сохранил файл (рис. [-@fig:006]).

![Сохранение файла](image/6.png){#fig:006 width=70%}

В конце и в начале файла написал некоторый текст (рис. [-@fig:007]).

![Написание доп. текста](image/7.png){#fig:007 width=70%}

Включил подсветку текста (рис. [-@fig:008]).

![Включение подсветки текста](image/8.png){#fig:008 width=70%}



# Выводы

В ходе данной работы я освоил основные возможности командной оболочки Midnight Commander и приобрел навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.




