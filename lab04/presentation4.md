---
marp: true

## Front matter
lang: ru-RU
title: Structural approach to the deep learning method
author: |
	Leonid A. Sevastianov\inst{1,3}
	\and
	Anton L. Sevastianov\inst{1}
	\and
	Edik A. Ayrjan\inst{2}
	\and
	Anna V. Korolkova\inst{1}
	\and
	Dmitry S. Kulyabov\inst{1,2}
	\and
	Imrikh Pokorny\inst{4}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
	\and
	\inst{2}LIT JINR, Dubna, Russian Federation
	\and
	\inst{3}BLTP JINR, Dubna, Russian Federation
	\and
	\inst{4}Technical University of Košice, Košice, Slovakia
date: NEC--2019, 30 September -- 4 October, 2019 Budva, Montenegro

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

**Лабораторная работа 4 **

**Работа в консоли Линукса**

Негматуллаев Бежан Шухратович



## Цель работы: Получение базовых навыков работы с консолью Линукса

---

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
