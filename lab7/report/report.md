---
## Front matter
title: "Отчёт по лабораторной работе №7"
subtitle: "Лабораторная работа 7. Модель M|M|1|∞"
author: "Ощепков Дмитрий Владимирович НФИбд-01-22"

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
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: Arial
romanfont: Arial
sansfont: Arial
monofont: Arial
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

Реализовать модель Модель M|M|1|∞

# Задание

Реализовать модель Модель M|M|1|∞ в xcos

# Выполнение лабораторной работы

Рассмотрим пример моделирования в xcos системы массового обслуживания типа
M|M|1|∞.
Зафиксируем начальные данные: λ = 0, 3, µ = 0, 35, z0 = 6.

![Суперблок, моделирующий поступление заявок](image/1.png){ #fig:001 width=70% }



![Модель «хищник–жертва» в xcos](image/2.png){ #fig:002 width=70% }


![Суперблок, моделирующий обработку заявок](image/3.png){ #fig:003 width=70% }

![Динамика размера очереди](image/4.png){ #fig:004 width=70% }

![Поступление ( — ) и обработка (– · · – ) заявок](image/5.png){ #fig:005 width=70% }


# Выводы

В процессе выполнения данной лабораторной реализована модель Модель M|M|1|∞