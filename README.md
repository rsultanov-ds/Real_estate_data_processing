## Подготовка данных по стоимости аренды квартир в Москве

Реализация проекта предполагает обработку / подготовку данных по стоимости и иным параметрам аренды квартир в Москве на основе заданного датасета для последующего их использования в создании модели предсказания стоимости аренды квартиры в Москве. 

Реализация проекта разбита на три этапа, выполнение которых обозначено коммитами к настоящему репозиторию (с пометкой "Release No. <>") с указанием номера релиза результатов соответствующего этапа.

Содержание этапов:

  - Этап 1: разведочный анализ данных заданного датасета.

  - Этап 2: препроцессинг, очистка данных датасета от пропусков.

  - Этап 3: подготовка итогового датасета с приведением данных в датасете в числовой формат, позволяющий использовать датасет в машинном обучении. 

Проект выполнен командой "Команда 'cmd'" в составе Александра Курчаткина, Артёма Дойникова и Руслана Султанова. 

По итогам реализации проекта был сформирован итоговый датасет в формате csv, предназначенный для использования в машинном обучении.

На финальном этапе обработки данных первоначального датасета были частично приняты и частично отвергнуты первоначальные предположения и идеи о включении тех или иных данных в итоговый датасет исходя из характера обрабатываемых данных, а также количества пропусков. Соответствующие комментарии представлены в файле preprocessing.ipynb, отражающем ход обработки данных. 

С учётом проведённой работы, команда полагает, что наиболее значимыми параметрами для определения цены аренды квартиры являются локация и общая площадь квартиры. 

В ходе обработки данных были использованы методы устранения пропусков (такие, как Complete Case Analysis, контекстуальное присвоение значений пропускам), методы обработки категориальных данных (one-hot encoding). 

Иллюстрации, характеризующие обрабатываемые данные, представлены в файле EDA.pdf.
