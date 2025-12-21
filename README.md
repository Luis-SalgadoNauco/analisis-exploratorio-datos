# Análisis Exploratorio de Datos – E-commerce

**Curso: Análisis de Datos y Estadística | Mes 2 – Semana 1**

---

## Descripción

Este repositorio documenta el trabajo realizado durante la **Semana 1: Análisis Exploratorio de Datos (EDA)**,
aplicado a un dataset de ventas de comercio electrónico generado con fines educativos.

El enfoque principal fue comprender la estructura, calidad y patrones de los datos antes de aplicar
modelos estadísticos o inferenciales.

---

## Objetivos del análisis

- Comprender la estructura del dataset
- Evaluar la calidad de los datos (tipos, valores faltantes, duplicados)
- Identificar patrones iniciales de comportamiento
- Generar preguntas relevantes para análisis posteriores
- Crear visualizaciones claras como evidencia del EDA

---

## Dataset

El conjunto de datos simula ventas de un e-commerce e incluye:

- Identificadores de pedidos, clientes y productos
- Cantidad y precio unitario
- Fecha del pedido
- Método de pago
- Edad del cliente
- Región de envío

**Nota:** Los datos son simulados y se utilizan exclusivamente con fines académicos.

---

## Proceso de Análisis Exploratorio

> Este proceso se desarrolló progresivamente durante la semana.  
> A continuación, se detalla el trabajo correspondiente al Día 1.

### Inspección inicial

- Dimensiones del dataset
- Tipos de datos
- Rango temporal de los pedidos

### Análisis de calidad de datos

- Identificación de valores faltantes
- Evaluación de completitud
- Validación de rangos lógicos
- Análisis de valores únicos

### Preguntas exploratorias

- Distribución de pedidos por región
- Métodos de pago más utilizados
- Distribución de edad de los clientes
- Gasto promedio por grupo etario
- Ingresos totales por región

---

## Día 1 – Inspección inicial y calidad de datos

Durante el **Día 1** se realizó el primer acercamiento al conjunto de datos, con el objetivo de
comprender su estructura general y evaluar su calidad antes de avanzar hacia análisis más profundos.

### Actividades realizadas

- Carga y configuración inicial del entorno de análisis
- Inspección de dimensiones, tipos de datos y rango temporal
- Identificación y análisis de valores faltantes
- Revisión de valores únicos y consistencia de las variables
- Formulación de preguntas exploratorias iniciales

### Resultados destacados

- El dataset presenta **1000 registros y 9 variables**
- Los valores faltantes se concentran en la variable **edad del cliente**
- No se detectaron valores fuera de rangos lógicos definidos para precios y cantidades
- La distribución por región y método de pago es relativamente equilibrada

### Evidencia

- `eda_ecommerce_dia1.ipynb`
- `distribucion_metodo_pago.png`
- `distribucion_region.png`
- `gasto_promedio_por_edad.png`
- `histograma_edad_clientes.png`
- `Evidencia_EDA_Ecommerce.xlsx`

---

## Visualizaciones generadas

Las siguientes visualizaciones se generaron como imágenes para una comunicación clara de resultados durante el Día 1 del análisis:

- Distribución de pedidos por región
- Distribución por método de pago
- Histograma de edad de clientes
- Gasto promedio por grupo de edad

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
├── Evidencia_EDA_Ecommerce.xlsx  
│  
├── distribucion_region.png  
├── distribucion_metodo_pago.png  
├── histograma_edad_clientes.png  
├── gasto_promedio_por_edad.png  
