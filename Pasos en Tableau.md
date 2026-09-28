# Parcial 2 - Pasos en Tableau

Archivo: `Parcial 2 - Visualizacion - Nicolas Meneses.twbx` (incluye los tres archivos de datos).

## Problema 1

1. Conectar a `Sample - Superstore.xls`, hoja `Orders`.
2. Doble clic en `City` (Tableau genera Latitud y Longitud). Agregar `State/Province` y `Country/Region` a Detalle.
3. Tipo de marca: Círculo.
4. `SUM(Sales)` a Tamaño y `SUM(Profit)` a Color (paleta divergente: naranja = pérdida, azul = ganancia).
5. `YEAR(Order Date)` a Columnas y `Category` a Filas, para obtener los múltiplos (3 categorías x 4 años).

## Problema 2

1. Conectar a `lifePlane.csv`.
2. `YEAR(Event_Date)` a Columnas y `lifePlane.csv (Recuento)` a Filas. Marca: Línea.
3. Campo calculado `Promedio móvil (3 años)`: `WINDOW_AVG(COUNT([Investigation_Type]), -2, 0)`, es decir, el año actual y los dos anteriores. Calcular usando: Tabla (horizontal).
4. Llevar el campo calculado a Filas, Eje doble y Sincronizar eje. Recuento en gris, promedio móvil en azul.
5. Para el literal b, duplicar la hoja y agregar `Investigation_Type` a Filas (antes de las medidas).

## Problema 3

1. Conectar a `marketing.csv` (separador `;`).
2. `Numero_Anuncios_de_TV` a Columnas, `Ingresos_en_dolares` a Filas, `Mes` a Detalle y Etiqueta. Marca: Círculo.
3. Analítica > Línea de tendencia lineal (R² = 0,61; pendiente de unos 881 USD por anuncio).

Las respuestas de cada problema están en los dashboards `Problema 1`, `Problema 2` y `Problema 3`.
