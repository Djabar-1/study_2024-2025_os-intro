---
## Front matter
title: "Лабораторная работа № 10"
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
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором vi.
3. Выполнить упраженения, используя команды vi.


# Выполнение лабораторной работы

## Создание нового файла с использованием vi.

Создал каталог и файл и вызвал vi (рис. 1).

![Создание каталога, файла и вызывание vi](image/1.png){#fig:001 width=70%}

Ввел нужный текст в файл (рис. 2).

![Ввод текста](image/2.png){#fig:003 width=70%}

Сделал файл исполняемым (рис. 3).

![Сделал файл исполняемым](image/3.png){#fig:003 width=70%}

## Редактирование существующего файла

Заменил HELL на HELLO (рис. 4).

![Замена слова](image/4.png){#fig:004 width=70%}

Заменил LOCAL на local (рис. 5).

![Замена слова](image/5.png){#fig:005 width=70%}

Вставил новую строку в конец (рис. 6).

![Вставка новой строки](image/6.png){#fig:006 width=70%}

Отменил последнюю команду (рис. 7).

![Отмена команды](image/7.png){#fig:007 width=70%}

Записал произведенные изменения (рис. 8).

![Записал изменения](image/8.png){#fig:008 width=70%}

# Выводы

В ходе работы я познакомился с операционной системой Linux. Получил практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.



