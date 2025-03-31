# Análisis de Datos de Ventas

Este proyecto consiste en la exploración y análisis de un conjunto de datos de ventas, utilizando Python y librerías como Pandas, Seaborn y Matplotlib.

## Pasos realizados:

1. **Carga y exploración de datos**  
   - Se cargó el dataset `data.csv` y se revisaron sus primeras filas.  
   - Se verificó la existencia de valores nulos y duplicados.  
   - Se analizaron los tipos de datos en cada columna.

2. **Análisis estadístico**  
   - Se calcularon medidas de tendencia central (media, mediana, moda) y dispersión (desviación estándar, rango).  
   - Se identificaron valores negativos en la columna `Quantity`, lo que podría indicar devoluciones o errores de registro.  
   - Se observó una alta variabilidad en los precios de los productos.

3. **Visualización de datos**  
   - Se generaron histogramas y boxplots para analizar la distribución de los precios.  
   - Se aplicó una escala logarítmica para visualizar mejor la dispersión de los valores.  
   - Se evidenció que la mayoría de los productos tienen precios bajos, mientras que unos pocos presentan precios elevados.

Este análisis permite entender mejor la estructura del dataset y detectar posibles errores o patrones en las ventas.
