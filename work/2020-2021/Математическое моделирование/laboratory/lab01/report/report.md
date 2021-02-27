---
# Front matter
lang: ru-RU
title: "Лабораторная работа 1"
subtitle: "Основы работы с github"
author: "Греков Максим Сергеевич"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Serif
monofont: PT Serif
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

Продемонстрировать умения работы с github, языком оформления Markdown.

## Задание

1. Создать профиль на github.
2. Загрузить SSH ключи в аккаунт github.
3. Создать локальный репозиторий с отчетами по лабораторным.
4. Создать репозиторий на github и загрузить в него отчеты.

# Выполнение лабораторной работы

Продемонстрировал профиль на github (рис. -@fig:001).

![Профиль на github](image/img001.png){ #fig:001 width=70% }

Продемонстрировал SSH ключи в аккаунте (рис. -@fig:002).

![SSH ключи](image/img002.png){ #fig:002 width=70% }

Создал локальный репозиторий, содержащий отчет по лабораторным
работам, поместил необходимые файлы (рис. -@fig:003).

![Локальный репозиторий](image/img003.png){ #fig:003 width=70% }

Создал репозиторий на github. Добавил в него локальный репозиторий.
Загрузил все файлы в репозиторий на github (рис. -@fig:004).

![Репозиторий на github](image/img004.png){ #fig:004 width=70% }

# Вывод

Продемонстрировал умения работы с github, языком оформления Markdown.