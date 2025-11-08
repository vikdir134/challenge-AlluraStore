# 🛒 Análisis de Ventas por Tienda – Proyecto en Google Colab

## 📘 Descripción del Proyecto
Este proyecto realiza un análisis completo de los datos de ventas de **cuatro tiendas distintas**, con el propósito de **determinar cuál debería ser vendida o liquidada** en base a evidencia numérica y visual.  

A través de distintas etapas de análisis y visualización, se exploran métricas clave como los ingresos totales, las categorías de productos más vendidas, las valoraciones de los clientes y los costos de envío, además de un análisis geográfico que muestra la distribución espacial de las ventas mediante coordenadas.

---

## 📊 Estructura del Análisis
El notebook está dividido en secciones temáticas para facilitar la comprensión:

### 🧾 1. Ingreso total por cada tienda
Se calcula la suma de todas las ventas realizadas por cada tienda, identificando cuál genera los mayores ingresos globales.

### 🧮 2. Ventas por categoría
Se analiza la cantidad de productos vendidos por categoría (muebles, electrónicos, juguetes, etc.), comparando las tendencias entre tiendas.

### 🌟 3. Valoración media por tienda
Se calcula la calificación promedio otorgada por los clientes, lo que permite medir la **satisfacción general** y la **reputación de cada tienda**.

### 📈 4. Productos más vendidos y menos vendidos
Identifica los productos más populares y los menos solicitados por los clientes, visualizados mediante gráficos comparativos.

### 🚚 5. Valor del envío promedio por tienda
Analiza el **costo promedio de envío** que asumen los clientes, comparando su impacto en la percepción de compra y competitividad entre tiendas.

### 🌍 6. Distribución geográfica de ventas (Extra)
Usando las columnas de **latitud y longitud**, se genera un **mapa de calor (HeatMap)** con la librería *Folium*, para visualizar las zonas con mayor concentración de ventas.  
El análisis mostró que **Bogotá** presenta la zona más brillante, reflejando **mayor actividad comercial y volumen de ventas**, mientras que las demás regiones tienen una distribución más uniforme y de menor intensidad.

---

## 🚀 Cómo Ejecutar el Proyecto

Puedes ejecutar el análisis de dos maneras:

### ✅ Opción 1 — Abrir directamente en Google Colab
1. Haz clic en el botón **“Open in Colab”** del repositorio.  
2. Una vez abierto el notebook, selecciona **“Entorno de ejecución → Ejecutar todo”**.  
3. Se generarán automáticamente todas las tablas, gráficos y el informe final.

> 💡 Esta es la forma más rápida y recomendada para visualizar los resultados.

---

### 📁 Opción 2 — Descargar y abrir desde Google Drive
1. Descarga el archivo `.ipynb` del repositorio.  
2. Sube el archivo a tu Google Drive.  
3. Ábrelo con **Google Colab**.  
4. Dirígete a **“Entorno de ejecución → Ejecutar todo”** para ejecutar todas las celdas y visualizar los resultados.  

Esto te permitirá ver las **tablas, datos procesados, correcciones automáticas y el informe final completo**.

---

## 🧩 Tecnologías Utilizadas
- **Python 3.10+**  
- **Pandas** → Limpieza y análisis de datos  
- **Matplotlib / Seaborn** → Visualizaciones  
- **Folium** → Mapas interactivos y mapas de calor  
- **Google Colab** → Ejecución del notebook

---

## 📊 Resultados Principales
- **Tienda 1** lidera en ingresos totales.  
- Las categorías más vendidas son **muebles y electrónicos**.  
- Las valoraciones promedio son muy similares entre tiendas.  
- **Bogotá** concentra la mayor densidad de ventas según el mapa de calor geográfico.

---

## 👨‍💻 Autor
**Victor Antonio Abrahan Camargo Chuchon**   
📍 Lima, Perú  

---

## 🏷️ Licencia
Proyecto con fines académicos y de aprendizaje.  
Puedes utilizarlo citando al autor original.
