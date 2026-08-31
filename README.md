# 🛒 Superstore Sales Dataset

Este repositorio aloja el archivo de datos original del proyecto "Superstore Sales", utilizado como fuente (origen de datos) para procesos de ingesta ETL y modelado en PostgreSQL.

## 📊 Sobre el Dataset

El archivo contiene el registro histórico transaccional de una cadena de tiendas minoristas (retail) en Estados Unidos. El dataset fue obtenido originalmente de [Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting).

### Detalles Técnicos:
* **Archivo:** `train.csv`
* **Formato:** CSV plano (Comma-Separated Values).
* **Volumen:** 9,800 registros (filas).
* **Variables:** 18 columnas que incluyen información de la orden, datos del cliente, ubicación de envío, detalles del producto y montos de ventas.

### Estructura de las Columnas:
1. `Row ID`: Identificador único de fila.
2. `Order ID`: Identificador de la orden de compra.
3. `Order Date`: Fecha en que se realizó la orden (Formato DD/MM/YYYY).
4. `Ship Date`: Fecha de envío.
5. `Ship Mode`: Tipo de envío (Ej. Standard Class, First Class).
6. `Customer ID`: Identificador único del cliente.
7. `Customer Name`: Nombre completo del cliente.
8. `Segment`: Segmento comercial (Consumer, Corporate, Home Office).
9. `Country`: País de envío.
10. `City`: Ciudad de envío.
11. `State`: Estado de envío.
12. `Postal Code`: Código postal numérico.
13. `Region`: Región comercial (South, West, Central, East).
14. `Product ID`: Código interno del producto.
15. `Category`: Categoría principal del producto (Furniture, Office Supplies, Technology).
16. `Sub-Category`: Subcategoría del producto.
17. `Product Name`: Descripción o nombre comercial del producto.
18. `Sales`: Monto de la venta (Métrica numérica).

## 🚀 Uso en Proyectos de Datos (Data Engineering)

El objetivo de alojar este archivo en GitHub es permitir su consumo directo a través de solicitudes HTTP (mediante su URL "Raw") para alimentar bases de datos en entornos locales o en la nube sin depender de descargas manuales.

**Enlace Raw para ingesta directa:**
```text
[https://raw.githubusercontent.com/egle06/superstore-sql-capstone/refs/heads/main/train.csv](https://raw.githubusercontent.com/egle06/superstore-sql-capstone/refs/heads/main/train.csv)
