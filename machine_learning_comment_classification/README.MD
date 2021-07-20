# Машинное обучение для текстов: Классификация комментариев

## Описание проекта
Для комментариев, которые оставляют на сайте пользователи, разработать модель классификации комментариев на позитивные и негативные. Неприемлимые комментарии будут отправляться на модерацию.

## Инструменты
Pandas, Numpy, Matplotlib, SnowballStemmer, Nltk, Sklearn, TfidfVectorizer, GridSearchCV, LogisticRegression, RandomForestClassifier, Classification_report, Torch, Transformers, AutoModel, BertTokenizerFast, BERT

## Выводы
В проекте обучали несколько моделей. В процессе обучения были достигнуты следующие значения метрики качества F1- score: 

- LogisticRegression F1 - score: 0.76
- RandomForestClassifier F1 - score: 0.48
- СatBoostClassifier F1 - score: 0.76
- BERT F1 - score: 0.54

Для определения неприемлимых комментариев на сайте рекомендуется модель машинного обучения LogisticRegression. Она быстро обучается, предсказывает и имеет высокую точность.
