<!-- hide -->
# Regularized Linear Regression Project Tutorial
<!-- endhide -->

- Este conjunto de datos del proyecto tiene muchas características relacionadas con los datos sociodemográficos y de recursos de salud por condado en los Estados Unidos, justo antes de que comenzara la pandemia de Covid-19 (datos de 2018 y 2019). Fue tomado de la competencia WIDS 2022 en Kaggle.

- Queremos descubrir si existe alguna relación entre los recursos sanitarios y los datos sociodemográficos. Elije una variable objetivo (relacionada con los recursos de salud) y usa el modelo LASSO para reducir las características a las más importantes para tu objetivo.

- Encuentra los parámetros para tu regresión lineal entre tus características seleccionadas y tu objetivo elegido.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones

**Datos sociodemográficos y de recursos de salud a nivel de condado de EE. UU. (2018-2019)**

Hay un 'diccionario de datos' ([haz clic aquí para abrir](https://github.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/blob/main/Data-Dictionary.csv)) que explica el significado de cada característica. Debes seleccionar una de las características relacionadas con los recursos de salud como su variable objetivo y luego usar la regresión LASSO para descubrir qué características son las más importantes como factores para explicar su variable objetivo.

**Paso 1:**

El conjunto de datos se puede encontrar en esta carpeta de proyecto como archivo 'dataset.csv'. Te invitamos a cargarlo directamente desde el enlace (https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/dataset.csv), o para descargarlo y agregarlo a tu carpeta data/raw. En ese caso, no olvides agregar la carpeta de datos al archivo .gitignore.
¡Es hora de trabajar en ello!

**Paso 2:**

Utiliza el notebook explore.ipynb para encontrar correlaciones entre funciones o entre funciones y el objetivo elegido.

No olvides escribir tus observaciones.

> Considera escalar características antes de aplicar LASSO.

**Paso 3:**

Ahora que tienes un mejor conocimiento de los datos, aplica el modelo LASSO que ya incluye la selección de características para obtener las características más importantes que influyen en tu variable objetivo.

> No vamos a predecir nada, pero no olvides descartar todas las características relacionadas con los recursos de salud de tu conjunto de datos X (características) y define tu objetivo elegido como su 'y'.

Utiliza la regresión de mínimos cuadrados ordinarios para elegir los parámetros que minimizan el error de una función lineal.

**Paso 4:**

Usa app.py para crear tu pipeline que seleccione las funciones más importantes.

Guarda tu modelo final en la carpeta 'modelos'.

En tu archivo README escribe un breve resumen.

Solution guide: https://github.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/blob/main/solution_guide.ipynb
 
