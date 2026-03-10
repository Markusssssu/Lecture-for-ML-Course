___
# Data Visualization  
  
## Структура построения графика  
  
### Импорт  
  
```python  
import seaborn as sns  
import matplotlib.pyplot as plt
```

### Создание фигуры

```python
plt.figure(figsize=(12, 8))
```

### Построение графика

```python
sns.scatterplot(data=df, x="x", y="y")  
  
plt.title("Example Graph")  
plt.show()
```

---

## Типы графиков

### Распределение признака

- sns.histplot()
    
- sns.kdeplot()
    
- sns.boxplot()
    

### Зависимость признаков

- sns.scatterplot()
    
- sns.lineplot()
    

### Сравнение категорий

- sns.boxplot()
    
- sns.violinplot()
    
- sns.barplot()
    

### Корреляции

- sns.heatmap()
    

### Полный анализ

- sns.pairplot()
    

### Подсчет категорий

- sns.countplot()
    

### Тренды

- sns.lineplot()
