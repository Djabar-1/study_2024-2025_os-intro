---
## Front matter
title: "Лабораторная работа №5"
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

Познакомиться с pass, gopass, native messaging, chezmoi. Научиться пользоваться этими утилитами, синхронизировать их с git.

# Задание

1. Установить дополнительное ПО
2. Установить и настроить pass
3. Настроить интерфейс с браузером
4. Установить и настроить chezmoi

# Выполнение лабораторной работы

## Настройка

Создал новый ключ (рис.1)

![Создание нового ключа](image/1.png){#fig:001 width=70%}

## Установка менеджера паролей

Устанавливаю pass (рис.2)

![Установка pass](image/2.png){#fig:002 width=70%}

Устанавливаю gopass (рис.3)

![Установка gopass](image/3.png){#fig:003 width=70%}

Инициализирую хранилище (рис.4)

![Инициализация хранилища](image/4.png){#fig:004 width=70%}

Создаю структуру git (рис.5)

![Создание структуры git](image/5.png){#fig:005 width=70%}

Задаю адрес репозитория на хостинге (рис.6)

![Задаю адрес репозитория на хостинге](image/6.png){#fig:006 width=70%}

## Настройка интерфейса с броузером

Устаналиваю программу, обеспечивающая интерфейс native messaging (рис.7)

![Установка программы](image/7.png){#fig:007 width=70%}

Также установка программы (рис.8)

![Установка программы](image/8.png){#fig:008 width=70%}

## Сохранение пароля

Добавляю новый пароль (рис.9)

![Новый пароль](image/9.png){#fig:009 width=70%}

Отображаю пароль для указанного имени файла (рис.10)

![Отображение пароля](image/10.png){#fig:010 width=70%}

## Дополнительное программное обеспечение

Устанавливаю дополнительное программное обеспечение (рис.11)

![Устанавливка дополнительного программного обеспечения](image/11.png){#fig:011 width=70%}

Устанавливаю шрифты (рис.12)

![Устанавливка шрифты](image/12.png){#fig:012 width=70%}

Устанавливаю бинарынй файл (рис.13)

![Устанавливка бинарынй файл](image/13.png){#fig:013 width=70%}

## Создание собственного репозитория с помощью утилит

Создаю новый репозиторий (рис.14)

![Создание нового репозитория](image/14.png){#fig:014 width=70%}

## Подключение репозитория к своей системе

Инициализирую chezmoi с моим репозиторием dotfiles (рис.15)

![Инилициализация chezmoi](image/15.png){#fig:015 width=70%}

После проверки изменений в домашнем каталоге запускаю команду (рис.16)

![Запуск команды](image/16.png){#fig:016 width=70%}


# Выводы

Познакомился с pass, gopass, native messaging, chezmoi. Научился пользоваться этими утилитами, синхронизировать их с git.



