# 05_project_banks - банки — анализ оттока клиентов 


## Данные

Данные о клиентах регионального банка:
- идентификатор пользователя;
- баллы кредитного скоринга;
- город;
- пол;
- возраст;
- количество баллов собственности;
- баланс на счёте;
- количество продуктов, которыми пользуется клиент;
- есть ли кредитная карта (булев тип);
- активный клиент (булев тип);
- заработная плата клиента;
- ушёл или нет (булев тип).


## Задача проекта

1. Проанализировать клиентов регионального банка и выделить сегменты клиентов, которые склонны уходить из банка.
2. Приоритизировать сегменты и сформировать рекомендации для отдела маркетинга по работе с ними.


## Сделанные выводы

В зоне наибольшего оттока оказались клиенты:

- с баллами кредитного скоринга 820-900;
- в возрасте 25-36 лет, а также в возрасте 50-61 года;
- мужчины;
- имеющие 4 балла собственности и более;
- использущие 3 и более продукта банка;
- без кредитной карты.

На основании этих данных я выделила 4 сегмента (от 500 клиентов на сегмент), в которых отток наблюдается больше, чем в среднем по банку. И сформировала рекомендации для отдела маркетинга по работе с ними.

## Навыки и инструменты
***python, tableau, pandas, seaborn, matplotlib, phik, scipy.stats, исследовательский анализ данных, проверка статистических гипотез, предобработанных данных, визуализация данных***