---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №15"
author: "Серегин Денис Алексеевич"

# Formatting
toc-title: "Содержание"
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
mainfont: Cambria
romanfont: Cambria
sansfont: Cambria
monofont: Cambria
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

Приобрести практические навыки работы с именованными каналами.

# Задания

Изучите приведённые в тексте программы server.c и client.c. Взяв данные примеры за образец, напишите аналогичные программы, внеся следующие изменения: 

1. Работает не 1 клиент, а несколько (например, два). 
2. Клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Используйте функцию sleep() для приостановки работы клиента. 
3. Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). Используйте функцию clock() для определения времени работы сервера. Что будет в случае, если сервер завершит работу, не закрыв канал?


# Выполнение лабораторной работы

1. Я изучил приведённые в тексте программы server.c и client.c., а также common.h

   (рис 1. -@fig:001)

   ![Файл common.h](D:\OBS\Videos_obs\ЛР15\Screenshot_9.png){ #fig:001 width=70% }

   

   (рис 2. -@fig:002)

   ![Файл server.c](D:\OBS\Videos_obs\ЛР15\Screenshot_10.png){ #fig:002 width=70% }

(рис 3. -@fig:003)

![Файл client.c](D:\OBS\Videos_obs\ЛР15\Screenshot_11.png){ #fig:003 width=70% }

2.  Взяв за образец примеры, написал аналогичные программы, внеся следующие изменения:

   1. Работает не 1 клиент, а несколько (например, два). 

   2. Клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Используйте функцию sleep() для приостановки работы клиента. 

   3. Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). 

      (рис 4. -@fig:004)

      ![Новый файл client.c](D:\OBS\Videos_obs\ЛР15\Screenshot_12.png){ #fig:004 width=70% }

      (рис 5. -@fig:005)

      ![Новый файл server.c (1)](D:\OBS\Videos_obs\ЛР15\Screenshot_13.png){ #fig:005 width=70% }

      (рис 6. -@fig:006)

      ![Новый файл server.c (2)](D:\OBS\Videos_obs\ЛР15\Screenshot_14.png){ #fig:006 width=70% }

(рис 7. -@fig:007)

![Работа программы с несколькими клиентами](D:\OBS\Videos_obs\ЛР15\Screenshot_8.png){ #fig:007 width=70% }

# Вывод

Я смог приобрести практические навыки работы с именованными каналами.

# Использованные ресурсы

https://www.opennet.ru/docs/RUS/linux_parallel/node17.html