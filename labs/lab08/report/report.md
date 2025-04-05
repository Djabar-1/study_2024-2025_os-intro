---
## Front matter
title: "Лабораторная работа №8"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков: по управлению процессами (и заданиям), по проверке использования диска и обслуживанию файловых систем.

# Задание

1. Вход в систему
2. Работа с файлами и каталогами
3. Запуск редактора gedit
4. Выполнение команд df и du.
5. Вывод имен всех директорий 


# Выполнение лабораторной работы

## Вход в систему

Вошел в систему под своим именем (рис. [-@fig:001]).

![Вход в систему](image/1.png){#fig:001 width=70%}

## Работа с файлами и каталогами

Записал названия файлов, содержащихся в /etc (рис. [-@fig:002]).

![Запись названия файлов в другой](image/2.png){#fig:002 width=70%}

Вывел все файлы с расширением .conf (рис. [-@fig:003]).

![Вывод файлов с расширением](image/3.png){#fig:003 width=70%}

Записал файлы выше в файл conf.txt (рис. [-@fig:004]).

![Запись файлов в другой](image/4.png){#fig:004 width=70%}

Определяю, какие файлы начинаются с символа с (рис. [-@fig:005]).

![Определение нужных файлов](image/5.png){#fig:005 width=70%}

Вывел имена файлов, начинающиеся на h (рис. [-@fig:006]).

![Вывод нужных файлов](image/6.png){#fig:006 width=70%}

Запустил процесс, который будет записывать нужные файлы в другой(рис. [-@fig:007]).

![Запуск процесса](image/7.png){#fig:007 width=70%}

Удалил файл ~/logfile (рис. [-@fig:008]).

![Удаление файла](image/8.png){#fig:008 width=70%}

## Запуск редактора gedit

Запустил редактор gedit (рис. [-@fig:009]).

![Запуск редактора](image/9.png){#fig:009 width=70%}

Определил идентификатор gedit (рис. [-@fig:010]).

![Определение идентификатора gedit](image/10.png){#fig:010 width=70%}

## Выполнение команд df и du.

Получил информацию о команде df (рис. [-@fig:011]).

![Получение информации о команде](image/11.png){#fig:011 width=70%}

Получил информацию о команде du (рис. [-@fig:012]).

![Получение информации о команде](image/12.png){#fig:012 width=70%}

Выполнил команду df(рис. [-@fig:013]).

![Выполнение команды df](image/13.png){#fig:013 width=70%}

Выполнил команду du(рис. [-@fig:014]).

![Выполнение команды du](image/14.png){#fig:014 width=70%}

## Вывод имен всех директорий 

Вывел имена всех директорий(рис. [-@fig:015]).

![Вывод имен всех директорий](image/15.png){#fig:015 width=70%}

# Выводы

В ходе работы я ознакомился с инструментами поиска файлов и фильтрации текстовых данных и приобрел практические навыки: по управлению процессами (и заданиям), по проверке использования диска и обслуживанию файловых систем.




