____
# Дататон МФТИ DS-2022
____

## Команда “Дюжина”

### Описание датасета
Датасет представляет собой таблицу с ценами и характеристиками ноутбуков, предлагаемых на маркетплейсе Wildberries, на дату 24.12.2022, пользователям без регистрации (в режиме инкогнито) в г. Москва.

### Бизнес-цели
С помощью датасета можно предсказывать/сравнивать цены ноутбуков в зависимости от их характеристик.

### Источники данных
* https://www.wildberries.ru/catalog/elektronika/noutbuki-pereferiya/noutbuki-ultrabuki - каталог по категории "Ноутбуки и ультрабуки"
* https://www.wildberries.ru/webapi/menu/main-menu-ru-ru.json - список всех каталогов wildberries
* https://static-basket-01.wb.ru/vol0/data/main-menu-ru-ru.json - json с категориями товаров
* группа https://vk.com/@happython-parser-wildberries

### Структура репозитория
* Каталог data:
    * Ноутбуки from 10000_to_1000000.xls - перечень ноутбуков
    * wb_parsed_info.json - файл с сырыми данными из парсера
* Каталог parsing:
    * парсер
* Файл EDA_WB_LAPTOPS_V5 содержит результаты EDA-анализа и визуализацию некоторых признаков

### Авторы
Богдан Костюк, Игнат Поздеев, Анатолий Кайда, Александр Пашков, Татьяна Чернова
