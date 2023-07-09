# Car price
---
# Задача:
Спрогнозировать цену такси на следующий час. RMSE <= 48
---
# Библиотеки:
* Random Forest Regressor
* Linear Regression
* Cat Boost Regressor
* Light GBM
---
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Cell 2   | Cell 3   |
| Row 2    | Cell 5   | Cell 6   |
| Row 3    | Cell 8   | Cell 9   |

|	                     | fit time|predict time|	RMSE|
|----------------------|------|-----|------|
| RandomForestRegressor| 49.7 s|	4.09|	1542|
| DecisionTreeRegressor|	859 ms|	29.7 ms|	1746|
| CatBoostRegressor|	40.6 s|	150 ms|	1601|
| LGBMRegressor|	6.98 s|	399 ms|	1669|
