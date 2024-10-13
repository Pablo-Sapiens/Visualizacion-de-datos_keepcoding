## Fecha : 13/10/2024
## Alumno: Pablo Aguinaga
## Profesor: José Antonio Gascón Pinedo
## Dataset : airbnb



## Comentarios: 

El dataset airbnb se compone de muchos campos que se pueden agrupar de la siguiente manera: 

	1. ID apartamento y descripción breve.
	2. Información y características del host.
	3. Localización geográfica
	4. Características del apartamento : amenities, baños, habitaciones, tipo, políticas etc..
	5. Precios.
	6. Reviews.
	
En el Dashboard me he centrado en las agrupaciones que he considerado más relevantes: precios y reviews. Y lo he cruzado con otro dataset (N veces alquilado), para evaluar también el impacto que tiene en el número de alquilares.

Una vez realizada la limpieza y transformación de los campos he añadido las siguientes columnas al dataset, con el objetivo de segmentar los apartamentos según su zona geográfica y según el número de huéspedes. Las nuevas columnas son : 
	1. category: individual, doble, familiar o multfamiliar.
	2. Zone : norte, centro y sur.


## Preguntas a las que responde el Dashboard: 

1. precios: 
¿Cómo cambian los precios en función de la categoría del apartamento? Precio máximo, mínimo y promedio. Evolución anual
¿Cuál es la evolución de precios anual en función de la zona?
¿Cuantas veces se alquilan los apartamentos en función de la zona? 

2. Reviews: 
¿ Cómo evolucionan las reviews en función de la categoría del apartamento? evolución anual.
¿Cúantas reviews tenemos en función de la zona? 
¿Cómo evoluciona cada una de las reviews ? evolución anual.
¿Cómo son las reviews en función de la zona y barrio? 