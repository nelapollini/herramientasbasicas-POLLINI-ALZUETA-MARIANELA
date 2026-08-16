# Mini Proyecto de Análisis de Datos: Ventas Minoristas (2019–2024)

**Autor:** Marianela Pollini Alzueta 
**Curso:** Herramientas Básicas para el Análisis de Datos  
**Año:** 2026  

---

## 1. Objetivo del Proyecto
El objetivo principal de este trabajo es analizar la evolución de las ventas en el sector minorista, identificando las categorías de productos que impulsaron el crecimiento y evaluando el impacto de los canales de distribución (Online vs. Tienda Física) en los ingresos y márgenes de ganancia.

---

## 2. Dataset
* **Fuente de datos:** Dataset de transacciones comerciales.
* **Volumen:** Registros con 9 variables clave (`transaction_id`, `date`, `category`, `channel`, `units_sold`, `unit_price`, `total_revenue`, `cost`, `profit`).
* **Ubicación:** [Ver archivo CSV](./data/raw/retail_sales_clean.csv)[cite: 1]

---

## 3. Pasos Realizados
1. **Limpieza e Ingesta (Python):** Tratamiento de nulos, eliminación de duplicados, formateo de fechas e imputación de ingresos faltantes (`units_sold` * `unit_price`).
2. **Exploración Visual (Python):** Generación de gráficos en Matplotlib/Seaborn para evaluar distribución por canal y categoría.
3. **Dashboard Interactivo (Power BI):** Modelado de datos, creación de métricas de ingresos/ganancias y un panel de filtros interactivo.

---

## 4. Enlaces a Recursos y Entregables
* **Notebook Exploratorio (Python):** [Ver eda_ventas.ipynb](./notebooks/eda_ventas.ipynb)[cite: 1]
* **Dashboard Power BI (.pbix):** [Ver reporte_ventas.pbix](./dashboard/reporte_ventas.pbix)[cite: 1]
* **Captura del Dashboard:** [Ver Captura](./dashboard/dashboard.png)[cite: 1]

---

## 5. Referencias
* *Seaborn / Pandas Documentation.* Data Visualization and Analysis in Python.
* *Power BI Documentation.* Microsoft Power BI Desktop Guidelines.
