# Car price
---
# Задача:
Построить модель для определения стоимости автомобиля. Для заказчика важны скорость обучения, качество и скорость предсказания.
---
# Библиотеки:
* Random Forest Regressor
* Decision Tree Regressor
* Cat Boost Regressor
* Light GBM Regressor
---
# Результаты:

|	                     | fit time|predict time|	RMSE|
|----------------------|------|-----|------|
| RandomForestRegressor| 49.7 s|	4.09|	1542|
| DecisionTreeRegressor|	859 ms|	29.7 ms|	1746|
| CatBoostRegressor|	40.6 s|	150 ms|	1601|
| LGBMRegressor|	6.98 s|	399 ms|	1669|
