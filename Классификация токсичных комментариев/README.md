# Классификация токсичных комментариев 

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **nltk**
- nltk.stem.**WordNetLemmatizer**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**cross_val_score**            
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.ensemble.**GradientBoostingClassifier**
- sklearn.metrics.**f1_score**
- sklearn.metrics.**confusion_matrix**

## Вывод

Была проведена исследовательская работа по обработке текстов и обучению и выбору модели для определения токсичных комментариев по методу TF-IDF. Данные проверены на корректность разметки комментариев на позитивные и негативные. Выполнены: токенизация - разбиение текста на токены: отдельные фразы, слова, символы; лемматизация - приведение слова к начальной форме - лемме ('looks' - 'look'); исключены лишние символы и стоп-слова. Признаки обработаны TF-IDF векторизацией. Список стоп-слов загружен из библиотеки nltk. Обучены 3 модели классификации - LogisticRegression, RandomForestClassifier, GradientBoostingClassifier. Параметры подобраны кросс-валидацией с применением GridSearchCV.
Выбрана логистическая регрессия