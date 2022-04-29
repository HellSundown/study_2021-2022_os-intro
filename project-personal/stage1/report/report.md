---
## Front matter
title: "Этап проекта №1"
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

Выполнить этап №1 по реализации проекта.

# Задание

### Размещение на Github pages заготовки для персонального сайта.

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

### Hugo был предварительно установлен.

### Был скопирован шаблон в отдельный репозиторий GitHub.

### Необходимо скопировать шаблон в локальный репозиторий(рис.1.1)

![image](image/1.png)

Рис.1.1 Копирование репозитория

### Запустить hugo для проверки работы сайтаи установленной на него темы(рис.1.2)

![image](image/2.png)

Рис.1.2 Запуск hugo

### Проверить работу сайта в браузере(рис.1.5)

![image](image/3.png)

Рис.1.3 Запуск браузера с ссылкой на сайт

### Удалить верхний блок сайта с ознакомительной информацией(рис.1.4)

![image](image/4.png)

Рис.1.4 Удаление блока с ознакомительной информацией

### Создать репозиторий для возможности заходить на сайт с любого ПК(рис.1.5-1.6)

![image](image/5.png)

Рис.1.5 Вход в GitHub

![image](image/6.png)

Рис.1.6 Создание репозитория с определённым именем

### Клонировать репозиторий. Сохранить изменения.(рис.1.7)

![image](image/7.png)

Рис.1.7 Клонирование репозитория

### Подключить репозиторий. Сохранить изменения.(рис.1.8-1.13)

![image](image/8.png)

Рис.1.8 

![image](image/9.png)

Рис.1.9 Клонирование репозитория

![image](image/10.png)

Рис.1.10 Клонирование репозитория

![image](image/11.png)

Рис.1.11 Подключение репозитория (ошибка)

![image](image/12.png)

Рис.1.12 Подключение репозитория (исправление ошибки)

![image](image/13.png)

Рис.1.13 Проверка правильности подключенного репозитория
