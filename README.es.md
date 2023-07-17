<!-- hide -->
# Regresión lineal regularizada
<!-- endhide -->

- Comprender un dataset nuevo.
- Procesarlo aplicando un análisis exploratorio (EDA).
- Modelar los datos utilizando la regresión lineal regularizada.
- Analizar los resultados y optimizar el modelo.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instructions

### Datos sociodemográficos y de recursos de salud a nivel de condado de EE. UU. (2018-2019)

Se han recopilado datos sociodemográficos y de recursos de salud por condado en los Estados Unidos y queremos descubrir si existe alguna relación entre los recursos sanitarios y los datos sociodemográficos.

Para ello, es necesario que establezcas una variable objetivo (relacionada con la salud) para llevar a cabo el análisis.

#### Paso 1: Carga del conjunto de datos

El conjunto de datos se puede encontrar en esta carpeta de proyecto bajo el nombre `demographic_health_data.csv`. Puedes cargarlo en el código directamente desde el enlace (`https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv`) o descargarlo y añadirlo a mano en tu repositorio. En este conjunto de datos encontrarás una gran cantidad de variables, que encontrarás definidas [aquí](https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/data_dict.csv).

#### Paso 2: Realiza un EDA completo

Este segundo paso es vital para asegurar que nos quedamos con las variables estrictamente necesarias y eliminamos las que no son relevantes o no aportan información. Utiliza el Notebook de ejemplo que trabajamos y adáptalo a este caso de uso.

Asegúrate de dividir convenientemente el conjunto de datos en `train` y `test` como hemos visto en lecciones anteriores.

#### Paso 3: Construye un modelo de regresión

Comienza a resolver el problema implementando un modelo de regresión lineal y analiza los resultados. A continuación, utilizando los mismos datos y los atributos por defecto, construye un modelo Lasso y compara los resultados con la regresión lineal base.

Analiza cómo evoluciona el $R^2$ cuando el hiperparámetro del modelo Lasso cambia (puedes por ejemplo empezar a probar desde el valor 0.0 e ir aumentándolo hasta un valor de 20). Dibuja estos valores en un diagrama de líneas.

#### Paso 4: Optimiza el modelo anterior

Después de entrenar el modelo Lasso, si los resultados no son satisfactorios, optimízalo empleando alguna de las técnicas vistas anteriormente.