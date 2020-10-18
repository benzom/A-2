# A-2


Репозиторий представляет разработки команды А-2 для кейса MyPoint.

Рабочая среда - Jupyter Notebook - лучшее решение для проектов Data Science. Код из ноутбуков можно экспортировать в файл с расширением .py и легко имплементировать в бэкенд часть будущего сервиса

Код и все выводы можно просмотреть внутри самого гитхаба, при желании воспроизвести ячейки ноутбуков самостоятельно необходимо установить пакет jupyter  https://jupyter.org/install

## Подробнее о файлах  

> **dataset_streets.xlsx** - датасет со всеми улицами города Егорьевска. Файл используется для генерации исходных данных

> **dataset_streets_final.xlsx** - обновленный датасет с добавлением геометок для улиц

> **dataset_orders_final_new.xlsx** - финальный сгенерированый датасет с заказами

> **geodataset** - ноутбук для генерации геосета (улицы, геометки, заказы)

> Файл **clasters_drawing** принимает на вход датасет с историческими данными **for_peresekator.xlsx** по адресам доставки (в координатах широты и долготы) в конкретном регионе, кластеризованный по логистическим хабам. Необходимые поля - номер кластера, координата широты и координата долготы. После обработки данных на карту региона наносятся кластеры логистических хабов, точки адресов доставки, а так же радиус каждого отдельного хаба

> Файл **courier_selection** используется для ранжирования курьеров 

> **geo_clusters** - алгоритм кластеризации заказов двумя разными вариантами (с известным количеством кластером и с подбором количества кластеров)

> **order_predictor** - ноутбук с моделью для предсказания количества заказов на день. Создана на основе алгоритма машинного обучения типа "Случайный лес" (ансамбль решающих деревьев)

> **prediction_orders.pkl** - готовый файл с моделью для предсказывания количества заказов на день

> **lgb.pkl** - модель для ранжирования курьеров

В папке **ui** находятся изображения с интерфейсом будущей системы 