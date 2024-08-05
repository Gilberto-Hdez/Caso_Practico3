# Caso_Practico3

Objetivo
Identificar cuáles son los productos del menú que han tenido más éxito y cuales son los que
menos han gustado a los clientes.

Pasos a seguir
a) Crear la base de datos con el archivo create_restaurant_db.sql

b) Explorar la tabla “menu_items” para conocer los productos del menú.
1.- Realizar consultas para contestar las siguientes preguntas:

● Encontrar el número de artículos en el menú. El menú cuenta con 32 platillos.

● ¿Cuál es el artículo menos caro y el más caro en el menú? El articulo con menor costo es el Edamame con un costo de 5 y el de mayor costo es el Shrimp Scampi cuyo costo es de 19.95.

● ¿Cuántos platos americanos hay en el menú? La categoría de comida americana cuenta con 6 platos.

● ¿Cuál es el precio promedio de los platos? El promedio por platilo es de 13.29.

c) Explorar la tabla “order_details” para conocer los datos que han sido recolectados.
1.- Realizar consultas para contestar las siguientes preguntas:

● ¿Cuántos pedidos únicos se realizaron en total? Se realizaron 12,234 pedidos únicos.

● ¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos? Los pedidos con mayor cantidad de artículos son la orden 440, 443, 2675, 3473, 4305 con 14 artículos pedidos en cada una de estas.

● ¿Cuándo se realizó el primer pedido y el último pedido? El primer pedido se realizo el 2023-01-01 y el ultimo el 2023-03-31.

● ¿Cuántos pedidos se hicieron entre el '2023-01-01' y el '2023-01-05'? En este periodo de tiempo hubo 702 pedidos.

e) Una vez que hayas explorado los datos en las tablas correspondientes y respondido las
preguntas planteadas, realiza un análisis adicional utilizando este join entre las tablas. El
objetivo es identificar 5 puntos clave que puedan ser de utilidad para los dueños del
restaurante en el lanzamiento de su nuevo menú. Para ello, crea tus propias consultas y
utiliza los resultados obtenidos para llegar a estas conclusiones.
1.- El platillo preferido por los conmensales son las hamburger.
2.- El platrillo con menor numero de ventas son los chicken tacos.
3.- La categoría de platos menos vendida es la americana, esto apesar de que el platillo más consumido pertenece a esta.
4.- La categoría prefererida es comida asian.
5.- El top 3 de platilos son las hamburguer, edamame y el korean beef bowl, en el order mencionado.
