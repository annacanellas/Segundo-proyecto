El objetivo que se nos presentaba como analistas de real estate era crear un modelo de machine learning que predeciera el precio de las viviendas teniendo en consideración un conjunto de variables tales como el número de habitaciones, baños, plantas, vistas etc. Para poder realizar este proyecto, se nos proporcionó un dataset con 22.000 viviendas que fueron vendidas entre mayo 2014 y mayo 2015.

Para poder alcanzar dicho objetivo nos ha parecido importante analizar y, consecuentemente transformar si fuera necesario, toda la información del dataset con el fin de conseguir la mejor predicción posible. Para ello, hemos uilizado tres herramientas; SQL, power bi y phyton.

En SQL, se puede encontrar una visión general de los datos que componen el dataset. Entre ellos, numeros máximos y mínimos de las distintas variables y sus valores únicos. Nos ha servido para comprender mejor la distribución y organización las variables y la posible relación entre ellas.

En PowerBi, se encuentra una representación gráfica de varias variables para comprobar mejor la relación entre ellas y facilitar su interpretación de forma visual.

Una vez entendida toda la información se dió inicio a la última fase, phyton. En el documento se describen todas las "queries" realizadas que se podrían agrupar en tres fases: análisis, "datacleaning" y finalmente la fase de predicción del modelo.
Cabe destacar que en la segunda fase se han eliminado outliers, se ha transformado el formato de "date" en "time", y se ha estandarizado la información con el fin de mejorar la predicción de nuestro modelo. Una vez realizadas todas las fases, concluimos que el modelo lgbmr es el que mejor realiza la predicción citada al inicio; 0,895.

Por lo tanto, se entregan cuatro documentos; 2 jupyter labs (uno con las "queries de SQL" y otro con las de phyton), power bi, ppt ( con la presentación).

