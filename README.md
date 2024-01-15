El propósito de este código es exhibir diversos métodos para abordar un problema común en Ciencia de Datos: la predicción de variables numéricas. En este repositorio, se presentan métodos de selección de variables como Lasso, Ridge, Elastic Net, SelectKBest, Backward Selection y Forward Selection. 
Además, se incluyen modelos de regresión para predecir el precio de venta de propiedades, tales como Regresión Lineal, XGBoost, LightGBM, Random Forest y Gradient Boosting Regression y distintos metodos de limpieza de datos.

Se analizaron variables no numéricas y numéricas por separado. Las variables numéricas presentaron asimetría hacia la izquierda, lo que motivó la normalización mediante el método logarítmico en algunas de ellas. Se detectaron outliers en relación con la variable objetivo, 'Sale Price', y se eliminaron aquellos puntos que podrían
afectar negativamente al modelo.

Finalmente, se evaluó si el modelo sufría de sobreajuste mediante el cálculo del coeficiente de determinación R2 para los conjuntos de entrenamiento y prueba. Se obtuvo un R2 de 0.77 para el conjunto de entrenamiento y un R2 de 0.79 para el conjunto de prueba, lo que indica que el modelo generaliza bien y no muestra signos de
sobreajuste.

