---
## Front matter
title: "Project"
subtitle: ""
author: "Pavlova Polina"
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

Выполнить 5 этап по реализации проекта.

# Задание

Добавить с сайту все остальные элементы.

- Сделать записи для персональных проектов.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору: Языки научного программирования.

# Выполнение лабораторной работы

## Создание записи для персонального проекта.(рис.1.1-1.3)

![image](image/1.png)

Рис.1.1 Создание записи для персонального проекта

![image](image/2.png)

Рис.1.2 Создание записи для персонального проекта

![image](image/3.png)

Рис.1.3 Создание записи для персонального проекта

## Сделать пост по прошедшей неделе.(рис.1.4-1.5)

![image](image/4.png)

Рис.1.4 Создание поста по прошедшей неделе

![image](image/5.png)

Рис.1.5 Создание поста по прошедшей неделе

## Добавить пост на тему по выбору.(рис.1.6-1.7)

![image](image/6.png)

Рис.1.6 Создание поста на тему: Языки научного программирования

![image](image/7.png)

Рис.1.7 Создание поста на тему: Языки научного программирования

# Выводы

Этап №5 проекта был реализован.