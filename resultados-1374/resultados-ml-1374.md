# Reporte de Análisis de Datos - Pandas

`Cristopher Lopez Machine Learning pandas, NC 1374`

## 1. DataFrame Convertido
```text
         Galeria  Artistas  Exposiciones_anio
0    Arte Actual        25                 12
1        Moderna        18                  8
2  Contemporánea        30                 15
3          Joven        15                  6
4    Alternativa        20                 10
5        Central        22                  9
```

## 2.1 Primeras Filas (head)
```text
       Galeria  Artistas  Exposiciones_anio
0  Arte Actual        25                 12
1      Moderna        18                  8
```

## 2.2 Últimas Filas (tail)
```text
       Galeria  Artistas  Exposiciones_anio
4  Alternativa        20                 10
5      Central        22                  9
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Galeria                str
Artistas             int64
Exposiciones_anio    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column             Non-Null Count  Dtype
---  ------             --------------  -----
 0   Galeria            6 non-null      str  
 1   Artistas           6 non-null      int64
 2   Exposiciones_anio  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Exposiciones_anio'
```text
count     6.000000
mean     10.000000
std       3.162278
min       6.000000
25%       8.250000
50%       9.500000
75%      11.500000
max      15.000000
Name: Exposiciones_anio, dtype: float64
```

## 4. Ordenar Ascendente por Exposiciones_anio
```text
         Galeria  Artistas  Exposiciones_anio
3          Joven        15                  6
1        Moderna        18                  8
5        Central        22                  9
4    Alternativa        20                 10
0    Arte Actual        25                 12
2  Contemporánea        30                 15
```

## 5. Ordenar Descendente por Artistas
```text
         Galeria  Artistas  Exposiciones_anio
2  Contemporánea        30                 15
0    Arte Actual        25                 12
5        Central        22                  9
4    Alternativa        20                 10
1        Moderna        18                  8
3          Joven        15                  6
```

`Cristopher Lopez Machine Learning pandas, NC 1374`