# Выбор локации для нефтяной скважины

**Описание проекта**

Необходимо провести исследоване для нефтедобывающей компании и решить, в каком из трех регионов будет выгоднее бурить новую скважину.
Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.

**Задача**

Построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализировать возможную прибыль и риски техникой Bootstrap.

Шаги для выбора локации:

* В избранном регионе ищут месторождения, для каждого определяют значения признаков;
* Строят модель и оценивают объём запасов;
* Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
* Прибыль равна суммарной прибыли отобранных месторождений.

**План проекта**
1. Изучение данных
2. Обучение и проверка модели
3. Подготовка к расчету прибыли
4. Расчёт прибыли и рисков

**Общий вывод**

Несмотря на то, что наибольший средний запас предсказанного сырья находится в третьем регионе, 
а наименьшую среднюю ошибку показала модель первого региона, самым выгодным регионом для разработки скважин является второй регион. 
В данном регионе при разведке 500 точек и разрабоке 200 лучших из них с вероятностью 95% средняя прибыль будет самая высокая - 10 млрд 510 млн рублей. 
Риск убытков в данном регионе - 0.3%.