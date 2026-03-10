## Проверка пропусков  
  
```python  
df.isnull().sum()  
df.isnull().sum() / len(df) * 100
```

## Удаление пропусков

```python
df = df.dropna()  
df = df.dropna(subset=["column"])  
df = df.dropna(thresh=5)
```

## Заполнение пропусков

```python
df["col"] = df["col"].fillna(0)
df["col"] = df["col"].fillna(df["col"].mean())
df["col"] = df["col"].fillna(df["col"].median())
df["col"] = df["col"].fillna(df["col"].mode()[0])
df["col"] = df["col"].fillna(method="ffill")
df["col"] = df["col"].fillna(method="bfill")
```