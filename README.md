# Определение региона для разработки месторождений

Перед нами поставлена задача определить, где бурить новую скважину.

Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Нам надо построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируем возможную прибыль и риски техникой Bootstrap

Шаги для выбора локации:

В избранном регионе ищем месторождения, для каждого определяем значения признаков;
Строим модель и оценивем объём запасов;
Выбираем месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
Прибыль равна суммарной прибыли отобранных месторождений.
