# SQLCaso
Este repositorio presenta un caso práctico de análisis de datos con SQL, enfocado en las ventas y el menú de un restaurante. Incluye consultas para identificar los platillos más vendidos, analizar patrones de consumo y optimizar las estrategias del menú

## Preguntas a responder

Encontrar el número de artículos en el menú.

32


¿Cuál es el artículo menos caro y el más caro en el menú?

- MENOS CARO: EDAMAME

- MÁS CARO: SHRIMP SCAMPI


¿Cuántos platos americanos hay en el menú?

6


¿Cuál es el precio promedio de los platos?

13.29


¿Cuántos pedidos únicos se realizaron en total?

5370


¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos?

- 440
- 2675
- 3473
- 4305
- 443


¿Cuándo se realizó el primer pedido y el último pedido?

- Primero: 2023-01-01

- Último: 2023-03-31


¿Cuántos pedidos se hicieron entre el "2023-01-01" y el "2023-01-05"?

308


---

# Análisis Adicional

Ademas se encontro que el item mas vendido es la hamburguesa y el menos vendido los chicken tacos

- La hamburguesa tuvo un total de 622 órdenes, generando un retorno de $8054.90.
- Los tacos tuvieron un total de 123 órdenes, generando un retorno de $1469.85.


Estos son los items mas vendidos y el retorno en las 5 ordenes mas caras, en donde la orden mas cara fue de 192.15

- Eggplant Parmesan con 7 ordenes, retorno de 118.65
- Chicken Parmesan con 4 ordenes, retorno de 71.80
- Spaghetti and meatballs con 4 ordenes, retorno de 71.80


Estos son los 5 items del menu que menos retorno dejan

| Producto              | Ingreso   |
|-----------------------|-----------|
| Chicken tacos         | $1469.85  |
| Potstickers           | $1845     |
| Chips & Guacamole     | $2133     |
| Hot Dog               | $2313     |
| Cheese Quesadillas    | $2446.50  |

---
La orden mas barata es de edamames de $5 
El promedio gastado por orden es de $29.80

---

Monthly Returns with Order Count, Revenue, Top 3 Best-Selling Products, and Top 3 Least-Selling Products
---
| **Mes**    | **Órdenes Totales** | **Ingresos Totales** | **Más Vendidos**                               | **Menos Vendidos**                          |
|------------|---------------------|----------------------|------------------------------------------------|---------------------------------------------|
| 2023-01    | 1,835               | $53,816.95           | Edamame, Hamburger, French Fries               | Chicken Tacos, Steak Tacos, /               |
| 2023-02    | 1,675               | $50,790.35           | Edamame, Cheeseburger, Korean Beef Bowl        | Chicken Tacos, Potstickers, Cheese Lasagna  |
| 2023-03    | 1,833               | $54,610.60           | Hamburger, Korean Beef Bowl, French Fries      | Chicken Tacos, Steak Tacos, Potstickers     |

De estos 3 meses, marzo fue el mejor en retorno y enero fue el mejor en ordenes

De todo el menu este es el top 5 de productos que mas retorno deja

- **Korean Beef Bowl**: $10,554.60  
- **Spaghetti & Meatballs**: $8,436.50  
- **Tofu Pad Thai**: $8,149.00  
- **Cheeseburger**: $8,132.85  
- **Hamburger**: $8,054.90  

## Top 10
| **Item Name**           | **Cantidad Vendida** | **Precio Unitario** | **Retorno Total** |
|--------------------------|----------------------|---------------------|-------------------|
| Korean Beef Bowl         | 588                  | $17.95               | $10554.60          |
| Spaghetti & Meatballs    | 470                  | $17.95               | $8436.50           |
| Tofu Pad Thai            | 562                  | $14.50               | $8149.00           |
| Cheeseburger             | 583                  | $13.95               | $8132.85           |
| Hamburger                | 622                  | $12.95               | $8054.90           |
| Orange Chicken           | 456                  | $16.50               | $7524.00           |
| Eggplant Parmesan        | 426                  | $16.75               | $7119.00           |
| Steak Torta              | 489                  | $13.95               | $6821.55           |
| Chicken Parmesan         | 364                  | $17.95               | $6533.80           |



## Estos son los items menos pedidos 

| **Item Name**        | **Enero** | **Febrero** | **Marzo** | **Retorno Enero** | **Retorno Febrero** | **Retorno Marzo** |
|-----------------------|-----------|-------------|-----------|-------------------|---------------------|-------------------|
| California Roll       | 135       | 113         | 107       | $1613.25           | $1350.35             | $1278.65           |
| Cheese Lasagna        | 66        | 64          | 77        | $1023.00           | $992.00              | $1193.50           |
| Cheese Quesadillas    | 79        | 76          | 78        | $829.50            | $798.00              | $819.00            |
| Cheeseburger          | 197       | 200         | 186       | $2748.15           | $2790.00             | $2594.70           |
| Chicken Burrito       | 166       | 141         | 148       | $2149.70 
