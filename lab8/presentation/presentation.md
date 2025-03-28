---
## Front matter
lang: ru-RU
title: Лабораторная Работа №8
subtitle: "Модель TCP/AQM"
author:
  - Ощепков Дмитрий Владимирович
institute:
  - Российский университет дружбы народов им. Патриса Лумумбы, Москва, Россия

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\makeatother'

## Fonts
mainfont: Arial
romanfont: Arial
sansfont: Arial
monofont: Arial
---


## Докладчик


  * Ощепков Дмитрий Владимирович 
  * НФИбд-01-22
  * Российский университет дружбы народов
  * [1132226442@pfur.ru]
  
## Цель работы

Реализовать  Модель TCP/AQM
## Задание

Реализовать Модель TCP/AQM

## Выполнение лабораторной работы

Зададим контекст в xcos
N = 1, R = 1, K = 5, 3, C = 1, W(0) = 0, 1, Q(0) = 1

![](image/2.png){ #fig:001 width=70% }


## Модель TCP/AQM 
![Модель TCP/AQM ](image/1.png){ #fig:002 width=70% }

## Вывод
![График](image/3.png){ #fig:003 width=70% }

## Фазовый портрет 
![Фазовый портрет ](image/4.png){ #fig:004 width=70% }

## Решим задачу в OpenModelica
Пограмма на OpenModelica

![Программный код](image/5.png){ #fig:005 width=70% }

## Вывод
![График](image/6.png){ #fig:006 width=70% }

## Фазовый портрет 
![Фазовый портрет ](image/7.png){ #fig:007 width=70% }


## Выводы

В процессе выполнения данной лабораторной реализована модель TCP/AQM