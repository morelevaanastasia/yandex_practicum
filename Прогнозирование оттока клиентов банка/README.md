# Прогнозирование оттока клиентов Банка

## Описание проекта

Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. На основе данных из банка определить клиентов, которые могут уйти - построить модель предсказания оттока.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.dummy.**DummyClassifier**
- sklearn.metrics.**confusion_matrix**
- sklearn.metrics.**roc_auc_score**
- sklearn.metrics.**accuracy_score**
- sklearn.metrics.**recall_score**
- sklearn.metrics.**precision_score**
- sklearn.metrics.**f1_score**
- sklearn.metrics.**roc_curve**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OneHotEncoder**

## Общий вывод

Датасет очищен, признаки отмасштабированы с помощью StandardScaler и закодированы с помошью One-Hot Encoding. Применены модели LogisticRegression, RandomForestClassifier, DecisionTreeClassifier. Использованы методы борьбы с дисбалансом классов - взвешивание классов, увеличение (upsampling) и уменьшение выборки (downsampling). Для устранения дисбаланса классов, для оценки моделей использовалась матрица ошибок, ROC кривая, Accuracy, Recall, Precision, F1, ROC-AUC
