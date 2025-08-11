# Análisis de Datos de Pingüinos con Python

## Descripción del Proyecto

Este proyecto tiene como objetivo realizar un **análisis exploratorio de datos (EDA)** y visualización utilizando **Python** sobre un dataset que contiene información sobre diversas especies de pingüinos. El análisis se enfoca en las características físicas de los pingüinos, tales como la longitud del culmen, la longitud de la aleta, la masa corporal, entre otras. El dataset también incluye información sobre la especie, isla y el sexo de cada pingüino.

Este proyecto utiliza herramientas como **Pandas**, **Matplotlib**, **Seaborn** y **Scikit-learn** para realizar el análisis y visualización de los datos.

### Archivos Principales

1. **ejemplo_pinguinos.ipynb**:
   - Este archivo Jupyter Notebook contiene un ejemplo completo de análisis de datos, con los siguientes pasos:
     - Carga y limpieza de los datos.
     - Exploración de estadísticas descriptivas.
     - Visualización de datos con gráficos como histogramas, diagramas de dispersión, y más.
     - Análisis de correlación y distribución de las características de los pingüinos.
   
2. **pinguinos.csv**:
   - Un archivo CSV que contiene las observaciones de los pingüinos. Las columnas son:
     - **species**: Especie del pingüino (Adelie, Chinstrap, Gentoo).
     - **island**: Isla donde se encontró el pingüino (Torgersen, Biscoe, Dream).
     - **culmen_length_mm**: Longitud del culmen en milímetros.
     - **culmen_depth_mm**: Profundidad del culmen en milímetros.
     - **flipper_length_mm**: Longitud de la aleta en milímetros.
     - **body_mass_g**: Masa corporal en gramos.
     - **sex**: Sexo del pingüino (MALE o FEMALE).

## Características del Dataset

El dataset contiene información sobre 344 pingüinos distribuidos en tres especies: **Adelie**, **Chinstrap** y **Gentoo**. Las observaciones fueron tomadas en tres islas diferentes en la Antártida: **Torgersen**, **Biscoe** y **Dream**.

### Preprocesamiento y Limpieza de Datos

- **Valores faltantes**: El dataset contiene valores nulos en algunas columnas (como `culmen_length_mm`, `culmen_depth_mm`, etc.). El código en el notebook realiza el tratamiento de estos valores, eliminando o imputando los valores faltantes según corresponda.
- **Valores atípicos**: Se realiza una inspección de los valores atípicos en las distintas características y se decide si es necesario filtrarlos o dejarlos en el análisis.

## Requisitos

Este proyecto requiere las siguientes librerías para ejecutar el análisis:

- **Python 3.x**
- **Jupyter Notebook** para ejecutar el archivo `.ipynb`.
- Librerías de Python necesarias:
  - **Pandas**: Para la manipulación y análisis de datos.
  - **Numpy**: Para operaciones numéricas.
  - **Matplotlib**: Para la creación de gráficos.
  - **Seaborn**: Para la visualización de datos estadísticos.
  - **Scikit-learn**: Para el análisis de características y, si es necesario, realizar modelos predictivos.

Puedes instalar las dependencias utilizando el archivo `requirements.txt`:

```bash
pip install -r requirements.txt


   ```bash
   git clone https://github.com/JuandaIA05/Proyecto_IA.git
   cd Proyecto_IA

