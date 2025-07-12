# 📊 Análisis de Ventas por Tienda

Este proyecto tiene como objetivo analizar datos de ventas provenientes de cuatro tiendas diferentes utilizando técnicas de análisis exploratorio de datos, visualización y geolocalización. El propósito principal es determinar cuál tienda representa la mejor opción para que el Sr. Juan comercialice sus productos, basándose en métricas como ingresos, calificaciones de los clientes, categorías, productos destacados y distribución geográfica.

---

## 📌 Contenido

- [🔍 Descripción](#-descripción)
- [🛠️ Instalación y dependencias](#️-instalación-y-dependencias)
- [🚀 Cómo ejecutar](#-cómo-ejecutar)
- [📊 Visualizaciones generadas](#-visualizaciones-generadas)
- [🧠 Resultados principales](#-resultados-principales)
- [📍 Extra: Análisis geográfico](#-extra-análisis-geográfico)
- [👥 Colaboradores](#-colaboradores)
- [✅ Checklist](#-checklist)
- [🗓️ Fechas importantes](#-fechas-importantes)
- [🏷️ Etiquetas](#-etiquetas)

---

## 🔍 Descripción

El análisis considera los siguientes puntos por tienda:

- Ingresos totales  
- Categorías más y menos vendidas  
- Calificaciones promedio de los clientes  
- Productos más y menos vendidos  
- Coste de envío promedio  
- Ubicación geográfica de las ventas (latitud y longitud)

Este proyecto fue desarrollado en **Python** utilizando librerías como `pandas`, `matplotlib` y `folium`.

---

## 🛠️ Instalación y dependencias

- Este proyecto fue desarrollado en Google Colab. Si deseas ejecutarlo localmente, asegúrate de tener:

`pip install pandas matplotlib folium`

---
## 🚀 Cómo ejecutar

1. Clona o descarga este repositorio.
2. Abre el archivo `AluraStoreLatam.ipynb` en Google Colab o Jupyter Notebook.
3. Asegúrate de tener conexión a internet para cargar los archivos CSV desde las URLs.
4. Ejecuta todas las celdas secuencialmente.
5. Visualiza los gráficos generados y revisa el informe final incluido en el notebook.

---

## 📊 Visualizaciones generadas

- 📉 **Gráfico de barras:** Ingresos totales por tienda  
- 🟦 **Gráfico de líneas:** Calificaciones promedio por tienda  
- 🧩 **Gráfico circular:** Distribución de categorías de productos  
- 🔻 **Gráfico de barras:** Productos más y menos vendidos  
- 💰 **Barras agrupadas:** Ingresos vs Costos de envío  
- 🗺️ **Mapas de calor:** Concentración geográfica de ventas  
- 🌍 **Mapas interactivos:** Distribución geográfica con `Folium`
---

## 🧠 Resultados principales

- **Tienda 1** tiene el mayor ingreso total, pero la menor calificación promedio y el costo de envío más alto.
- **Tienda 3** mantiene un excelente equilibrio entre ingresos, calificaciones y logística, siendo la más recomendable.
- **Tienda 2** posee buenas calificaciones, pero con ingresos levemente inferiores.
- **Tienda 4** destaca por su bajo costo de envío, pero tiene el ingreso más bajo entre las cuatro tiendas.

📌 **Recomendación final:** La **Tienda 3** es la más adecuada para que el Sr. Juan comercialice sus productos, debido a su rendimiento global balanceado.

---

## 📍 Extra: Análisis geográfico

Se utilizaron las columnas `lat` y `lon` para mapear la distribución geográfica de las ventas. Entre los hallazgos principales destacan:

- Identificación de regiones con alta densidad de ventas.
- Detección de zonas estratégicas para optimizar logística y cobertura.
- Visualización clara de patrones de compra según la ubicación.

Se generaron tanto **mapas de calor** como **mapas interactivos** usando `Folium`, lo que permitió explorar de manera más visual y detallada el comportamiento geográfico de las ventas.

---

## 👥 Colaboradores

- 👩‍💻 Cleysi Ramos 
---
## ✅ Checklist

- [x] Análisis de datos de ventas
- [x] Visualización con Matplotlib
- [x] Cálculo de métricas clave (ingresos, satisfacción, envíos)
- [x] Mapas interactivos con Folium
- [x] Informe final en formato Markdown
- [x] Archivo README completo y estructurado

---

## 🗓️ Fechas importantes

- 📅 Inicio del proyecto: Julio 2025  
- 📅 Última actualización: Julio 2025---

## 🏷️ Etiquetas

`#Python` `#DataScience` `#EDA` `#Ventas` `#Visualización`  
`#Pandas` `#Folium` `#Matplotlib` `#AnálisisExploratorio` `#Geolocalización`

---
