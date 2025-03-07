---
## Front matter
title: "Отчет по лабораторной работе №1 "
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

1. Создание виртуальной машины
2. Установка операционной системы 
3. Работа с операционной системой после установки
4. Установка программного обеспечения для создания документации
5. Дополнительные задания


# Выполнение лабораторной работы

## Создание виртуальной машины 

Открываю VirtualBox
![](image/1.png)

Создаю виртуальную машину в VirtualBox
![](image/2.png)

Изменяяю размер основной памяти на 4096 МБ
![](image/3.png)

Изменяяю размер памяти жесткого диска на 80 ГБ
![](image/4.png)

Конфигурация виртуальной машины
![](image/5.png)

Меняю видеопамять на 128 МБ
![](image/6.png)

## Установка операционной системы 

Запустил виртуальную машину
![](image/7.png)

Вижу интерфейс начальной конфигурации. Нажимаю Enter для создания конфигурации по умолчанию, далее нажимаю Enter, чтобы выбрать в качестве модификатора клавишу Win
![](image/8.png)

Запускаю Терминал нажатием клавиш Win+Enter и запускаю liveinst
![](image/9.png)

Выбираю язык, который буду использовать в процессе установки
![](image/10.png)

Проверяю раскладку на русском и английском языках
![](image/11.png)

Устанавливаю дату и время
![](image/12.png)

Выбираю место для установки
![](image/13.png)

Устанавливаю имя узла
![](image/14.png)

Создаю аккаунт администратора и создаю пароль для супер-пользователя
![](image/15.png)

Создаю пользователя, добавляю административные привелегии для этой учетной записи, чтобы я мог свободно выолнять команды как супер-пользователь
![](image/16.png)

Установил операционную систему
![](image/17.png)

## Работа с операционной системой после установки

В терминале устанавливаю программы дя удобства работы в консоли: tmux для открытия нескольких "вкладок" в одном терминале, mc в качестве файлового менеджера в терминале
![](image/18.png)

Перемещаюсь в директорию /etc/selinux, открываю md, ищу нужный файл
![](image/19.png)

Изменяю открытый файл: SELINUX=enforcing меняю на значение SELINUX=permissive
![](image/20.png)

Устанавливаю dkms
![](image/21.png)

Подмантировал и запустил media
![](image/22.png)

## Установка программного обеспечения для создания документации

Устанавливаю pandoc
![](image/23.png)

Устанавливаю texlive, но не полностью 
![](image/24.png)

Установил texlive до конца 
![](image/25.png)

## Дополнительные задания

Узнаю версию ядра Linux
![](image/27.png)

Узнаю частоту процессора
![](image/28.png)

Узнаю модель процессора
![](image/29.png)

Узнаю объем доступной оперативной памяти
![](image/30.png)

Узнаю тип обнаруженного гипервизора
![](image/31.png)

Узнаю тип файловой системы корневого раздела
![](image/32.png)

Узнаю последовательность монтирования файловых систем
![](image/33.png)


# Выводы

В ходе данной лабораторной работы я приобрел практические навыки установки операционной систсемы, а также настройки необходимых для дальнейшей работы сервисов 

# Библиография

::: {#refs}
1. Dash, P. Getting Started with Oracle VM VirtualBox / P. Dash. – Packt Publishing Ltd, 2013. – 86 сс.
2. Colvin, H. VirtualBox: An Ultimate Guide Book on Virtualization with VirtualBox. VirtualBox / H. Colvin. – CreateSpace Independent Publishing Platform, 2015. – 70 сс.
3. Vugt, S. van. Red Hat RHCSA/RHCE 7 cert guide : Red Hat Enterprise Linux 7 (EX200 and EX300) : Certification Guide. Red Hat RHCSA/RHCE 7 cert guide / S. van Vugt. – Pearson IT Certification, 2016. – 1008 сс.
4. Робачевский, А. Операционная система UNIX / А. Робачевский, С. Немнюгин, О. Стесик. – 2-е изд. – Санкт-Петербург : БХВ-Петербург, 2010. – 656 сс.
5. Немет, Э. Unix и Linux: руководство системного администратора. Unix и Linux / Э. Немет, Г. Снайдер, Т.Р. Хейн, Б. Уэйли. – 4-е изд. – Вильямс, 2014. – 1312 сс.
6. Колисниченко, Д.Н. Самоучитель системного администратора Linux : Системный администратор / Д.Н. Колисниченко. – Санкт-Петербург : БХВ-Петербург, 2011. – 544 сс.
7. Robbins, A. Bash Pocket Reference / A. Robbins. – O’Reilly Media, 2016. – 156 сс.
:::


