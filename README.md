# Избранные учебные проекты

Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии  "Специалист по Data Science".

## Описание проектов


| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Поиск изображения по текстовому описанию](image-search-by-text-description) | Демонстрационная версия поиска изображений по текстовому запросу для фотохостинга. Проект иллюстрирует владение инструментами библиотек *torch* и *torchvision* (создание и обучение моделей нейронных сетей, feature extraction, подбор гиперпараметров моделей с кроссвалидацией).| *torch, torchvision, sentence_transformers, numpy, pandas, os, re, PIL, matplotlib, sklearn*|
| [Предсказание цен на недвижимость](real-estate-value) | Создание и обучение модели линейной регрессии на данных о жилье в Калифорнии в 1990 году. Проект демонстрирует навыки работы с Big Data: чтение и исследование данных, создание моделей, предобработка данных и подбор гиперпараметров с кроссвалидацией в пайплайне.  | *pyspark, pandas, phik, matplotlib, seaborn* |
| [Предсказание температуры стали](steel-temperature) | Создание модели МО для имитации технологического процесса на металлургическом комбинате. Проект демонстрирует базовые навыки DS и Анализа данных: чтение и исследование данных, предобработка данных и создание признаков, создание и тестирование моделей, подбор гиперпараметров, анализ важности признаков. | *lightgbm, sqlalchemy, numpy, pandas, phik, shap, scipy, sklearn, matplotlib, seaborn, os, random* |
| [Определение возраста покупателей](age-estimation) | Построение модели, которая по фотографии определяет приблизительный возраст человека. Проект демонстрирует навыки работы с библиотекой *keras*: загрузка, предобработка и аугментация данных, создание и обучение моделей, transfer learning. | *keras, pandas, PIL, matplotlib* |
| [Прогнозирование заказов такси](taxi_order_forecasting) | Построение модели для прогноза количества заказов такси на следующий час. Пример работы с временными рядами от предобработки и исследовательского анализа данных до оценки работы модели. | *datetime, statsmodels, pandas, numpy, matplotlib, seaborn, lightgbm, sklearn* |
| [Анализ риска ДТП](accident_risk_analysis) | Данный проект позволяет понять, возможно ли предсказывать ДТП, опираясь на исторические данные одного из регионов. Демонстрация навыков SQL, работы с СУБД, моделями Случайного леса и Градиентного бустинга, обработкой признаков в пайплайне. | *catboost, scipy, phik, sklearn, random, pandas, numpy, matplotlib, seaborn, shap, sqlalchemy* |