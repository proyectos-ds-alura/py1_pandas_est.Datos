# Análisis de Ventas y Costos de Envío en Tiendas Online

Este proyecto analiza datos de ventas, productos, calificaciones y costos de envío de cuatro tiendas online diferentes. Se realizan cálculos de ingresos totales, conteos por categoría y producto, análisis de calificaciones y costos promedio de envío, junto con visualizaciones para facilitar la interpretación.

---

## Descripción del Proyecto

El objetivo es explorar y comparar la información comercial de cuatro tiendas, identificando:

- Ingresos totales por tienda.
- Cantidad de productos vendidos por categoría.
- Calificaciones promedio de los productos por tienda.
- Productos más y menos vendidos.
- Costos promedio de envío por tienda.

---

## Datos

Los datos provienen de archivos CSV públicos alojados en GitHub:

- Tienda 1: [Link CSV Tienda 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- Tienda 2: [Link CSV Tienda 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- Tienda 3: [Link CSV Tienda 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- Tienda 4: [Link CSV Tienda 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

---

## Herramientas utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn

---

## Código y Análisis

### Carga de datos

Se cargan los datos de las cuatro tiendas en dataframes separados con pandas.

### Ingresos Totales por Tienda

Se calcula la suma total del precio de los productos vendidos por cada tienda y se visualiza con un gráfico de barras verticales.

![Gráfico de ingresos totales](images/ingresos%20totales%20x%20tienda.png)

### Conteo de Productos por Categoría

Se cuentan los productos vendidos por categoría en cada tienda y se crea una tabla pivote para visualizar con un heatmap, mostrando la distribución por tienda y categoría.

![Heatmap de categorías](images/cant%20prod%20vend%20x%20cat%20y%20tienda.png)

### Calificación Promedio por Tienda

Se calcula el promedio de las calificaciones de los productos para cada tienda.

### Productos Más y Menos Vendidos

Se identifican los productos con mayor y menor cantidad de ventas en cada tienda.

### Costo Promedio de Envío

Se calcula el costo promedio de envío por tienda y se visualiza con un gráfico de barras horizontales.

![Gráfico de ingresos totales](images/costo%20envio%20x%20tienda.png)
---

## Visualizaciones

- Gráfico de barras verticales para ingresos totales.
- Heatmap para distribución de productos por categoría y tienda.
- Gráfico de barras horizontales para costos promedio de envío.

---

## Resultados destacados

- Las tiendas presentan diferentes ingresos y perfiles de ventas.
- Las categorías más populares varían entre tiendas.
- Hay diferencias en las calificaciones promedio de productos.
- Los costos de envío promedio difieren significativamente.

---

## Uso

Para ejecutar el análisis, asegúrate de tener instaladas las librerías requeridas:

```bash
pip install pandas matplotlib seaborn
