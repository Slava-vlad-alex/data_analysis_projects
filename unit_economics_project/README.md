# Анализ бизнес-показателей развлекательного приложения Procrastinate Pro+ 

## Данные

Имеется три файла с информацией о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- файл, который хранит лог сервера с информацией о посещениях сайта, в т.ч.:
    - уникальный идентификатор пользователя,
    - страна пользователя,
    - тип устройства пользователя,
    - идентификатор источника перехода,
    - дата и время начала сессии,
    - дата и время окончания сессии.
- файл с информацией о заказах, в т.ч.:
    - уникальный идентификатор пользователя,
    - дата и время покупки,
    - сумма заказа.
- файл с информацией о расходах на рекламу, в т.ч.:
    - дата проведения рекламной кампании,
    - идентификатор рекламного источника,
    - расходы на эту кампанию.

## Задача
Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Задача — определить причины образования убытков и дать компании рекомендации, которые помогут ей быть в "плюсе".

## Используемые библиотеки

*pandas, datetime, timedelta, matplotlib, numpy*
