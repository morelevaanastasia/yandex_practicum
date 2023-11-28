# Определение стоимости автомобиля 

## Описание проекта

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторических данных необходимо разработать систему рекомендации определения рыночной стоимости автомобиля на основе его описания

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- catboost.**CatBoostRegressor**
- lightgbm
- sklearn.dummy.**DummyRegressor**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OneHotEncoder**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.metrics.**mean_squared_error**

## Общий вывод

Проведен статистический анализ, данные очищены от дубликатов, пропусков и аномалий. Выявлены важные признаки, лишние признаки удалены. Проведено кодирование категориальных признаков с помощью One-Hot Encoding для модели линейной регрессии, с помощью OrdinalEncoder для DecisionTreeRegressor, для бустинговых алгоритмов были использованы внутренние кодировщики. Обучены модели Linear Regression, DecisionTreeRegressor, CatBoostRegressor, LGBMRegressor. Выбор лучшей модели производился по скорости и среднеквадратичной ошибке RMSE
