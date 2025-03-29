---
## Front matter
title: "Лабораторная работа №7"
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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы

# Задание

1. Работа с каталогами.
2. Работа с командрй chmod.
3. Работа с каталогами.
4. Работа с man.



# Выполнение лабораторной работы

## Работа с каталогами

Скопировал файл и назвал его(рис. [-@fig:001]).

![Копирование файла](image/1.png){#fig:001 width=70%}

Создал директорию и переместил туда файл(рис. [-@fig:002]).

![Создание директории и перемещение файла](image/2.png){#fig:002 width=70%}

Переименовал файл(рис. [-@fig:003]).

![Переименование файла](image/3.png){#fig:003 width=70%}

Создал файл и скопировал его в каталог(рис. [-@fig:004]).

![Сощдание файла и его копирование в каталог](image/4.png){#fig:004 width=70%}

Создал каталог(рис. [-@fig:005]).

![Создание каталога](image/5.png){#fig:005 width=70%}

Переместил файлы в каталог(рис. [-@fig:006]).

![Перемещение файлов](image/6.png){#fig:006 width=70%}

Создал другой каталог и переместил его(рис. [-@fig:007]).

![Создание каталога и его перемещение](image/7.png){#fig:007 width=70%}

## Работа с командрй chmod.

Создал файл и присвоил ему выделенные права доступа(рис. [-@fig:008]).

![Создание файла и присвоение прав доступа](image/8.png){#fig:008 width=70%}

Создал файл и присвоил ему выделенные права доступа(рис. [-@fig:009]).

![Создание файла и присвоение прав доступа](image/9.png){#fig:009 width=70%}

Создал файл и присвоил ему выделенные права доступа(рис. [-@fig:010]).

![Создание файла и присвоение прав доступа](image/10.png){#fig:010 width=70%}

Создал файл и присвоил ему выделенные права доступа(рис. [-@fig:011]).

![Создание файла и присвоение прав доступа](image/11.png){#fig:011 width=70%}

## Работа с каталогами

Просмотрел содержимое файла(рис. [-@fig:012]).

![Просмотр содержимого файла](image/12.png){#fig:012 width=70%}

Скопировал файл в другой(рис. [-@fig:013]).

![Копирование файла](image/13.png){#fig:013 width=70%}

Переместил файл(рис. [-@fig:014]).

![Перемещение файла](image/14.png){#fig:014 width=70%}

Скопировал каталог(рис. [-@fig:015]).

![Копирование каталога](image/15.png){#fig:015 width=70%}

Переместил каталог и назвал его(рис. [-@fig:016]).

![Перемещение каталога](image/16.png){#fig:016 width=70%}

Лишаю права на чтение владельца файла (рис. [-@fig:017]).

![Лишение прав на чтенеие владельца файла](image/17.png){#fig:017 width=70%}

При попытке просмотреть файл мне отказывают в доступе(рис. [-@fig:018]).

![Отказ в доступе](image/18.png){#fig:018 width=70%}

При попытке скопировать файл мне отказывают в доступе((рис. [-@fig:019]).

![Отказ в доступе](image/19.png){#fig:019 width=70%}

Даю владельцу файла право на чтение(рис. [-@fig:020]).

![Возврат прав на чтение](image/20.png){#fig:020 width=70%}

Лишаю владельца каталога прав на выполнение(рис. [-@fig:021]).

![Лишение владельца каталога прав на выполнение](image/21.png){#fig:021 width=70%}

При попытке перехода в каталог мне отказывают в доступе(рис. [-@fig:022]).

![Отказ в доступе](image/22.png){#fig:022 width=70%}

Возращаю права на выполнение(рис. [-@fig:023]).

![Возврат прав на выполнение](image/23.png){#fig:023 width=70%}

Монтирую файловую систему(рис. [-@fig:024]).

![Монтирование файловой системы](image/24.png){#fig:024 width=70%}

Проверяю и восстанавливаю файловую систему(рис. [-@fig:025]).

![Проверка и восстановление файловой системы](image/25.png){#fig:025 width=70%}

Создание файловой системы(рис. [-@fig:026]).

![Создание файловой системы](image/26.png){#fig:026 width=70%}

Отправка сигналов процессам(рис. [-@fig:027]).

![Отправка сигналов процессам](image/27.png){#fig:027 width=70%}

# Выводы

В ходе работы я ознакомился с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобрел практические навыки по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы
