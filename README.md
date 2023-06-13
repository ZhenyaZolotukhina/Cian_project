## Продажа квартир в Москве - анализ рынка недвижимости.

Проект выполнили: Золотухина Евгения, Рыбин Сергей, Ягжов Иван

# Описание проекта:

Исследование, определяющее рыночную стоимость объектов недвижимости и типичные параметры квартир на основании данных сайта объявлений об аренде и продаже недвижимости Циан. Рассмотрено множество признаков: район, улица, ближайшая станция метро, этаж, общее количество этажей в доме, жилая площадь, площадь кухни, количество комнат, год постройки дома, общая стоимость, стоимость за квадратный метр, автор объявления и его тип.

На основе вышеуказанных признаков исследуются: цены и влияние различных характеристик квартиры на неё;  факторы, влияющие на рынок недвижимости (такие как изменение экономической ситуации в стране, изменение денежной политики, изменение законодательства, налоговых ставок и других факторов); изменение цены за квадратный метр по районам. Планируется по имеющимся данным прогнозировать цену квартиры.

Для этого проекта были использованы:
- Python;
- Pandas;
- Numpy; 
- Matplotlib;
- Предобработка данных;
- Exploratory Data Analysis (EDA);
- Визуализация данных;
- Создание новых признаков;
- Гипотезы;
- Машинное обучение.

Для парсинга данных с сайта Циан использовался готовый парсер. Источник: https://github.com/lenarsaitov/cianparser 

## Структура репозитория:
- в папке cianparser-main лежит использованный парсер с задаными нами параметрами
- в файле cian_parsing_total.csv находятся все данные, которые мы спарсили и используются в проекте
- в файле Andan_Cian_Project.ipynb находится код Python

