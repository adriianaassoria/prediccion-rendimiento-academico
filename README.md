# Predicción temprana del rendimiento académico

Proyecto final de **Aprendizaje Automático** (3.º Ingeniería Matemática, UFV) — María Carlota Abad y Adriana Soria.

Queremos predecir qué alumnos van a suspender (nota final < 10 sobre 20) a partir de sus hábitos y situación personal, sin usar notas (escenario A) y añadiendo la nota del primer trimestre (escenario B).

## Contenido

| Carpeta / fichero | Qué es |
|---|---|
| `entrega2_eda_y_primeros_modelos.ipynb` | Notebook de la Entrega 2: EDA, preprocesado y primeros modelos |
| `student-por.csv` | Datos de Lengua portuguesa (649 alumnos) |
| `student-mat.csv` | Datos de Matemáticas (395 alumnos) |

## Cómo ejecutarlo

**En Google Colab:** subir el notebook y los dos archivos `.csv`, y ejecutar todas las celdas en orden.

**En local:** instalar las librerías `pandas`, `matplotlib` y `scikit-learn` y abrir el notebook con Jupyter.

Al ejecutarlo se crea sola una carpeta `figuras/` con los gráficos.

Usamos una semilla fija (`SEMILLA = 42`), así que los resultados salen siempre iguales.

## Datos

Cortez, P. (2008). *Student Performance* [conjunto de datos]. UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/320/student+performance — Licencia CC BY 4.0.
