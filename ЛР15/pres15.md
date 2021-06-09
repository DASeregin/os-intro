---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №15
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

Приобрести практические навыки работы с именованными каналами.


# Задачи

## Задачи

Изучите приведённые в тексте программы server.c и client.c. Взяв данные примеры за образец, напишите аналогичные программы, внеся следующие изменения: 

1. Работает не 1 клиент, а несколько (например, два). 
2. Клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Используйте функцию sleep() для приостановки работы клиента. 
3. Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). Используйте функцию clock() для определения времени работы сервера. Что будет в случае, если сервер завершит работу, не закрыв канал

# Результаты

## Первая задача

Я изучил приведённые в тексте программы server.c и client.c., а также common.h



## Файл common.h

![Файл common.h](D:\OBS\Videos_obs\ЛР15\Screenshot_9.png){ #fig:001 width=70% }

## Файл server.c 

![Файл server.c](D:\OBS\Videos_obs\ЛР15\Screenshot_10.png){ #fig:002 width=70% }

## Файл client.c

![Файл client.c](D:\OBS\Videos_obs\ЛР15\Screenshot_11.png){ #fig:003 width=70% }

## Вторая задача

Взяв за образец написал аналогичные программы со следующими изменениями:

1. Работает не 1 клиент, а несколько (например, два). 
2. Клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Используйте функцию sleep() для приостановки работы клиента. 
3. Сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек).

## Файл client.c

![Новый файл client.c](D:\OBS\Videos_obs\ЛР15\Screenshot_12.png){ #fig:004 width=70% }

## Файл server.c (1)

![Новый файл server.c (1)](D:\OBS\Videos_obs\ЛР15\Screenshot_13.png){ #fig:005 width=70% }

## Файл server.c (2)

![Новый файл server.c (2)](D:\OBS\Videos_obs\ЛР15\Screenshot_14.png){ #fig:006 width=70% }

## Результат работы

![Работа программы с несколькими клиентами](D:\OBS\Videos_obs\ЛР15\Screenshot_8.png){ #fig:007 width=70% }

## Вывод

Я смог приобрести практические навыки работы с именованными каналами.


## {.standout}

Спасибо за внимание!

