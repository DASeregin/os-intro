---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №14
author: |
	Denis A. Seregin
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 2021, 05 June

## Formatting
mainfont: Cambria
romanfont: Cambria
sansfont: Cambria
monofont: Cambria
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

# Содержание

## Содержание

- Цель работы

- Задачи

- Результаты

- Вывод



# Цель работы

## Цель работы

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.


# Задачи

## Задачи

- Написать программу реализующую функции простейшего калькулятора
- С помощью утилиты splint попробуйте проанализировать коды файлов calculate.c и main.c

# Результаты

## Первая задача

В домашнем каталоге создал подкаталог ~/work/os/lab_prog. Создал в нём файлы: calculate.h, calculate.c, main.c.

Выполнил компиляцию программы посредством gcc: 

Исправил синтаксические ошибки

Создал Makefile с содержанием из указаний к лабораторной работе

Запустил отладчик GDB, загрузив в него программу для отладки

## Создание файлов и директории

![Создание файлов и директории](D:\OBS\Videos_obs\ЛР14\Screenshot_3.png){ #fig:001 width=70% }

## Компиляция программы

![Компиляция программы с помощью gcc](D:\OBS\Videos_obs\ЛР14\Screenshot_6.png){ #fig:002 width=70% }

## Отладка

![Запуск калькулятора в отладчике GDB](D:\OBS\Videos_obs\ЛР14\Screenshot_8.png){ #fig:003 width=70% }

## Результаты работы

![Работа команды run](D:\OBS\Videos_obs\ЛР14\Screenshot_9.png){ #fig:004 width=70% }

## Вторая задача

С помощью утилиты splint попробовал проанализировать коды файлов calculate.c и main.c.

## Результат работы команды

![Работа команды splint](D:\OBS\Videos_obs\ЛР14\Screenshot_10.png){ #fig:005 width=70% }

## Результат работы команды

![Работа команды splint](D:\OBS\Videos_obs\ЛР14\Screenshot_11.png){ #fig:006 width=70% }



## Вывод

В ходе лабораторной работы мне удалось приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.


## {.standout}

Спасибо за внимание!