---
## Front matter
title: "Отчёт по лабораторной работе №8"
subtitle: "Модель TCP/AQM"
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

Реализовать  Модель TCP/AQM
# Задание

Реализовать Модель TCP/AQM

# Выполнение лабораторной работы

Зададим контекст в xcos
N = 1, R = 1, K = 5, 3, C = 1, W(0) = 0, 1, Q(0) = 1

![](image/2.png){ #fig:001 width=70% }


Модель TCP/AQM 
![Модель TCP/AQM ](image/1.png){ #fig:002 width=70% }

Вывод
![График](image/3.png){ #fig:003 width=70% }

Фазовый портрет 
![Фазовый портрет ](image/4.png){ #fig:004 width=70% }

Решим задачу в OpenModelica
Пограмма на OpenModelica

![Программный код](image/5.png){ #fig:005 width=70% }

Вывод
![График](image/6.png){ #fig:003 width=70% }

Фазовый портрет 
![Фазовый портрет ](image/7.png){ #fig:004 width=70% }


# Выводы

В процессе выполнения данной лабораторной реализована модель TCP/AQM