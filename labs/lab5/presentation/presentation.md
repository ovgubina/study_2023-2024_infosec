---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов

author:
  - Губина О. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 06 октября 2023

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

  * Губина Ольга Вячеславовна
  * студент(-ка) уч. группы НПИбд-01-20
  * Российский университет дружбы народов
  * [1032201737@pfur.ru](mailto:1032201737@rudn.ru)
  * <https://github.com/ovgubina>

# Вводная часть

## Актуальность

- Необходимость понимания возможножностей, предоставляемых различными правами и атрибутами доступа для пользователей. 

## Объект и предмет исследования

- Применение SetUID-, SetGID- и Sticky-битов.

## Цели и задачи

- Изучить на практике действие SetUID-, SetGID- и Sticky-битов.

## Материалы и методы

- Командная строка ОС Linux

# Процесс выполнения работы

## Создание программы simpleid.c

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/02.png)

:::
::: {.column width="50%"}

![](image/03.png)
:::
::::::::::::::

## Выполнение программы simple.c  

![](image/04.png)

## Программа simpleid2.c

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/05.png)

:::
::: {.column width="50%"}

![](image/06.png)

:::
::::::::::::::

## Изменение прав доступа

![](image/07.png)
![](image/08.png)

## Выполнение программы simple2.c

![](image/09.png)

## Назначение SetGID-бита

![](image/10.png)

## Запуск программы

![](image/11.png)

## Программа readfile.c

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/12.png)

:::
::: {.column width="50%"}

![](image/13.png)

:::
::::::::::::::

## Смена прав доступа

![](image/14.png)

![](image/15.png)

## Добавление SetUID-бита

![](image/16.png)

## Попытка чтения файла readfile.c

![](image/17.png)

## Попытка чтения файла /etc/shadow

![](image/18.png)

## Проверка наличия STICKY-бита на директории tmp и создание тестового файла

![](image/19.png)

![](image/20.png)

## Попытка дозаписи и записи в файл и его удалениие

![](image/21.png){width=70%}

![](image/24.png){width=70%}

## Удаление STICKY-бита

![](image/22.png)

## Попытка дозаписи и записи в файл и его удаление

![](image/23.png)

![](image/25.png)

# Результаты работы

- Изучила на практике действие SetUID-, SetGID- и Sticky-битов.

# Вывод

Изучила механизмы изменения идентификаторов, применения SetUID- и Sticky-битов. Получила практические навыки работы в консоли с дополнительными атрибутами. Рассмотрела работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

[def]: ttps://github.com/ovgubina