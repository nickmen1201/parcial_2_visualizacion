# Universidad Pontificia Bolivariana
## Visualización de la Informacion
### Segundo Parcial

**Tiempo:** 2 hora 45 minutos.
**Material permitido:** Solamente el material suministrado por el profesor a cada estudiante.

El valor total del examen son 5 puntos, el valor de cada problema se lee entre paréntesis. Debe detallar lo más posible cada paso de la solución.

**NOMBRE:** ______________________  **ID:** ______________

---

## Problema 1 (1.6 puntos)

Utilizando el set de datos `/data/Sample-Superstore.xls`. Construya una visualización de pequeños múltiples de la distribución espacial de los ingresos (Sales) y ganancias (Profit) por ciudades, asigne el atributo visual del tamaño del circulo al ingreso y la intensidad del color a la ganancia, los múltiples serian por año (OrderDate) y categoría de producto (Category).

¿Que ha pasado a la distribución espacial de las ganancias y la distribución espacial de los ingresos de los productos de tecnología en el tiempo? ¿hay alguna otra categoría a la que le este pasando algo interesante?

---

## Problema 2 (1.7 puntos)

Volvamos a utilizar la data sobre los accidentes de aviones `/data/lifeplane.csv`. Construya la visualización de la cantidad de eventos a través de los años. Queremos describir el patrón visual que se observa pero para no dejarnos llevar por las fluctuaciones entonces construya en la misma gráfica la curva del promedio móvil utilizando dos puntos hacia atrás en cada calculo.

**a)** ¿Cuál es el patrón temporal que observa ahora?

**b)** Repita el proceso para cada Investigation Type (Incidente, Accidente). ¿Cuales son los patrones que observas en estos dos nuevos gráficos y cómo cada uno contribuyen a describir lo observado en el primer gráfico? Muestre las gráficas obtenidas.

**Sugerencia:** Tableau genera un campo llamado `lifePlane.csv(Recuento)` que cuenta la cantidad de filas en la fuente de datos. Cada fila corresponde a un evento.

---

## Problema 3 (1.7 puntos)

Usted es analista de marketing de la compañía y posee la data de los Ingresos y Numero de Anuncios de televisión para cada uno de los últimos 20 meses. Usted ha descubierto a través de un análisis que los Ingresos se han beneficiado significativamente con el Numero de Anuncios de televisión. Es necesario presentar estos beneficios al Director General. Indique que relación cuantitativa es la que se necesita expresar visualmente y explique porque. Construya la visualización con los datos en `/data/marketing.csv`. ¿Que patrones visuales observa?

---

## Lifeplane.csv

| Nombre del Campo | Tipo de Campo | Descripcion | Ejemplo |
|---|---|---|---|
| Model | Cadena | Modelo de avión | CL-600 |
| Investigation_type | Cadena | Accidente o Incidente aereo | Accident |
| Event_date | Fecha | Fecha del accidente o incidente | 9/17/00 |
| Location | Cadena | Ciudad o lugar del evento | "ATLANTA, GA" |
| Country | Cadena | Pais donde ocurrió el evento | United States |
| Aircraft_Damage | Cadena | Evaluacion del daño | Substantial |
| Make | Cadena | Fabricante | Bombardier |
| Fatal_Injuries | Numero | Numero de fallecidos | 11 |
| Intro | Fecha | Fecha en la que el modelo fue introducido al mercado | 1/1/92 |
| Outro | Fecha | Fecha en que el modelo salió del mercado. En caso de que el modelo aun estuviera operado hasta la fecha de colección de los datos (21 de Septiembre del 2017) la fecha que aparece es 9/21/17 | 1/1/07 |
| Operational_Count | Numero | Cantidad de vuelos realizado por el modelo hasta la fecha del 21 de Septiembre del 2017. Recuerde que este es un dato del modelo por lo que su valor se repite en todas las filas en las que el accidente o incidente sea del mismo modelo | 1054 |
| Is_Operational | Boolean | No: si el modelo no estaba operando a la fecha del 21 de Septiembre 2017. Yes: si el modelo estaba operando a la fecha del 21 de Septiembre del 2017 | No |
