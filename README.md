# 📊 Análisis de Ventas - Documentación del Proyecto

## 📌 Descripción General

Este proyecto tiene como objetivo analizar el comportamiento de ventas de una tienda en línea utilizando *Python* y *Pandas*. Se realiza un *proceso completo de análisis de datos*, que incluye:

- *Limpieza y transformación de datos* para garantizar la calidad de la información.
- *Exploración de datos* para entender patrones y tendencias.
- *Visualización* mediante `Matplotlib`.
- *Conclusiones y recomendaciones* para la optimización de ventas.

---

## 📂 Contenido del Proyecto

### 📁 1. Datos de entrada

*Archivo:* `datos_finales.xlsx`

Contiene la información procesada y lista para el análisis, después de aplicar procesos de limpieza y transformación.

### 📒 2. Notebook de Análisis

**Archivo:** `Ultimo_proyecto.ipynb`

- *Carga y exploración de datos* (`df.info()`, `df.describe()`).
- *Limpieza y tratamiento de valores nulos*.
- *Eliminación de columnas irrelevantes con justificación clara*.
- *Visualización de datos para detectar tendencias y patrones.*

### 📄 3. Informe de Análisis

*Archivo:* `INFORME_DE_ANÁLISIS_DE_VENTAS.docx`

📜 Contiene:

- *💰 Resumen del total de ventas.*
- *🛍️ Número de pedidos y ticket promedio.*
- *🏆 Categorías más y menos vendidas.*
- *📆 Tendencias de ventas por período.*
- *✅ Conclusiones y recomendaciones.*

### 🖥️ 4. Dashboard Interactivo

El archivo `datos_finales.xlsx` incluye un **Dashboard interactivo** para visualizar el comportamiento de ventas y productos a lo largo del tiempo.

---

## 📊 Columnas Principales del Conjunto de Datos

| *Columna*              | *Descripción*                      |
| ---------------------- | ---------------------------------- |
| `order_id`             | Identificador único del pedido.    |
| `product_id`           | ID del producto comprado.          |
| `price`                | Precio del producto en la orden.   |
| `freight_value`        | Costo del envío.                   |
| `customer_state`       | Estado donde se realizó la compra. |
| `order_purchase_date`  | Fecha en que se realizó la compra. |
| `order_delivered_date` | Fecha de entrega del pedido.       |
| `product_category`     | Categoría del producto.            |

---

## 🚀 Instrucciones de Uso

1️⃣ *Abrir `Ultimo_proyecto.ipynb` en Jupyter Notebook.*  
2️⃣ *Ejecutar todas las celdas* en orden para ver el procesamiento y análisis de datos.  
3️⃣ *Revisar `INFORME_DE_ANÁLISIS_DE_VENTAS.docx`* para obtener un resumen ejecutivo de los hallazgos.  
4️⃣ *Explorar el `Dashboard` en `datos_finales.xlsx`* para visualizar tendencias interactivas.  

---

## 🎯 Conclusiones y Recomendaciones

📌 *La categoría más vendida* es `beleza_saude`, se recomienda reforzar su promoción.  
📌 *Categorías con menor demanda* necesitan estrategias para aumentar sus ventas.  
📌 *El ticket promedio* es *120.82*, se pueden implementar descuentos por compra mínima para aumentarlo.  
📌 *Optimización logística:* Se sugiere analizar tiempos de entrega y reducir costos de envío.  

---

## 📂 Autores y Referencias

📊 Base de datos: [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
✍️ *Autores:* Francisco Magioli · Leo Dabague · Andre Sionek  
