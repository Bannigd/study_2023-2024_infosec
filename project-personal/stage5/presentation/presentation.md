---
## Front matter
lang: ru-RU
title: "Индивидуальный проект. Этап 5."
subtitle: "Использование Burp Suite"
author: 
author:
  - Стариков Данила Андреевич

date: 11 мая 2024

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

- Познакомиться с экосистемой Burp Suite для поиска уязвимостей веб-приложений и демонстрации возможностей злоумышленника

# Результаты

## Знакомство с интерфейсом приложения

![Окно приложения Burp Suite.](image/image1.png){#fig:1 width=70%}

## Знакомство с интерфейсом приложения

![Представление перехваченного HTTP запроса.](image/image2.png){#fig:2 width=70%}

## Знакомство с интерфейсом приложения

![Сайт открыт через приложение.](image/image3.png){#fig:3 width=70%}

## Знакомство с интерфейсом приложения

![История всех HTTP запросов.](image/image4.png){#fig:4 width=70%}


## Перехват и модификация HTTP запроса

![Тестовое приложение.](image/image5.png){#fig:5 width=70%}

## Перехват и модификация HTTP запроса

![Личный кабинет с 100 долларами на счету.](image/image6.png){#fig:6 width=70%}

## Перехват и модификация HTTP запроса

![Перехват HTTP запроса при добавлении товара в корзину.](image/image7.png){#fig:7 width=70%}

## Перехват и модификация HTTP запроса

![Запрос после изменения цены.](image/image8.png){#fig:8 width=70%}

## Перехват и модификация HTTP запроса

![Корзина с измененой ценой товара.](image/image9.png){#fig:9 width=70%}

## Перехват и модификация HTTP запроса

![Итоговый счет на аккаунте после оплаты заказа.](image/image10.png){#fig:10 width=70%}

# Итог

- В результате работы познакомились с экосистемой `Burp Suite` и продемонтсрировали ее работу при перехвате и модификации HTTP запроса.


