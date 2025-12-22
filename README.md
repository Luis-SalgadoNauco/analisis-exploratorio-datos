# Análisis Exploratorio de Datos (EDA)

**Curso: Análisis de Datos y Estadística | Mes 2 – Semana 1**

---

## Descripción

Este repositorio documenta el trabajo realizado durante la **Semana 1 de Análisis Exploratorio de Datos (EDA)**, aplicando técnicas de exploración, estadística descriptiva y visualización sobre distintos datasets simulados con fines educativos.

El objetivo general del proyecto es **comprender la estructura, calidad, distribución y patrones de los datos** antes de aplicar modelos estadísticos o inferenciales.

---

## Objetivos generales del análisis

- Comprender la estructura de los datasets
- Evaluar la calidad de los datos (tipos, valores faltantes, duplicados)
- Analizar el comportamiento central y la dispersión de las variables
- Identificar patrones y posibles valores atípicos
- Formular preguntas relevantes para análisis posteriores
- Comunicar resultados mediante visualizaciones claras

---

## Datasets utilizados

Durante la semana se trabajó con los siguientes conjuntos de datos simulados:

### Dataset E-commerce
- Identificadores de pedidos, clientes y productos
- Cantidad y precio unitario
- Fecha del pedido
- Método de pago
- Edad del cliente
- Región de envío

### Dataset Empleados
- ID del empleado
- Edad
- Salario
- Años de experiencia
- Departamento
- Nivel jerárquico

**Nota:** Todos los datasets son simulados y se utilizan exclusivamente con fines académicos.

---

## Desarrollo del Análisis Exploratorio

### Día 1 – Inspección inicial y calidad de datos (E-commerce)

Durante el **Día 1** se realizó el primer acercamiento al dataset de e-commerce, enfocándose en comprender su estructura general y evaluar la calidad de los datos.

#### Actividades realizadas
- Carga y configuración del entorno de análisis
- Inspección de dimensiones y tipos de datos
- Análisis de valores faltantes y consistencia
- Revisión de rangos lógicos
- Exploración inicial mediante visualizaciones

#### Resultados destacados
- Dataset con **1000 registros y 9 variables**
- Valores faltantes concentrados en la variable **edad del cliente**
- No se detectaron valores fuera de rangos lógicos en precios y cantidades
- Distribuciones equilibradas por región y método de pago

#### Evidencia
- `eda_ecommerce_dia1.ipynb`
- `distribucion_metodo_pago.png`
- `distribucion_region.png`
- `histograma_edad_clientes.png`
- `gasto_promedio_por_edad.png`
- `Evidencia_EDA_Ecommerce.xlsx`

---

### Día 2 – Análisis estadístico descriptivo (Empleados)

Durante el **Día 2** se profundizó el EDA mediante el uso de **estadística descriptiva**, analizando el comportamiento central, la dispersión y la distribución de las variables numéricas, así como comparaciones por categorías.

#### Análisis realizados
- Medidas de tendencia central: media, mediana y moda
- Medidas de dispersión: rango, varianza, desviación estándar y coeficiente de variación
- Análisis de percentiles y rango intercuartílico (IQR)
- Identificación de valores atípicos
- Comparaciones por departamento y nivel jerárquico

#### Visualizaciones generadas
- Salario promedio por departamento (gráfico de barras)
- Boxplots de:
  - Edad
  - Salario
  - Años de experiencia
- Composición de empleados por departamento (gráfico circular)
- Composición del salario total por nivel (gráfico circular)

#### Evidencia
- `eda_empleados_dia2.ipynb`
- `salario_promedio_departamento.png`
- `boxplot_edad.png`
- `boxplot_salario.png`
- `boxplot_anios_experiencia.png`
- `composicion_empleados_departamento.png`
- `composicion_salarial_nivel.png`
- `Evidencia_EDA_Dia2.xlsx`

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git y GitHub

---

## Estructura del repositorio

analisis-exploratorio-datos/

│  
├── README.md  
├── .gitignore  
│  
├── eda_ecommerce_dia1.ipynb  
├── eda_empleados_dia2.ipynb  
│  
├── Evidencia_EDA_Ecommerce.xlsx  
├── Evidencia_EDA_Dia2.xlsx  
│  
├── distribucion_region.png  
├── distribucion_metodo_pago.png  
├── histograma_edad_clientes.png  
├── gasto_promedio_por_edad.png  
├── salario_promedio_departamento.png  
├── boxplot_edad.png  
├── boxplot_salario.png  
├── boxplot_anios_experiencia.png  
├── composicion_empleados_departamento.png  
├── composicion_salarial_nivel.png 
