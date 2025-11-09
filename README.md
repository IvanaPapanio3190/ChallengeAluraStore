# ChallengeAluraStore
Proyecto de análisis de datos del desafío Alura Store: ingresos, reseñas y desempeño de ventas por tienda.

# Alura Store - Análisis de Tiendas

Este proyecto forma parte del desafío de análisis de datos de **Alura LATAM**.  
El objetivo fue ayudar al Sr. Juan a decidir qué tienda de su cadena Alura Store debería vender, basándose en los datos de ventas, reseñas y rendimiento de las 4 tiendas.

---

## Objetivo del Proyecto
Analizar el desempeño de las tiendas para identificar cuál presenta los peores resultados, considerando:
- Ingresos totales
- Ventas por categoría
- Valoraciones promedio
- Productos más y menos vendidos
- Envío promedio

---

##  Propósito del análisis
El propósito de este proyecto fue aplicar técnicas de **análisis de datos con Python** para responder a las siguientes preguntas:

- 1. ¿Cuál es la facturación total de cada tienda?  
- 2. ¿Qué categorías de productos son las más populares en cada tienda?  
- 3. ¿Cuál es la valoración promedio de los clientes?  
- 4. ¿Cuáles son los productos más y menos vendidos?  
- 5. ¿Cuál es el costo o tiempo promedio de envío?

Con estas métricas, se elaboró una recomendación final para el Sr. Juan.

---

## Librerías utilizadas
- `pandas`
- `seaborn`
- `matplotlib.pyplot`
  

---

## Instrucciones para ejecutar el notebook

1. Abrí el archivo `.ipynb` en **Google Colab** o **Jupyter Notebook**.  
2. Asegurate de tener instaladas las librerías necesarias:
   ```bash
   pip install pandas matplotlib
3. Ejecutá todas las celdas en orden.
4. El notebook cargará automáticamente los datos desde GitHub y generará las visualizaciones.


---   

## Análisis Realizado

### 1. Ingreso total por tienda
Se sumaron los valores de la columna **Precio** en cada dataset.  
   *La Tienda 1 presentó el mayor ingreso total.*

### 2. Ventas por categoría
Se agruparon los datos por **Categoría del Producto** para visualizar los productos más vendidos en cada tienda.

### 3. Valoración media por tienda
Se calculó el promedio de las calificaciones.  
  *La Tienda 3 obtuvo la mejor valoración promedio.*
   
### 4. Productos más y menos vendidos
Se analizaron los productos con mayor y menor número de ventas.  
  *Algunos productos muestran bajo rendimiento constante entre tiendas.*

### 5. Envío promedio
Se calculó el tiempo medio de envío para evaluar la eficiencia logística.
  

---

### Ejemplo de gráficos e insights

**1 Ingreso total por tienda**
  
![Ingreso total](./grafico_i

**2 Ventas por categoría**

![Ventas por categoría](./grafico_cat

**3 Costo de envío promedio**

![Costo de envío promedio](./grafico_en


---

##  Conclusión final


Tras analizar los datos de las cuatro tiendas de Alura Store, se observa que la Tienda 4 presenta el menor desempeño general en varios indicadores clave:

**- Ingreso total:** es la tienda con menor facturación total (≈ 1.038 millones, $1,038,375,700.00).

**- Categorías y ventas:** muestra menor volumen de ventas en la mayoría de las categorías, especialmente en Electrónica y Accesorios.

**- Valoración promedio:** los clientes califican sus productos con un promedio inferior al de las demás tiendas, reflejando menor satisfacción.

**-  Costo de envío promedio:** registra un costo de envío similar o superior al promedio general, lo que impacta negativamente en su competitividad y margen de ganancia.

En conjunto, estos factores evidencian que la Tienda 4 es la menos eficiente dentro del grupo analizado.

Por ello, se recomienda al Sr. Juan considerar vender la Tienda 4 y reinvertir el capital en su nuevo emprendimiento o en fortalecer las tiendas con mejor desempeño (como la Tienda 1 y la Tienda 2).

Además, se sugiere revisar estrategias de precios, logística y atención al cliente para mejorar la rentabilidad y la percepción de valor en futuras operaciones.



---

## Tecnologías utilizadas

- Python

- Pandas (para análisis de datos)

- Matplotlib (para visualizaciones)

- Google Colab (entorno de desarrollo)

- GitHub (para control de versiones y publicación del proyecto)


---

##  Autor
**Ivana Papaño**  
Desafío de Análisis de Datos - Alura LATAM

