<!-- hide -->
# Construye un modelo de regresion lineal
<!-- endhide -->

- Comprender un dataset nuevo.
- Procesarlo aplicando un análisis exploratorio (EDA).
- Modelar los datos utilizando la regresión lineal regularizada.
- Analizar los resultados y optimizar el modelo de regresion lineal.

## 🌱 Cómo iniciar este proyecto

1. Crea un nuevo repositorio basado en el [proyecto de Machine Learning](https://github.com/4GeeksAcademy/machine-learning-python-template) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Abre el repositorio creado recientemente en Codespace usando la [extensión del botón de Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Una vez que el VSCode del Codespace haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar el modelo de regresión lineal

Una vez que hayas terminado de resolver el caso práctico, asegúrate de confirmar tus cambios, haz push a tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones para construir el modelo de regresion lineal

### Datos socio demográficos y de recursos de salud a nivel de condado de EE. UU. (2018-2019)

Se han recopilado datos socio demográficos y de recursos de salud por condado en los Estados Unidos y queremos descubrir si existe alguna relación entre los recursos sanitarios y los datos socio demográficos.

Para ello, es necesario que establezcas una variable objetivo (relacionada con la salud) para llevar a cabo el análisis.

#### Paso 1: Carga del conjunto de datos a tu modelo

El conjunto de datos se puede encontrar en esta carpeta de proyecto bajo el nombre `demographic_health_data.csv`. Puedes cargarlo en el código directamente desde el siguiente enlace:

```text
https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv
```

O descargarlo y añadirlo a mano en tu repositorio. En este conjunto de datos encontrarás una gran cantidad de variables, que encontrarás definidas [aquí](https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/data_dict.csv).

#### Paso 2: Realiza un EDA completo

Este segundo paso es vital para asegurar que nos quedamos con las variables estrictamente necesarias y eliminamos las que no son relevantes o no aportan información. Utiliza el Notebook de ejemplo que trabajamos y adáptalo a este caso de uso.

Asegúrate de dividir convenientemente el conjunto de datos en `train` y `test` como hemos visto en lecciones anteriores.

#### Paso 3: Construye un modelo de regresión

Comienza a resolver el problema implementando un modelo de regresión lineal y analiza los resultados. A continuación, utilizando los mismos datos y los atributos por defecto, construye un modelo Lasso y compara los resultados con la regresión lineal base.

Analiza cómo evoluciona el $R^2$ cuando el hiperparámetro del modelo Lasso cambia (puedes por ejemplo empezar a probar desde el valor 0.0 e ir aumentándolo hasta un valor de 20). Dibuja estos valores en un diagrama de líneas.

#### Paso 4: Optimiza el modelo de regresion anterior

Después de entrenar el modelo Lasso, si los resultados no son satisfactorios, optimízalo empleando alguna de las técnicas vistas anteriormente.

> Nota: También incorporamos muestras de solución en `./solution.ipynb` que te sugerimos honestamente que solo uses si estás atascado por más de 30 minutos o si ya has terminado y quieres compararlo con tu enfoque.
