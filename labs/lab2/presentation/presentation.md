---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
subtitle: Дискреционное разграничение прав в Linux. Основные атрибуты.
author:
  - Стариков Д. А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 02 марта 2023

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

# Цели и задачи

- Получение практических навыков работы в консоли с атрибутами файлов
- Закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.

# Результаты

## Создание нового пользователя

![Создание нового пользователя.](image/image0.png){#fig:0 width=70%}

## Домашняя директория, UID и GID

![Окно входа в систему с пользователям guest.](image/image1.png){#fig:1 width=70%}

## Домашняя директория, UID и GID

![Определение домашней директории, uid и gid.](image/image2.png){#fig:2 width=70%}



## Работа с атрибутами каталогов


![Расширенные атрибуты /home и создание dir1.](image/image6.png){#fig:6 width=70%}

## Работа с атрибутами каталогов

![Права доступа и расширенные атрибуты dir1.](image/image5.png){#fig:5 width=70%}

## Работа с атрибутами каталогов

![Попытка создания файла.](image/image9.png){#fig:9 width=70%}

## Заполнение таблицы

![Проверка разрешенных действий над dir1 c правами 000.](image/image10.png){#fig:10 width=70%}

## Заполнение таблицы

![Проверка разрешенных действий над dir1 c правами 700.](image/image11.png){#fig:11 width=70%}

# Итог

- В результате выполнения лабораторной работы получены практические навыки работы в консоли с атрибутами файлов.


