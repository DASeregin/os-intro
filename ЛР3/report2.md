---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №2"
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
sansfont: cambria
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

Изучить идеологию и применение средств контроля версий.

# Задания

1. Настроить git.
2. Подключить репозиторий к github.
3. Провести первичную конфигурацию.
4. Провести конфигурацию git-flow.

# Выполнение лабораторной работы

1. Создал учётную запись на github.

2. Настроил систему контроля версий так как это описано в указаниях к лабораторной работе.

3. Создал структуру каталога лабораторных работ согласно пункту М.2.

4. Создал репозиторий на GitHub. Для примера назвал его os-intro.

   (рис. -@fig:001)

   ![Создание репозитория на github](D:\OBS\Videos_obs\ЛР2\Screenshot_1.png){ #fig:001 width=70% }

5. Рабочий каталог обозначил как laboratory и перешел в него

   (рис. -@fig:002)

   ![Переход в рабочий каталог](D:\OBS\Videos_obs\ЛР2\Screenshot_2.png){ #fig:002 width=70% }

6. Инициализировал систему git

   (рис. -@fig:003)

   ![Инициализация системы git](D:\OBS\Videos_obs\ЛР2\Screenshot_3.png){ #fig:003 width=70% }

7. Создал заготовку для файла README.md

   (рис. -@fig:004)

   ![Создание заготовки для файла README](D:\OBS\Videos_obs\ЛР2\Screenshot_4.png){ #fig:004 width=70% }

   (рис. -@fig:005)

   ![Создание заготовки для файла README](D:\OBS\Videos_obs\ЛР2\Screenshot_5.png){ #fig:005 width=70% }

8. Сделал первый коммит и выложил на github

   (рис. -@fig:006)

   ![Создание коммита](D:\OBS\Videos_obs\ЛР2\Screenshot_6.png){ #fig:006 width=70% }

9. Добавил файл лицензии

   (рис. -@fig:007)

   ![Добавление файла лицензии](D:\OBS\Videos_obs\ЛР2\Screenshot_7.png){ #fig:007 width=70% }

10. Добавил шаблон игнорируемых файлов. Просмотрел список имеющихся шаблонов

    (рис. -@fig:008)

    ![Добавление шаблона gitignore](D:\OBS\Videos_obs\ЛР2\Screenshot_8.png){ #fig:008 width=70% }

11. Затем скачал шаблон, например, для C и добавил новые файлы

    (рис. -@fig:009)

    ![Добавление шаблона для С](D:\OBS\Videos_obs\ЛР2\Screenshot_9.png){ #fig:009 width=70% }

12. Выполнил коммит

    (рис. -@fig:010)

    ![Создание заготовки для файла README](D:\OBS\Videos_obs\ЛР2\Screenshot_10.png){ #fig:010 width=70% }

13. Отправил на github

    (рис. -@fig:011)

    ![Отправка на github](D:\OBS\Videos_obs\ЛР2\Screenshot_11.png){ #fig:011 width=70% }

14. Инициализировал git-flow. Префикс для ярлыков установил в v.

    (рис. -@fig:012)

    ![Инициализация git-flow](D:\OBS\Videos_obs\ЛР2\Screenshot_12.png){ #fig:012 width=70% }

15. Проверил, что нахожусь на ветке develop

    (рис. -@fig:013)

    ![Проверка ветки](D:\OBS\Videos_obs\ЛР2\Screenshot_13.png){ #fig:013 width=70% }

16. Создал релиз с версией 1.0.0

    (рис. -@fig:014)

    ![Создание релиза с версией 1.0.0](D:\OBS\Videos_obs\ЛР2\Screenshot_14.png){ #fig:014 width=70% }

17. Записал версию

    (рис. -@fig:015)

    ![Запись версии](D:\OBS\Videos_obs\ЛР2\Screenshot_15.png){ #fig:015 width=70% }

18. Добавил в индекс

    (рис. -@fig:016)

    ![Добавление файлов](D:\OBS\Videos_obs\ЛР2\Screenshot_16.png){ #fig:016 width=70% }

    (рис. -@fig:017)

    ![Добавление коммита](D:\OBS\Videos_obs\ЛР2\Screenshot_17.png){ #fig:017 width=70% }

19. Залил релизную ветку в основную ветку

    (рис. -@fig:018)

    ![Залив релизной ветки в основную](D:\OBS\Videos_obs\ЛР2\Screenshot_18.png){ #fig:018 width=70% }

20. Отправил данные на github

    (рис. -@fig:019)

    ![Отправка на github](D:\OBS\Videos_obs\ЛР2\Screenshot_19.png){ #fig:019 width=70% }

    

21. Создал релиз на github.

    (рис. -@fig:020)

    ![Релиз](D:\OBS\Videos_obs\ЛР2\Screenshot_21.png){ #fig:020 width=70% }



# Выводы

Благодаря лабораторной работе я смог изучить идеологию и применить систему контроля версий git.

# Использованные ресурсы

https://habr.com/ru/post/125799/