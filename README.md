📈 Predicción de Ventas con Regresión Lineal

Este proyecto tiene como objetivo predecir el volumen de ventas de una tienda a partir de variables temporales y comerciales, utilizando técnicas de análisis de datos y un modelo de regresión lineal supervisado.
🧠 Objetivos

    Analizar el comportamiento de ventas en función de promociones y días festivos.

    Visualizar patrones estacionales.

    Entrenar un modelo de regresión para predecir ventas futuras.

    Evaluar la precisión del modelo.

🔧 Tecnologías y librerías utilizadas

    Python

    Pandas

    Matplotlib y Seaborn

    Scikit-learn

📊 Estructura del proyecto
1. Carga y preparación de datos

    Lectura del dataset Ventas.csv, con 365 registros correspondientes a todo el año 2022.

    Ingeniería de variables: se extrajeron columnas como año, mes, día y día de la semana a partir de la fecha.

    Se verificó que no haya valores nulos.

2. Análisis exploratorio

    Se agruparon y visualizaron las ventas según la presencia de promociones y días festivos.

    Se generó un gráfico de barras comparando las ventas bajo distintas condiciones.

3. Selección y preparación del modelo

    Se definió como variable objetivo Ventas y se seleccionaron como variables independientes las demás columnas.

    Se dividieron los datos en entrenamiento y prueba (70/30).

4. Entrenamiento y evaluación

    Se entrenó un modelo de regresión lineal (LinearRegression).

    El modelo obtuvo una puntuación de 1.0 (perfecta) en el conjunto de prueba (ideal para fines didácticos, aunque en casos reales podría implicar sobreajuste).

    Se graficó la relación entre valores reales y predichos.

📌 Resultados

    El modelo fue capaz de capturar perfectamente las relaciones entre las variables, logrando una predicción precisa del comportamiento de ventas en base a los factores analizados.

    Se observaron diferencias claras en las ventas dependiendo de si era un día festivo y si había promociones.

🎯 Conclusiones

Este proyecto demuestra cómo preparar datos de series temporales, aplicar análisis exploratorio y entrenar modelos de predicción simples. Puede ser una base útil para incorporar otros modelos más complejos o nuevas variables (como clima, eventos o comportamiento del cliente).
