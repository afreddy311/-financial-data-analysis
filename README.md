# Análisis de Gastos Frecuentes 💸

Este proyecto consiste en el análisis de un dataset de transacciones personales con el objetivo de entender los patrones de gasto, categorías frecuentes y comportamiento financiero mensual.

---

## 📍 Objetivos

* Identificar en qué se gasta más dinero.
* Analizar la evolución de gastos mes a mes.
* Evaluar la distribución de montos gastados.
* Conocer los días con mayor frecuencia de transacciones.

---

## 📂 Dataset

* Fuente: Dataset de transacciones personales (CSV)
* Columnas principales:

  * `date`: Fecha y hora de la transacción
  * `category`: Categoría del gasto
  * `amount`: Monto de la transacción (en soles)

---

## 📊 Análisis Realizados

### 1. Gasto total por categoría

Gráfico de barras que muestra en qué rubros se gasta más dinero (ej. mercado, restaurante, café).

### 2. Gasto mensual total

Gráfico de línea con la evolución mensual de gastos para detectar picos o tendencias.

### 3. Distribución de montos

Histograma que refleja la concentración de transacciones por rango de montos.

### 4. Gasto promedio por categoría

Comparación del gasto promedio por cada tipo de gasto.

### 5. Frecuencia de gastos por día de la semana

Indica cuáles son los días con mayor o menor actividad financiera.

---

## 🧰 Herramientas Utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 📁 Estructura del Proyecto

```text
proyecto_gastos_personales/
├── data/
│   └── budget_data.csv
├── notebooks/
│   └── analisis_gastos.ipynb
├── output/
│   ├── gasto_categoria.png
│   ├── gasto_mensual.png
│   ├── distribucion_montos.png
│   ├── promedio_categoria.png
│   ├── frecuencia_dias.png
│   └── resumen_gastos.csv
└── README.md
```

---




