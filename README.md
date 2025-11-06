# 📊 Análisis de ventas y recomendación de tienda para el Sr. Juan

## 🧠 Descripción del proyecto
Este proyecto tiene como objetivo analizar la información de ventas de cuatro tiendas con el fin de determinar cuál de ellas representa la mejor opción comercial para el Sr. Juan.  
Se utilizó **Python**, **Google Colab** y la biblioteca **pandas** para procesar, visualizar y comparar distintos indicadores clave de desempeño, como ingresos, calificaciones, costos de envío y categorías de productos vendidos.

---

## 🧩 Estructura del proyecto
El proyecto se compone de las siguientes secciones principales:

1. **Carga de datos**: Importación de los conjuntos de datos de las cuatro tiendas (`tienda1`, `tienda2`, `tienda3`, `tienda4`).
2. **Exploración de datos**: Inspección de estructura, columnas y valores faltantes.
3. **Análisis estadístico**:  
   - Cálculo de ingresos totales por tienda.  
   - Identificación de categorías y productos más y menos vendidos.  
   - Obtención de valoraciones promedio por tienda.  
   - Estimación del costo de envío promedio.  
4. **Visualización de resultados**: Creación de gráficos de barras, pastel y líneas para representar los hallazgos de manera clara.
5. **Informe final**: Síntesis de resultados y recomendación justificada sobre la mejor tienda para vender los productos del Sr. Juan.

---

## ⚙️ Requisitos y dependencias

Para ejecutar correctamente el código, asegúrate de tener instaladas las siguientes bibliotecas de Python:

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
