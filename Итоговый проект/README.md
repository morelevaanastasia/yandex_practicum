# Итоговый проект

## Описание проекта

Требуется спрогнозировать отток клиента на основании исторических данных о поведении клиентов

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **matplotlib**
- **phik**        
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**GradientBoostingClassifier**
- **catboost**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**

## Общий вывод

Проведен статистический анализ, объединение данных, обработаны пропуски, добавлены дополнительные признаки, составлена матрица корреляций phik, отобраны признаки для машинного обучения, сформирован портрет уходящего и лояльного клиента, масштабированы числовые признаки, закодированы категориальные признаки. Обучены LogisticRegression, GradientBoostingClassifier, CatBoostClassifier	с подбором параметров с помощью GridSearchCV и метрикой ROC-AUC на кросс-валидации. Проведено тестирование модели, удалось достигнуть требуемого заказчиком уровня метрики ROC-AUC
