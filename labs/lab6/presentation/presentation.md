---
## Front matter
lang: ru-RU
title: Лабораторная работа №6
subtitle: Мандатное разграничение прав в Linux


author:
  - Губина О. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 10 октября 2023

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

- Необходимость понимания возможножностей технологии SELinux и веб-сервера Apache.

## Объект и предмет исследования

- SELinux, Apache

## Цели и задачи

- Получить первое практическое знакомство с технологией SELinux1
- Проверить работу SELinx на практике совместно с веб-сервером Apache

## Материалы и методы

- Командная строка ОС Linux

# Процесс выполнения работы

## Режим enforcing политики targeted и запуск

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](./image/08.png){}

:::
::: {.column width="50%"}

![](image/09.png)
:::
::::::::::::::

## Статистика Apache

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/11.png)

:::
::: {.column width="50%"}

![](image/12.png)

:::
::::::::::::::

## Создание файла test.html

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/16.png)

:::
::: {.column width="50%"}

![](image/17.png)

:::
::::::::::::::

## Обращение к файлу через веб-сервер

![](image/18.png){width=80%}

## Смена контекста безропасности html файла

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/20.png)

:::
::: {.column width="50%"}

![](image/21.png)

:::
::::::::::::::

## Log-файлы

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/22.png)

:::
::: {.column width="50%"}

![](image/23.png)

:::
::::::::::::::

## Смена прослушиваемого порта и перезапуск сервера

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/24.png)

:::
::: {.column width="50%"}

![](image/25.png)

:::
::::::::::::::

## log-файл

![](image/26.png){width=80%}

## Список портов

![](image/30.png){width=80%}

## Возвращаем контекст безопасности

:::::::::::::: {.columns align=center}
::: {.column width="50%"}

![](image/32.png)

:::
::: {.column width="50%"}

![](image/33.png)

:::
::::::::::::::

## Удаление файла

![](image/35.png){width=80%}

# Результаты работы

- Получила первое практическое знакомство с технологией SELinux1
- Проверила работу SELinx на практике совместно с веб-сервером Apache.

# Вывод

Развила навыки администрирования ОС Linux. Получила первое практическое знакомство с технологией SELinux1. Проверила работу SELinx на практике совместно с веб-сервером Apache.

[def]: ttps://github.com/ovgubina