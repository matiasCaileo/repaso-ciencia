# Flujo Profesional de Datos - Housing Dataset

## Descripción
Proyecto de limpieza y transformación de datos del dataset de precios de casas.

## Dataset
- **Fuente:** Kaggle - Housing Prices Dataset
- **Filas originales:** 545
- **Columnas originales:** 13

## Flujo de trabajo
1. Carga y exploración del dataset
2. Codificación binaria de variables yes/no
3. One-Hot Encoding de furnishingstatus
4. Normalización con MinMaxScaler
5. Estandarización con StandardScaler
6. Detección de outliers con boxplots
7. Eliminación de outliers con método IQR
8. Feature Engineering (3 nuevas variables)
9. Guardado del dataset procesado

## Resultados
- **Filas después de limpieza:** 365
- **Columnas finales:** 18
- **Outliers eliminados:** 180

## Tecnologías usadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Kedro
