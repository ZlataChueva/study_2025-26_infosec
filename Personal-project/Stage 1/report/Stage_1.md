---
## Front matter
title: "Отчёт по индивидуальному проекту. Этап 1"
subtitle: "Установка Kali Linux"
author: "Чуева Злата НБИбд-01-24"

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
fontsize: 13pt
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
mainfont: Times New Roman
romanfont: Times New Roman
sansfont: Times New Roman
monofont: Times New Roman
mathfont: Times New Roman
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
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Получение навыков по установке ОС на менеджер виртуальных машин.

# Задание

Установить дистрибутив Kali Linux.

# Выполнение лабораторной работы

Открываю приложение VirtualBox и создаю новую машину.

![Имя и ОС](image/1.png){#fig:01 width=70%}

Задаю оперативную память.

![Размер оперативной памяти](image/2.png){#fig:02 width=70%}

Задаю размер жесткого диска.

![Объем жесткого диска](image/3.png){#fig:03 width=70%}

Создаю виртуальную машину. 

![Детали](image/4.png){#fig:004 width=70%}

Запускаю систему и выбираю Graphical Install что бы начать установку. 

![Окно установки](image/5.png){#fig:05 width=70%}

Выбираю язык установки.

![Подключенный образ](image/6.png){#fig:06 width=70%}

Выбираю конфигурацию клавиатуры. 

![конфигурация клавиатуры](image/8.png){#fig:07 width=70%}

Задаю имя хоста.

![Hostname](image/10.png){#fig:09 width=70%}

Задаю имя пользователя и устанавливаю пароль. 

![Создание пользователя](image/11.png){#fig:10 width=70%}

![Имя аккаунта](image/12.png){#fig:11 width=70%}

![Установка пароля](image/13.png){#fig:12 width=70%}

Выбираю тип разделения диска. 

![Тип разделения](image/16.png){#fig:13 width=70%}

Выбираю диск для работы.

![Выбор диска](image/17.png){#fig:14 width=70%}

Выбираю схему разделения. 

![Выбор схемы](image/18.png){#fig:15 width=70%}

Завершаю выбор разделения и сохраняю настройки.

![Краткий обзор](image/19.png){#fig:16 width=70%}

![Применение настроек](image/20.png){#fig:17 width=70%}

Начинается установка базовой системы. 

![Применение настроек](image/21.png){#fig:18 width=70%}

Выбираю среду рабочего стола и инструменты.

![Применение настроек](image/22.png){#fig:19 width=70%}

Устанавливаю GRUB boot loader.

![Установка](image/25.png){#fig:20 width=70%}

Выбираю устройство для установки boot loader.

![Устройсво](image/26.png){#fig:21 width=70%}

Завершаю установку. 

![Завершение установки](image/28.png){#fig:22 width=70%}

Перезагружаю систему и захожу в систему. 

![Пользователь](image/29.png){#fig:23 width=70%}

![Рабочий стол](image/30.png){#fig:24 width=70%}



# Выводы

Получила навыки по установке ОС на менеджер виртуальных машин.
