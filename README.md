# Mini Proyecto de Análisis de Datos: Ventas Minoristas

**Autor:** Marianela Pollini Alzueta  
**Curso:** Herramientas Básicas para el Análisis de Datos  
**Año:** 2026  

---

## 1. Objetivo del Proyecto
Analizar la evolución de las ventas en el sector minorista, identificando las categorías de productos que impulsaron el crecimiento y evaluando el impacto de los canales de distribución (Online vs. Tienda Física) en los ingresos y márgenes de ganancia.

---

## 2. Dataset
* **Fuente de datos:** Dataset de transacciones comerciales.
* **Volumen:** Registros con 9 variables clave (`transaction_id`, `date`, `category`, `channel`, `units_sold`, `unit_price`, `total_revenue`, `cost`, `profit`).
* **Ubicación:** [Ver archivo CSV](./data/raw/retail_sales_clean.csv)

---

## 3. Pasos Realizados
1. **Limpieza e Ingesta (Python):** Tratamiento de nulos, eliminación de duplicados, formateo de fechas e imputación de ingresos faltantes (`units_sold` * `unit_price`).
2. **Exploración Visual (Python):** Generación de gráficos en Matplotlib/Seaborn para evaluar distribución por canal y categoría.
3. **Dashboard Interactivo (Power BI):** Modelado de datos, creación de métricas de ingresos/ganancias y un panel de filtros interactivo.

---

## 4. Enlaces a Recursos y Entregables
* **Notebook Exploratorio (Python):** [Ver eda_ventas.ipynb](./notebooks/eda_ventas.ipynb)
* **Dashboard Power BI (.pbix):** [Ver reporte_ventas.pbix](./dashboard/reporte_ventas.pbix)
* **Captura del Dashboard:** [Ver Captura](./dashboard/dashboard.png)
