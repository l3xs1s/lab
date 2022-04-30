---
## Front matter
title: "Лабораторная работа №1"
subtitle: "Установка виртуальной машины Fedora"
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

Создание отчета формата md 


# Ход работы

**1.**
Вводим в коноль команду VisualBox &, создаем виртуальную машину указав место для сохранения(рис. [-@fig:001])

![создание машины](images/1.jpg){ #fig:001 width=70% }

**2.**
Устанавливаем размер виртуальной машины(рис. [-@fig:002])

(images/2.jpg){ #fig:002 width=70% }


**3.**
Ждем окончания установки и в это время создаем пользователя и администратора(рис. [-@fig:003])

(images/3.jpg){ #fig:003 width=70% }

**4.**
По окончанию установки входим в созданный аккаунт (рис.[-@fig:004;])

(images/4.jpg){ #fig:004 width=70% }

**5.**
Вводим команды данные на ТУИСЕ(рис. [-@fig:010;])

(images/5.jpg){ #fig:010 width=70% }

# Вывод

Мы научились создавать и настраивать виртуальную машину

