**Задача:**

Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.

Вам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.

Шаги для выбора локации:

В избранном регионе ищут месторождения, для каждого определяют значения признаков;
Строят модель и оценивают объём запасов;
Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
Прибыль равна суммарной прибыли отобранных месторождений.

**Цель:**
Поиск региона, где нефтедобыча принесет наибольшую прибыль.

**Инструменты:**
Python, Pandas, Numpy, Sklearn, Matplotlib, Bootstrap

**Выводы:**
Мне были предоставлены пробы нефти в трёх регионах.
Я исследовала 500 точек в каждом регионе, из которых с помощью машинного обучения выбрала 200 лучших для разработки.по результатам проведенного мной исследования, регион номер один имеет наименьшие риски - 0% и наименьший доверительный интервал, так же у этого региона наибольшие показатели прибыли лучших 200 месторожденияй. Еще одним фактором в пользу первого региона является лучший показатель RMSE линейной регресии - 0.89.
Я рекомендую к разработке новых скважин регион номер один - вероятность убытков по нему соотвествует поставленной задаче - меньше 2,5 %, однако, следует обратить внимание, на недодстаточность показателя среднего запаса сырья на скважине для безубыточной разработки.
