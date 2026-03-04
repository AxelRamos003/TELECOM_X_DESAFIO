#***TELECOM X***           🛰️📡


**Análisis de Churn de Clientes en Telecom X**

*Descripción del Proyecto*

Este repositorio contiene el análisis de datos enfocado en la tasa de cancelación (churn) de clientes de Telecom X. El objetivo del análisis fue identificar los factores que influyen en la evasión de clientes, utilizando datos históricos de la empresa.

**Datos Utilizados**

Los datos analizados incluyen información demográfica de los clientes, tipo de contrato, servicios contratados y variables económicas (como cargo mensual y cargos totales). Se aplicó un proceso de limpieza de datos, normalización de variables categóricas y un análisis exploratorio (EDA) con visualizaciones.

**Tecnologías utilizadas**
Python 3.10+
Pandas (procesamiento de datos)
Plotly (Grafico interactivo)
Matplotlib y Seaborn (visualización de datos)
Jupyter/Colab (notebooks interactivos)

**Proceso de Análisis**

Limpieza de Datos: Se identificaron y eliminaron valores nulos y cadenas vacías. Se normalizaron nombres de columnas y se transformaron variables categóricas en variables binarias (0 y 1).

Análisis Exploratorio: Se analizaron las distribuciones de variables numéricas (como antigüedad, cargo mensual, cargos totales) y se exploró la relación con la cancelación. Además, se generaron gráficos comparativos para evaluar la tasa de cancelación según diferentes variables (género, tipo de contrato, servicios complementarios, etc.).

Correlación: Se calculó una matriz de correlación entre las variables numéricas y se analizó qué factores tenían mayor relación con la cancelación.

**Hallazgos Principales**

La tasa de cancelación general fue del 26.6%.

Las cancelaciones se concentran principalmente en los primeros meses de antigüedad.

Los clientes con contrato mensual y cargos mensuales altos tienen mayor probabilidad de cancelar.

Métodos de pago automáticos (tarjeta o transferencia bancaria) muestran menor churn.

Los cargos mensuales altos se asocian a mayor evasión.

Los servicios complementarios (seguridad, respaldo, soporte) ayudan a reducir la evasión.

**Reproductivilidad

url de datos: 'https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json'

Abrir el notebook: en google colab

**Próximos Pasos**

Los hallazgos obtenidos serán la base para el equipo de Data Science, que desarrollará modelos predictivos de churn. Esto permitirá implementar estrategias personalizadas de retención y optimizar la toma de decisiones comerciales.


**proyecto realizado por Axel Ramos Estudiante de Alura Latam.**
