# supermarket-sales-cleaning-project
"Proyecto de limpieza de datos del dataset de Supermarket Sales"
Proyecto de Limpieza de Datos - Supermarket Sales Dataset

Este proyecto tiene como objetivo limpiar y procesar el dataset "Supermarket Sales" para prepararlo para su uso en Machine Learning. 
A través de este proyecto, he realizado una serie de pasos de limpieza y transformación de datos utilizando Python y la librería Pandas

Descripción del Proyecto

El dataset contiene información sobre las ventas de un supermercado, incluyendo detalles sobre la sucursal, los productos, el cliente y otros aspectos relevantes de las transacciones. 
El objetivo es limpiar y transformar estos datos para que estén listos para su análisis o uso en modelos de Machine Learning.

Pasos realizados:
- Carga y revisión de los datos: Inspección inicial del dataset con df.info() y df.head().
- Renombrar columnas: Traducción y renombramiento de columnas para mayor claridad.
- Eliminación de duplicados: Verificación y eliminación de registros duplicados.
- Manejo de valores nulos: Identificación y tratamiento de valores nulos en las columnas.
- Conversión de tipos de datos: Conversión de columnas a tipos adecuados, como fechas (datetime) y categorías (category).
- Revisión de datos: Exploración de los datos con estadísticas descriptivas y análisis preliminar.

Instrucciones para Ejecutar el Proyecto

1. Clonar el repositorio
Puedes clonar este repositorio en tu máquina local con el siguiente comando:

git clone https://github.com/amonfiver/supermarket-sales-cleaning-project.git

2. Instalar dependencias
Este proyecto requiere de algunas librerías de Python. Puedes instalarlas usando pip:

pip install pandas numpy

3. Ejecutar el notebook
Una vez instaladas las dependencias, abre el archivo Supermarket_Sales_Cleaning.ipynb con Jupyter Notebook o cualquier otro entorno compatible para Python. Ejecuta cada celda para ver el proceso de limpieza paso a paso.

jupyter notebook Supermarket_Sales_Cleaning.ipynb

Detalles del Dataset

El dataset incluye las siguientes columnas:

1. ID de factura: Identificador único para cada venta.
2. Sucursal: La sucursal del supermercado donde se realizó la venta.
3. Ciudad: Ciudad en la que se encuentra la sucursal.
4. Tipo de cliente: Tipo de cliente (ej. Regular, VIP).
5. Género: Género del cliente.
6. Línea de productos: Categoría del producto (ej. Electrónica, Ropa, etc.).
7. Precio unitario: El precio de una unidad del producto.
8. Cantidad: Cantidad de productos vendidos.
9. Impuesto 5%: El impuesto aplicado al precio del producto.
10. Total: El total de la venta, incluyendo impuestos.
11. Fecha: Fecha en que se realizó la venta.
12. Hora: Hora en que se realizó la venta.
13. Pago: Método de pago (ej. Efectivo, Tarjeta).
14. Costo de ventas: El costo total de los productos vendidos.
15. Porcentaje de margen bruto: El margen de ganancia sobre el costo.
16. Ingresos brutos: Los ingresos obtenidos de la venta antes de impuestos.
17. Calificación: Calificación de la transacción, dada por el cliente.

Resultados de la Limpieza

- Columnas renombradas: Para facilitar la comprensión del dataset.
- Duplicados eliminados: No se encontraron registros duplicados.
- Valores nulos: Se manejaron los valores nulos con técnicas de relleno o eliminación según la columna.
- Tipos de datos corregidos: Las columnas de fechas y categorías fueron convertidas a sus tipos adecuados (datetime64[ns], category).

Conclusiones

Este proyecto muestra cómo preparar un dataset de ventas para su uso en modelos de Machine Learning, asegurando que los datos estén limpios, correctamente formateados y sin duplicados ni valores nulos.

Contacto


- Correo electrónico: amonfiver@gmail.com
