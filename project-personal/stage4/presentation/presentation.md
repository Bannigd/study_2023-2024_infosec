---
## Front matter
lang: ru-RU
title: "Индивидуальный проект."
subtitle: "Этап 4. Использование nikto"
author: "Стариков Данила Андреевич"
institute: "Российский университет дружбы народов имени Патриса Лумумбы, Москва, Россия"
date: 19 апреля 2024

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
- Познакомиться с утилитой nikto для поиска уязвимостей веб-серверов
- Проверить ее работу на ранее установленном сервере DVWA

# Результаты
## Результаты
![Запус веб-сервера DVWA.](image/image4.png){#fig:4 width=70%}

## Результаты

![Проверка работы сервера.](image/image6.png){#fig:6 width=70%}

## Результаты

![Man-page nikto.](image/image5.png){#fig:5 width=70%}

## Результаты

![Консольный вывод программы во время работы.](image/image7.png){#fig:7 width=70%}

## Результаты

![Пример найденной уязвимости веб-сервера.](image/image8.png){#fig:8 width=70%}

## Результаты

![Итоговый отчет по тестированию веб-сервера.](image/image9.png){#fig:9 width=70%}

## Результаты

![Итоговый отчет по тестированию веб-сервера с большим числом тестов.](image/image10.png){#fig:10 width=70%}

# Итог

- В результате работы познакомились с утилитой `nikto` и проверили уязвимости веб-сервера DVWA с разными параметрами теста.
