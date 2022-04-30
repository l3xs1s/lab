---
## Front matter
title: "Лабораторная работа 4"
subtitle: "Работа с консолью Линукса"
author: "Негматуллаев Бежан Шухратович"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Получение базовых навыков работы с консолью Линукса


# Ход работы

**1.**
Определяем полное имя нашего каталога(рис. [-@fig:001])

(images/1.jpg){ #fig:001 width=70% }

**2.**
Переходим в каталог /tmp и просматриваем его содержимое(рис. [-@fig:002])

(images/2.jpg){ #fig:002 width=70% }


**3.**
Смотрим есть ли в каталоге /var/spool подкаталог cron

(рис. [-@fig:003])

(images/3.jpg){ #fig:003 width=70% }

**4.**
Просматриваем содержимое домашнего каталога (рис.[-@fig:004;])

(images/4.jpg){ #fig:004 width=70% }

**5.**
В домашнем каталоге создаем newdir(рис. [-@fig:005;])

(images/5.jpg){ #fig:005 width=70% }

**6.**
В нем создаем подкаталог morefun, а затем удаляем его и newdir. Проверяем это(рис. [-@fig:006;])

(images/6.jpg){ #fig:006 width=70% }

**7.**
С помощью команды man узнаем какуюопцию ls нужно использовать для сортировки по
времени последнего изменения(рис. [-@fig:007;])

(images/7.jpg){ #fig:007 width=70% }

**8.**
 С помощью этой же команды узнаем что делают команды cd pwd mkdir rmdir rm.(рис. [-@fig:008;])

(images/8.jpg){ #fig:008 width=70% }

**9.**
 С помощью команды history узнаем историю введеных команд и повторно вызываем одну
из них..(рис. [-@fig:009;])

(images/9.jpg){ #fig:009 width=70% }

# Вывод

Мы научились создавать работать в консоли Линукса



