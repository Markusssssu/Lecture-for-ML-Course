# sklearn Data Processing  
  
## Работа с пропущенными значениями  
  
```python  
from sklearn.impute import SimpleImputer, KNNImputer
```

**SimpleImputer** — простое заполнение пропусков  
**KNNImputer** — заполнение на основе ближайших соседей

---
## Масштабирование признаков

from sklearn.preprocessing import StandardScaler  
from sklearn.preprocessing import MinMaxScaler  
from sklearn.preprocessing import RobustScaler  
from sklearn.preprocessing import MaxAbsScaler

**StandardScaler**  
Стандартизация данных (mean = 0, std = 1)

**MinMaxScaler**  
Масштабирование в диапазон `[0, 1]`

**RobustScaler**  
Использует медиану и IQR, устойчив к выбросам

**MaxAbsScaler**  
Масштабирование по максимальному абсолютному значению

---

## Кодирование категориальных признаков

```python
from sklearn.preprocessing import OneHotEncoder  
from sklearn.preprocessing import LabelEncoder  
from sklearn.preprocessing import OrdinalEncoder
```

**OneHotEncoder**  
Создает бинарные признаки для каждой категории

**LabelEncoder**  
Присваивает категории числовые значения

**OrdinalEncoder**  
Кодирование категорий с порядком