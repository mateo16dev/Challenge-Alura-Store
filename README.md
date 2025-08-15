# 📊 Análisis de Ventas — Alura Store

## 🎯 Propósito del análisis
Este proyecto tiene como objetivo ayudar al Sr. Juan a decidir qué tienda de su cadena **Alura Store** debería vender para financiar un nuevo emprendimiento.  
A partir de datos reales de ventas, rendimiento y reseñas de **4 tiendas**, se identificará la menos eficiente y se presentará una **recomendación final respaldada por evidencia**.

---

## 📂 Estructura del proyecto
```text
📁 Alura_Store_Analysis
├── 📄 AluraStoreLatam.ipynb   # Notebook principal con el análisis
├── 📁 data/                       # Archivos CSV con datos de ventas y reseñas
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
├── 📁 img/                        # Imágenes y gráficos generados
│   ├── ventas_por_tienda.png
│   ├── calificación_por_tienda.png
│   └── costo_promedio_envio.png
└── 📄 README.md                   # Descripción del proyecto
```


---

## 📈 Ejemplos de gráficos e insights

- **Ingresos totales por tienda**  
  <img src="img/ventas_por_tienda.png" width="400">  
  *Insight:* La Tienda No. 4 presenta el menor nivel de ingresos acumulados.

- **Calificación por tienda**  
  <img src="img/categorias_mas_vendidas.png" width="400">  
  *Insight:* La Tienda No.1 presenta la calificación más baja con 3.98 de puntos.

- **Costo promedio de envío**  
  <img src="img/promedio_envio.png" width="400">  
  *Insight:* La Tienda No.1 presenta el costo promedio más alto, lo que podría afectar la satisfacción del cliente.

---

## 🛠️ Tecnologías y librerías utilizadas
- **Python 3.10**
- **Pandas** — Limpieza y manipulación de datos.
- **Matplotlib** — Creación de visualizaciones.
- **Google Colab** — Desarrollo y documentación interactiva.

---

📌 Recomendación final

Basado en el análisis de ingresos, reseñas y rendimiento, la Tienda C se identifica como la menos eficiente y la candidata recomendada para ser vendida.
Esta conclusión se respalda en:

Ingresos por debajo del promedio.

Menor número de productos líderes en ventas.

Evaluaciones de clientes con puntuaciones más bajas.

---
✍️ Autor

Proyecto desarrollado como parte del desafío Alura Store — Data Analysis Challenge.

---
## ▶️ Instrucciones para ejecutar el notebook
1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/usuario/alura-store-analysis.git
   cd alura-store-analysis
