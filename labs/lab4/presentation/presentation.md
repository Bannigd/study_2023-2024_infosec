---
## Front matter
lang: ru-RU
title: "Лабораторная работа №4."
subtitle: "Дискреционное разграничение прав в Linux. Расширенные атрибуты"
author: 
author:
  - Стариков Данила Андреевич

date: 30 марта 2024

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

- Получение практических навыков работы в консоли с расширенными атрибутами файлов

# Результаты


![Вывод расширенных атрибутов file1.](image/image1.png){#fig:1 width=100%}

## Попытка установки расширенного атрибута

![Попытка добавления атрибута a от guest.](image/image2.png){#fig:2 width=100%}

## Установка расширенного атрибута под root

![Успешное добавление атрибута a от root-пользователя.](image/image3.png){#fig:3 width=100%}

## Проверка доступных операций с файлом с флагом а

![Запись текста в конец file1.](image/image4.png){#fig:4 width=100%}

## Проверка доступных операций с файлом с флагом а

![Проверка доступных операций с file1 с флагом a.](image/image6.png){#fig:6 width=100%}

## Проверка доступных операций с файлом с флагом а

![Попытка установки новых прав file1 с флагом a.](image/image7.png){#fig:7 width=100%}

## Проверка доступных операций с file1 без флага a

![Проверка доступных операций с file1 без флага a.](image/image8.png){#fig:8 width=100%}

## Проверка доступных операций с file1 без флага a

![Попытка установки новых прав file1 без флага a.](image/image9.png){#fig:9 width=100%}

## Проверка доступных операций с файлом с флагом i

![Проверка доступных операций c file1 с флагом i.](image/image10.png){#fig:10 width=100%}

# Итог

- В рамках лабораторной работы получили практические навыки работы с основыми и расширенными атрибутами при разграничении доступа.


