# Databases and SQL for Data Science with Python - IBM Certificate

Este repositorio contiene los proyectos y ejercicios prácticos desarrollados durante el curso **Databases and SQL for Data Science with Python**, impartido por IBM a través de Coursera. Este curso forma parte de la certificación profesional **IBM Data Science Professional Certificate**.

## 📌 Descripción del Proyecto
En este módulo se trabajó en la integración entre bases de datos relacionales (SQLite) y Python mediante Jupyter Notebooks, utilizando extensiones de SQL Magic (`ipython-sql`) y bibliotecas de análisis de datos como `pandas` y `sqlite3`.

### 📊 Conjuntos de Datos Analizados
Se realizó un análisis de datos integrados sobre la ciudad de Chicago utilizando tres conjuntos de datos reales:
1. **Datos Socioeconómicos (`socioeconomic`)**: Indicadores de hacinamiento, pobreza, desempleo e ingresos per cápita por área comunitaria.
2. **Escuelas Públicas de Chicago (`school`)**: Métricas de desempeño escolar, asistencia y puntuaciones de seguridad (`SAFETY_SCORE`).
3. **Datos de Criminalidad (`crime`)**: Registros de delitos, tipos primarios (`PRIMARY_TYPE`), descripciones y ubicaciones.

## 🛠️ Herramientas y Tecnologías Utilizadas
- **Lenguaje**: Python
- **Bases de Datos**: SQLite (`sqlite3`)
- **Librerías de Python**: `pandas`, `prettytable`
- **Herramientas de Jupyter**: SQL Magic (`%load_ext sql`, `%%sql`)
- **SQL**: Consultas complejas con `GROUP BY`, `ORDER BY`, filtros condicionales (`LIKE`, `WHERE`), agregaciones (`AVG`, `COUNT`) y exploración de esquemas (`PRAGMA_TABLE_INFO`).

## 🔍 Consultas y Análisis Destacados
Entre los análisis ejecutados dentro del proyecto se incluyen:
- Identificación de áreas comunitarias con ingresos per cápita inferiores a $11,000 USD.
- Evaluación del promedio de puntuación de seguridad (`SAFETY_SCORE`) agrupado por tipo de escuela (primaria, secundaria y preparatoria).
- Filtrado y análisis de incidentes delictivos reportados dentro de instituciones escolares.
- Identificación de las áreas comunitarias con mayor porcentaje de hogares por debajo del límite de pobreza.
