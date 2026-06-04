# Proyecto de Visualización de Datos: revisión de factores macroeconómicos en el marco del blanqueo de capitales.

## Descripción
Este proyecto busca desarrollar un análisis exploratorio mediante una serie de herramientas de visualización interactiva del riesgo de blanqueo de capitales a través de los datos internacionales de corrupción, desarrollo económico y características regionales.

## Variables analizadas en el estudio
De entre las variables identificadas en el estudio identificamos una serie de variables clave para el estudio tal como:

- AML Score
- CPI Score (Índice de percepción de la corrupción)
- PIB per cápita
- PIB
- Uso de Internet
- Tasa de desempleo
- Grupo de ingresos
- Región geográfica

## Preguntas analizadas
Tal y como se establece en la práctica preliminar, el proyecto pretende dar solución a las siguientes cuestiones:
1. ¿Qué países presentan los mayores niveles de riesgo AML?
2. ¿Existen diferencias regionales significativas en el riesgo AML?
3. ¿Cómo se relaciona la corrupción con el riesgo de blanqueo de capitales?
4. ¿Existe relación entre el nivel de desarrollo económico y el riesgo AML?
5. ¿Los países con mayores ingresos presentan menores niveles de riesgo AML?
6. ¿Qué variables socioeconómicas están más relacionadas con el riesgo AML?
7. ¿Es posible identificar grupos de países con características similares mediante técnicas de clustering?

## Visualizaciones realizadas
En la dinámica de las visualizaciones se han contemplado una serie de visualizaciones clave:
- Mapa mundial del riesgo AML
- Top 20 países con mayor riesgo AML
- Relación entre corrupción y AML
- Relación entre PIB per cápita y AML
- AML por grupo de ingresos
- AML por región
- Matriz de correlaciones
- Agrupamiento de países mediante PCA y K-Means

## Tecnologías utilizadas
Las tecnologías empleadas para el desarrollo de la práctica se engloban en el contexto de Pandas y Numpy dentro del idioma Python.
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
- Jupyter Notebook

## Principales resultados
Los resultados más reseñables del estudio son los siguientes:

- Existe una relación negativa moderada entre corrupción y riesgo AML.
- Los países con mayor PIB per cápita tienden a presentar menor riesgo AML.
- Europa Occidental presenta los niveles de riesgo más bajos.
- África Subsahariana presenta los niveles de riesgo más elevados.
- El análisis PCA y K-Means permite identificar perfiles diferenciados de países según sus características económicas y de gobernanza.


## Estructura de carpetas
data/
graficas/
visualizacion.py
index.html
README.md
requirements.txt
LICENSE

## Visualización web
La página web integra visualizaciones estáticas e interactivas desarrolladas en Python mediante Matplotlib, Seaborn y Plotly, permitiendo la exploración de los principales hallazgos obtenidos a partir del deataset "merged_countries_fin".

La visualización puede consultarse públicamente en:

```
https://landriax.github.io/Visualizacion_proyecto/
```

La página principal se encuentra en el archivo:
index.html

## Licencia
Realizado a través de licencia MIT License.
