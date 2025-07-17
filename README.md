# Challenges ONE - Alura Store

## 📊 Análisis de Eficiencia de Tiendas - Alura Store

Este proyecto tiene como objetivo ayudar al Sr. Juan, dueño de la cadena **Alura Store**, a decidir cuál de sus cuatro tiendas debería vender para iniciar un nuevo emprendimiento. El análisis se basa en datos de ventas, desempeño, calificaciones y envíos de cada tienda.

---

## 📁 Estructura del Proyecto

El análisis se divide en 5 secciones:

1. **Análisis de facturación**  
2. **Ventas por categoría**  
3. **Calificación promedio de la tienda**  
4. **Productos más y menos vendidos**  
5. **Costo promedio de envío**

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib
- NumPy

---

## 📌 Pasos del análisis

### 1. Carga de datos
Se cargan los archivos `.csv` correspondientes a las 4 tiendas con información sobre productos, precios, envío, calificaciones, fechas, etc.

```python
import pandas as pd

tienda1 = pd.read_csv('tienda_1.csv')
tienda2 = pd.read_csv('tienda_2.csv')
...
```

---

### 2. Análisis de facturación

Se calcula el ingreso total por tienda sumando los valores de la columna **Precio**.  
📈 **Visualización**: Gráfico de barras.

---

### 3. Ventas por categoría

Se agrupan los productos por categoría para conocer las más vendidas en cada tienda.  
📊 **Visualización**: Gráfico de barras agrupadas.

---

### 4. Calificación promedio

Se calcula la calificación media otorgada por los clientes a cada tienda.  
📉 **Visualización**: Gráfico de líneas.

---

### 5. Productos más y menos vendidos

Se identifican los productos más y menos vendidos en cada tienda.  
📋 **Visualización**:  
- Gráfico de dispersión

---

### 6. Costo promedio de envío

Se analiza cuánto gasta cada tienda en promedio por envío.  
📦 **Visualización**:
- Gráfico de pie

---

## ✅ Conclusión

Tras analizar todas las métricas:

- **Tienda 4** tiene el **menor ingreso total**
- No lidera ninguna categoría de ventas
- Mantiene una calificación promedio aceptable (4.0)
- Tiene el **costo de envío más bajo**, lo cual es una fortaleza

📌 **Recomendación**: Se sugiere **vender la Tienda 4**, por ser la menos eficiente globalmente.

---

## 📂 Archivos incluidos

- `tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`: datos de cada tienda
- `analisis_alura_store.ipynb`: notebook con todo el análisis y gráficos
- `README.md`: este archivo

---

## 🧠 Autor

**Sebastián Vicente Ramírez Pérez**  
Proyecto de práctica de análisis de datos en Python para Alura Latam
