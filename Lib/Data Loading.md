___
# Data Loading and Initial Analysis  

___
## Загрузка данных  
  
| Метод | Описание | Пример |  
|------|----------|--------|  
| CSV | Загрузка CSV | `pd.read_csv("file.csv")` |  
  
---  
## Первичный анализ данных  
  
| Метод | Описание | Пример |  
|------|----------|--------|  
| info() | Информация о DataFrame | `df.info()` |  
| describe() | Статистика | `df.describe()` |  
| head() | Первые строки | `df.head()` |  
| tail() | Последние строки | `df.tail()` |  
| shape | Размерность | `df.shape` |  
| columns | Названия колонок | `df.columns` |  
| dtypes | Типы данных | `df.dtypes` |  
| value_counts() | Частота значений | `df["col"].value_counts()` |  
| unique() | Уникальные значения | `df["col"].unique()` |  
| nunique() | Количество уникальных | `df["col"].nunique()` |  
| kurtosis() | Эксцесс | `df.kurtosis()` |