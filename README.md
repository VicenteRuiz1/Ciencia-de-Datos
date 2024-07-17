Primera parte:
En primer lugar, se cargan las librerías a utilizar. Luego se carga la base de datos y se visualizan las primeras filas. Por último se aprecia información acerca de los datos y un análisis descriptivo de éstos.

Segunda parte:
A continuación, se realiza análisis de componentes principales para reducir dimensionalidad, para lo cual se dejan de lado las variables "Name" y "GP", además de la variable a predecir "Target_5Yrs". Tras esto, la primera acción a realizar es la estandarización de los datos para luego obtener su matriz de correlación. Luego se realizan pruebas para determinar que sí se puede aplicar PCA. Seguido de esto, se obtiene la matriz de covarianza, los autovalores y los autovectores. A partir de lo último, so obtiene el porcentaje de varianza explicada de cada autovalor.
Se obtiene el número de componentes y la varianza explicada de cada uno (gráfico incluido). En este punto está definido que la cantidad de componentes equivale 4, se obtiene la matriz de correlación Pearson y al DataFrame de dichos componentes se le agrega la variable binaria a predecir ahora con el nombre"Target".  