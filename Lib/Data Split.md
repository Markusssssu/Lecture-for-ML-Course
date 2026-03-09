# Train/Test Split  
  
## Подключение библиотеки  
  
```python  
from sklearn.model_selection import train_test_split

## Определение target

target = "target_column"  
  
X = df.drop(target, axis=1)  
y = df[target]

## Разделение данных

X_train, X_test, y_train, y_test = train_test_split(  
    X,  
    y,  
    test_size=0.2,  
    random_state=42,  
    stratify=y  
)
  
---  
  
| Метод | Назначение | Пример |  
|------|------------|--------|  
| fit() | обучение модели | model.fit(X_train, y_train) |  
| predict() | предсказание | model.predict(X_test) |  
| predict_proba() | вероятность классов | model.predict_proba(X_test) |  
| score() | быстрая оценка | model.score(X_test, y_test) |  
| get_params() | параметры модели | model.get_params() |  
| set_params() | изменить параметры | model.set_params() |
```
