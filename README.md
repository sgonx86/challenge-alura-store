Alura Store Latam - Análisis de Tienda

Objetivo del Proyecto

Analizar los datos de ventas, productos, calificaciones y envíos de cuatro tiendas online ficticias (Tienda 1 a Tienda 4) proporcionadas por Alura Latam. El propósito final es determinar cuál de estas tiendas representa la mejor oportunidad estratégica para que el "Sr." enfoque sus esfuerzos de venta, basándose en un análisis comparativo de su desempeño.

# Fuentes de datos

Los datos utilizados provienen de cuatro archivos CSV, cada uno representando una tienda diferente:

tienda_1 .csv
tienda_2.csv
tienda_3.csv
tienda_4.csv

Los archivos csv de datos contienen información sobre transacciones, incluyendo detalles del producto, precios, costos de envío, fechas, calificaciones de clientes y ubicaciones geográficas.

# Herramientas usadas

El análisis se realizó utilizando Python y las siguientes bibliotecas principales:

- Python 3.x
- Pandas: Para la manipulación, limpieza y agregación de datos.
- Matplotlib & Seaborn: Para la creación de visualizaciones y gráficos comparativos.
- Jupyter Notebook: Como entorno interactivo para el desarrollo del análisis y la documentación del proceso (AluraStoreLatam.ipynb).
- Google Collab
- Google Drive

# Resumen del Análisis Realizado

Se llevaron a cabo los siguientes análisis comparativos entre las cuatro tiendas:

- Ingresos Totales: Comparación de la facturación total generada por cada tienda.
- Ventas por Categoría: Análisis de la cantidad de productos vendidos por categoría, identificando las más y menos populares en cada tienda.
- Calificación Promedio: Calculo y comparación de la satisfacción promedio de los clientes basada en sus calificaciones.
- Productos Más/Menos Vendidos: Identificación de los productos específicos con mayor y menor volumen de ventas (unidades) en cada tienda.
- Costo de Envío Promedio: Comparación del gasto promedio en envíos por transacción para cada tienda.


# Hallazgos Importantes y Vistas

El análisis revelde las tiendas:

Tienda 1: Lidera en ingresos totales pero tiene la calificación promedio más baja y los costos de envío más altos.
Tienda 2: Rendimiento sólido y equilibrado, muy cercano a Tienda 3.
Tienda 3: Destaca por la mayor satisfacción del cliente (calificación promedio más alta) y un fuerte volumen de ventas en la categoría principal ("Muebles"), con costos de envío competitivos.
Tienda 4: Ofrece los costos de envío más bajos pero tiene los ingresos totales más bajos.
Se generaron diversos gráficos (barras, dispersión, pastel) para visualizar estas comparaciones, incluyendo:

Ventas totales por tienda.
Calificación promedio por tienda.
Distribución de categorías (ejemplo Tienda 1).
Relación Precio vs. Costo de Envío.
Distribución geográfica de las ventas.

# Recomendaciones

Basado en la combinación de factores (alta satisfacción del cliente, fuerte desempeño en categorías clave, ingresos sólidos y costos de envío razonables), se concluyó que la Tienda 3 representa la oportunidad estratégica más equilibrada y prometedora para el Sr.

# Como ejecutar este analisis de datos

1. Clonar este repositorio (si aplica) o descargar el archivo .ipynb y los archivos .csv.
2. Asegurarse de tener Python y las bibliotecas requeridas instaladas:pip install pandas matplotlib seaborn
3. Abrir y ejecutar el notebook AluraStoreLatam.ipynb en un entorno Jupyter (como Jupyter Lab, Jupyter Notebook clásico, o Google Colab). Las celdas deben ejecutarse en orden.
