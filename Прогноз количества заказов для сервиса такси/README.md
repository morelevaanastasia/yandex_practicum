# Прогноз количества заказов для сервиса такси

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**make_scorer**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**


## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование трёх типов моделей для предсказания количества заказов такси на несколько часов вперед в течение дня с проверкой метрикой RMSE на кросс-валидации, выбрана линейная регрессия