# Yandex.Practicum

Здесь собраны некоторые проекты выполненные во время обучения по Data Science

## CV Проекты

Название проекта | Цель и задачи | Стек
--- | --- | ---
[Определение возраста покупателей](https://github.com/HappyDari/Yandex.Practicum/blob/82f8e85ea965b4955f297e0c1469fbd10cd0a04e/Computer_Vision/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%BE%D0%B7%D1%80%D0%B0%D1%81%D1%82%D0%B0%20%D0%BF%D0%BE%D0%BA%D1%83%D0%BF%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9.ipynb) | Построить модель, которая по фотографии определит приблизительный возраст человека. Необходимо добиться значения MAE на тестовой выборке не больше 8. | Keras, Pandas, Matplotlib, Numpy |

## Классификация текста
Название проекта | Цель и задачи | Стек
--- | --- | ---
[Классификация комментариев по токсичности](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/Text_classification/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BA%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B5%D0%B2%20%D0%BF%D0%BE%20%D1%82%D0%BE%D0%BA%D1%81%D0%B8%D1%87%D0%BD%D0%BE%D1%81%D1%82%D0%B8.ipynb) | Обучить модель классифицировать комментарии на позитивные и негативные для интернет-магазина. Построить модель со значением метрики качества *F1* не меньше 0.75. | Pandas, Numpy, Transformers, Torch, Re, NLTK, Sklearn      |

## Прогнозирование временных рядов
Название проекта | Цель и задачи | Стек
--- | --- | ---
[Прогнозирование заказов такси](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/Time-series_analysis/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%B0%D0%BA%D0%B0%D0%B7%D0%BE%D0%B2%20%D1%82%D0%B0%D0%BA%D1%81%D0%B8.ipynb) | Спрогнозировать количество заказов такси на следующий час, построить модель для такого предсказания. Значение метрики *RMSE* на тестовой выборке должно быть не больше 48. | Pandas, Numpy, Matplotlib, Statsmodels, Sklearn, LightGBM |

## EDA Проекты
Название проекта | Цель и задачи | Стек
--- | --- | ---
[Определение перспективного тарифа для телеком-компании](https://github.com/HappyDari/Yandex.Practicum/blob/0f468d6aaba88785187ad4091532c4cb4e49b6b9/Statistical_DA/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%B5%D1%80%D1%81%D0%BF%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D0%B3%D0%BE%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D1%82%D0%B5%D0%BB%D0%B5%D0%BA%D0%BE%D0%BC-%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8.ipynb) | Необходимо сделать предварительный анализ тарифов и поведения клиентов на небольшой выборке и сделать вывод — какой тариф лучше подходит определенным клиентам. | Pandas, Plotly, Numpy, Matplotlib, Scipy 
[Исследование успешности компьютерных игр](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/Computer_games_DA/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%83%D1%81%D0%BF%D0%B5%D1%88%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D1%85%20%D0%B8%D0%B3%D1%80.ipynb) | Нужно выявить определяющие успешность игры закономерности. Провести исследовательский и статистический анализ исторических данных из открытых источников. | Pandas, Scipy,  Plotly.express, Plotly.offline, Plotly.graph_objs, Matplotlib
[Исследование объявлений о продаже квартир](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/EDA_project/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B5%20%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80.ipynb) | Необходимо определить рыночную стоимость объектов недвижимости. Установить параметры чтобы потом построить автоматизированную систему, которая будет отслеживать аномалии и мошенническую деятельность. | Pandas, Matplotlib, EDA
[Исследование надёжности заёмщиков](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/Preprocessing/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D0%B7%D0%B0%D0%B5%D0%BC%D1%89%D0%B8%D0%BA%D0%BE%D0%B2.ipynb) | Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга. | Pandas, nltk, EDA

## ML Проекты

Название проекта | Цель и задачи | Стек
--- | --- | ---
[Определение стоимости автомобилей](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/Car_cost_analysis/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D0%B5%D0%B9.ipynb)  | Построить модель для определения стоимости автомобиля для сервиса по продаже автомобилей. Заказчику важны качество, скорость предсказания и время обучения модели | Pandas, Matplotlib, Numpy, Sklearn.preprocessing, Sklearn.ensemble, Sklearn.metrics, Lightgbm, Sweetviz  |
[Восстановление золота из руды](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/ML_4/%D0%92%D0%BE%D1%81%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%BE%D0%BB%D0%BE%D1%82%D0%B0%20%D0%B8%D0%B7%20%D1%80%D1%83%D0%B4%D1%8B.ipynb) | Необходимо подготовить прототип модели машинного обучения для золотодобывающей компании. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. | Pandas, Sklearn.linear_model, Sklearn.preprocessing, Sklearn.metrics, Numpy, Matplotlib 
[Выбор локации для нефтяной скважины](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/ML_3/%D0%92%D1%8B%D0%B1%D0%BE%D1%80%20%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B8%20%D0%B4%D0%BB%D1%8F%20%D0%BD%D0%B5%D1%84%D1%82%D1%8F%D0%BD%D0%BE%D0%B9%20%D1%81%D0%BA%D0%B2%D0%B0%D0%B6%D0%B8%D0%BD%D1%8B.ipynb) | Необходимо провести исследоване для нефтедобывающей компании и решить, в каком из трех регионов будет выгоднее бурить новую скважину. | Pandas, Numpy, Sklearn.linear_model, Sklearn.metrics, Bootstrap
[Отток клиентов из банка](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/ML_2/%D0%9E%D1%82%D1%82%D0%BE%D0%BA%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.ipynb) | Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. | Pandas, Sklearn.linear_model, Sklearn.metrics, Sklearn.preprocessing
[Рекомендация тарифов](https://github.com/HappyDari/Yandex.Practicum/blob/09b83464e3be941ee846ad70df8b9ea5c1fc5df8/ML_1/%D0%A0%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D1%8F%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%BE%D0%B2.ipynb) | Нужно проанализировать поведение клиентов и предложить пользователям новый тариф, построить модель для задачи классификации, которая выберет подходящий тариф.  | Pandas, Sklearn.tree, Sklearn.ensemble, Sklearn.metrics



