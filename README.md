Este repositorio fue creado para subir los momentos evaluativos del curso seminario para la especialización En ciencia y analítica de datos, GRUPO NUMERO 2 (G02)
Cristian Bolaños y Mateo Cabarcas

ME03:
En el notebook se detalla la preparación de los datos con sus distintas transformaciones y arreglos para entrenar y evaluar los modelos de ML 

1. Primero se deben importar las librerías
2. Se carga el dataset, el cual está almacenado de manera cruda en la carpeta "Dataset" de este mismo repositorio de github
3. Se procede a realizar la limpieza de datos (Eliminación de columnas, operaciones entre columnas, eliminación de registros duplicados, conversión de variables numéricas a categóricas y conversión de unidades)
4. Se ejecuta una revisión de las variables de entrada categóricas y numéricas así como de la variable de salida, teniendo en cuenta distribuciones, posibles correlaciones y principales estadísticos
5. Se identifican y eliminan valores atipicos. Se hace la división inicial de datos de entrenamiento tomando el 90% de los datos para entrenar y 10% para evaluar al final todos los modelos. Posteriormente se balancean los datos y se dummifican y escalan las variables pertinentes. Luego se vuelven a dividir los datos en una proporción 80-20 % para entrenar y evaluar cada modelo individualmente y se dummifica y escala
6. Finalmente se preparan los datos del dataset completo para ser usados en validación cruzada para tunning de hiperparámeteros de varios modelos a aplicar
