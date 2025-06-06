---
## Front matter
lang: ru-RU
title: Лабораторная работа №12
subtitle: Пример моделирования простого протокола передачи данных
author:
  - Тимофеева Е. Н.
institute:
  - Российский университет дружбы народов, Москва, Россия

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Тимофеева Екатерина Николаевна
  * студентка
  * Российский университет дружбы народов
  * [1132226446@pfur.ru](1132226446@pfur.ru)
  * <https://entimofeeva.github.io/ru/>

:::
::: {.column width="30%"}



:::
::::::::::::::

## Цели и задачи

**Цель работы**

Реализовать простой протокол передачи данных в CPN Tools.

**Задание**

- Реализовать простой протокол передачи данных в CPN Tools.
- Вычислить пространство состояний, сформировать отчет о нем и построить граф.

## Выполнение лабораторной работы

![Задание деклараций](image/1.jpg){#fig:001 width=70%}

## Выполнение лабораторной работы

![Начальный граф](image/2.jpg){#fig:002 width=60%}

## Выполнение лабораторной работы

![Добавление промежуточных состояний](image/3.jpg){#fig:003 width=60%}

## Выполнение лабораторной работы

![Задание деклараций](image/4.jpg){#fig:004 width=70%}

## Выполнение лабораторной работы

![Модель простого протокола передачи данных](image/5.jpg){#fig:005 width=70%}

## Выполнение лабораторной работы

![Запуск модели простого протокола передачи данных](image/6.jpg){#fig:006 width=70%}

## Упражнение

```
 Statistics
------------------------------------------------------------------------

  State Space
     Nodes:  13341
     Arcs:   206461
     Secs:   300
     Status: Partial

  Scc Graph
     Nodes:  6975
     Arcs:   170859
     Secs:   14
```

## Упражнение

```
 Boundedness Properties
------------------------------------------------------------------------

  Best Integer Bounds
                             Upper      Lower
     Main'A 1                20         0
     Main'B 1                10         0
     Main'C 1                6          0
     Main'D 1                5          0
     Main'NextRec 1          1          1
     Main'NextSend 1         1          1
     Main'Reciever 1         1          1
     Main'SA 1               1          1
     Main'SP 1               1          1
     Main'Send 1             8          8
```

## Упражнение

![Пространство состояний для модели простого протокола передачи данных](image/7.jpg){#fig:007 width=70%}

## Выводы

В процессе выполнения данной лабораторной работы я реализовала простой протокол передачи данных в CPN Tools и проведен анализ его пространства состояний.



