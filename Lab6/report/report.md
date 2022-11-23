---
# Front matter
lang: ru-RU
title: 'Отчёт'
subtitle: 'по лабораторной работе 6'
author: 'Кочетов Андрей Владимирович'

# Formatting
toc-title: 'Содержание'
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: LiberationSerif
romanfont: LiberationSerif
sansfont: LiberationSans
monofont: LiberationMono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучение программы octave

# Задание

Ознакомиться с новыми командами приложения, работа с пределами, последовательностями и рядами

# Выполнение лабораторной работы

1. Задал предел и расчитал к какому числу сходится (рис.1).

   ![рис.1. Предел](images/1.png){ #fig:001 width=60% }

2. Задал частичные суммы и отобразил на графике (рис.2).

   ![рис.2. Частичные суммы](images/2.png){ #fig:002 width=60% }

3. Рассчитал сумму ряда (рис.3).

   ![рис.3. Сумма ряда](images/3.png){ #fig:003 width=60% }

4. Вычислил интеграл (рис.4).

   ![рис.4. Интеграл](images/4.png){ #fig:004 width=60% }

5. Выполнил аппроксимирование суммами (рис.5).

   ![рис.5. Аппроксимация](images/5.png){ #fig:005 width=60% }

6. Сравнил скорость отработки разных аппроксимаций (рис.6).

   ![рис.6. Сравнение аппроксимаций](images/6.png){ #fig:006 width=60% }

# Выводы

Улучшил навыки octave.
Теперь знаю новые команды и функционал приложения.