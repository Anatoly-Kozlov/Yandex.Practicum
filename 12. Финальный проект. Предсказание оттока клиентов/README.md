## 12. Финальный проект. Предсказание оттока клиентов

### Сфера деятельности

Телеком

### Цель проекта  

Спрогнозировать отток клиентов из телеком компании. Построить модель со значением метрики качества ROC_AUC не меньше 0.88.

### Итоги

- Датасет подготовлен к обучению (убраны лишние колонки, закодированы категориальные переменные, числовые признаки отмасштабированы)
- Выядены ъарактерные паттерны поведения клиентов
- Обучены модели LogisticRegression, LGBMClassifier, RandomForestClassifier для решения задачи классификации. Результаты проверены на метриках AUC-ROC и accuracy
- Результаты всех моделей оказались лучше, чем у DummyClassifier
- Лучшие показатели оказались у модели LGBMClassifier: roc_auc = 0,91 , accuracy = 0,86

### Статус проекта
Закончен

### Используемый стек инструментов

- pandas
- numpy
- sklearn
- scipy
- matplotlib
- seaborn 
- lightgbm
