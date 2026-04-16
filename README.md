# Trabajo Final: Herramientas Básicas para el Análisis de Datos

**Autor:** Vargas, Lucía Daniela
**Curso:** Herramientas Básicas para el Análisis de Datos - UTN


## 🧠 Proceso realizado

El trabajo se desarrolló en dos etapas fundamentales:

### 1. Análisis en Python (Google Colab)
Se realizó el proceso de ETL (Extracción, Transformación y Carga) detallado en el notebook incluido:
* Carga y limpieza de datos utilizando la librería Pandas.
* Revisión de tipos de datos y valores nulos.
* Conversión de fechas.
* Creación de nuevas variables temporales.
* Eliminación de columnas no relevantes para el análisis.

### 2. Visualización en Power BI

Se diseñó un dashboard interactivo que incluye:
* KPIs: Tarjetas con Ventas Totales, Cantidad de Pedidos y Ticket Promedio.
* Segmentador de Año: Filtro dinámico para análisis temporal.
* Gráfico de Anillo: Ventas por Región.
* Gráfico de Líneas: Evolución mensual de las ventas.
* Gráficos de Barras: Ventas por Categoría y Segmento de Cliente.


---

## 3 Archivos del proyecto

- `Dataset.csv`: datos originales
- `ventas_limpio.csv`: datos procesados
- `análisis_ventas_superstore.ipynb.ipynb`: notebook de análisis
- `herramientasbasicas-vargas-lucia.pbix`: archivo de Power BI
- `dashboard.png`: imagen del dashboard

---

## 4. Conclusiones y Resultados

1.  **Categoría Líder:** La categoría "Technology" es la que genera mayores ingresos.
2.  **Segmento de Cliente:** El segmento "Consumer" representa el mayor volumen de ventas.
3.  **Estacionalidad:** Las ventas aumentan significativamente hacia el último trimestre del año.
4.  **Distribución Regional:** La región "West" es el mercado más fuerte.

---

## 5. Bibliografía

* *Knyazeva, K. (2019). Superstore Sales Dataset. Kaggle.*
* *Knaflic, C. N. (2015). Storytelling with data: A data visualization guide for business professionals. John Wiley & Sons.*
* *Documentación de Pandas:* [pandas.pydata.org](https://pandas.pydata.org/)
* *Documentación de Power BI:* [learn.microsoft.com/power-bi/](https://learn.microsoft.com/power-bi/)

---

## ℹ️ Notas

- Algunos valores nulos están presentes en la columna Postal Code del dataset original.
- El archivo `.pbix` requiere Power BI Desktop para ser abierto.
