# Ejercicio: Análisis de Datos de Ventas

[Back](../../../README.md)

## Contexto

Eres analista de una tienda en línea, y te han proporcionado un conjunto de
datos con información sobre las ventas. Tu objetivo es responder preguntas
clave que ayudarán a tomar decisiones de negocio.

## Dataset

Imagina que tienes un archivo CSV llamado `ventas.csv` con las siguientes
columnas:

- `id_venta`: Identificador único de la venta.
- `fecha`: Fecha de la venta en formato `AAAA-MM-DD`.
- `producto`: Nombre del producto vendido.
- `categoria`: Categoría del producto.
- `precio`: Precio unitario del producto.
- `cantidad`: Cantidad vendida.
- `ingreso`: Ingreso total generado por la venta (calculado como
  `precio * cantidad`).

## Instrucciones

1. Carga de datos:
    - Lee el archivo [ventas.csv](./ventas.csv) en un DataFrame usando pandas.
    - Inspecciona las primeras filas y obtén información básica (número de
      filas, columnas y tipos de datos).

2. Análisis Exploratorio:
    - Calcula el ingreso total generado por todas las ventas.
    - Identifica las cinco categorías con mayores ingresos.
    - Calcula el ingreso promedio por venta.

3. Análisis por Producto:
    - Encuentra el producto más vendido (por cantidad) y el producto con
      mayores ingresos.
    - Crea una nueva columna llamada `ingreso_por_unidad` que muestre el
      ingreso generado por unidad vendida para cada venta.

4. Fechas y Tendencias:
    - Convierte la columna `fecha` a formato de fecha.
    - Agrupa las ventas por mes y calcula el ingreso total mensual.

5. Tarea Adicional (opcional):
    - Encuentra los días con ingresos por debajo del ingreso promedio.
    - Calcula el porcentaje de ventas que pertenecen a cada categoría.

## Resultado esperado

Los estudiantes deben entregar un archivo Jupyter Notebook con el código
implementado y una breve explicación de cada paso.
