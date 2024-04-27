---
## Front matter
lang: ru-RU
title: "Лабораторная работа №6."
subtitle: "Мандатное разграничение прав в Linux"
author: "Стариков Данила Андреевич"

date: 27 апреля 2024

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

- Развить навыки администрирования ОС Linux. 
- Получить первое практическое знакомство с технологией SELinux. 
- Проверить работу SELinx на практике совместно с веб-сервером Apache.

# Выполнение

## Выполнение

![Проверка режима работы SELinux.](image/image1.png){#fig:1 width=70%}

## Выполнение

![Проверка режима работы httpd.](image/image2.png){#fig:2 width=70%}

## Выполнение

![Список всех связанных с httpd процессов.](image/image3.png){#fig:3 width=70%}

## Выполнение

![Фрагмент справки текущих состояний httpd.](image/image4.png){#fig:4 width=50%}

## Выполнение

![Статистика по политике httpd.](image/image5.png){#fig:5 width=50%}

## Выполнение

![Информация о содержимом каталога /var/www .](image/image6.png){#fig:6 width=70%}

## Выполнение

![Информация о содержимом каталога /var/www/html .](image/image7.png){#fig:7 width=70%}

## Выполнение

![Создание файла test.html.](image/image8.png){#fig:8 width=70%}

## Выполнение

![Проверка контекста test.html.](image/image9.png){#fig:9 width=70%}

## Выполнение

![Открытие файла через веб-браузер.](image/image10.png){#fig:10 width=70%}

## Выполнение

![Изменение контекста файла test.html.](image/image12.png){#fig:12 width=70%}

## Выполнение

![Попытка открытия файла через веб-браузер.](image/image13.png){#fig:13 width=70%}

## Выполнение

![Просмотр логов веб-сервера.](image/image14.png){#fig:14 width=70%}

## Выполнение

![Ошибка при попытке открытия файла через веб-браузер.](image/image15.png){#fig:15 width=70%}

## Выполнение

![Просмотр /var/log/messages.](image/image16.png){#fig:16 width=70%}

## Выполнение

![Просмотр /var/log/httpd/error_log.](image/image17.png){#fig:17 width=70%}

## Выполнение

![Просмотр /var/log/audit/audit.log.](image/image18.png){#fig:18 width=70%}

## Выполнение

![Настройка прослушивания порта 81.](image/image19.png){#fig:19 width=70%}

## Выполнение

![Возвращение нужного контекста файлу test.html.](image/image21.png){#fig:21 width=70%}

## Выполнение

![Открытие файла через веб-браузер на порте 81.](image/image20.png){#fig:20 width=70%}

# Итог

- В рамках лабораторной работы развили навыки администрирования ОС Linux, получили первое практическое знакомство с технологией SELinux и проверили работу SELinux на практике совместно с веб-сервером Apache.


