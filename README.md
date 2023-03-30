# Evolucion de los videos juegos en la historia
## Data Evolution Games
Es un proyecto de analisis de datos que busca explorar y responder algunas preguntas sobre como ha evolucionado la industria de los videos y sus ventas a lo largo de los años, algunas noticias han dado ha entender que esta industria ha desminuido sus ventas o al menos ha perdido territorio, es por eso que decidi hacer mi propio analisis de datos y encontrar hallazgos importantes.

### Tecnologias usadas
- SQL (postgresql)
- Pandas
- Tableau

### Interrogantes del negocio a responder con el analisis de datos y visualizacion.

- TOP 10 de  juegos mas vendidos en la historia
- TOP 10 de plataformas con la mayor venta de videos juegos
- TOP 10 de años con mas ventas en la industria de los video juegos
- Ventas y lanzamientos por año a lo largo de la historia de los video juegos
- Ventas de videos juegos y lanzamientos para las plataformas mas populares a lo largo de los años en la historia de los video juegos.

Es importante tomar en cuenta que la columa **SALES** hace referencia a copias vendidas y esta representada en millones.

#### Cuales son los videos juegos mas vendidos de la historia?
![TOP 10 DE VIDEO JUEGOS](https://live.staticflickr.com/65535/52781950796_ecc5af343b_c.jpg "TOP 10 DE VIDEO JUEGOS")

En esta grafica ademas de un top 10 que compara la proporcion de copias vendidas por video juegos,  podemos evidenciar a que plataforma pertenece cada juego que acumulo mas ventas en este top.

#### Cuales son las plataformas con mas ventas de video juegos en la historia?

![TOP PLATAFORMAS CON MAS VENTAS](https://live.staticflickr.com/65535/52782425218_15f6736c29_w.jpg "TOP PLATAFORMAS CON MAS VENTAS")

Podemos ver un top 10 de plataformas con la mayor cantidad de copias vendidas donde las PC figuran como la plataforma con la mayor venta de video juegos, en la historia, cabe recalcar que PC esta como una sola plataforma, en cambio las consolas estan dividas por modelo de consola, de igual manera es un buen partida para darnos cuenta que ninguna consola acumulo mas ventas que la PC como plataforma unica en la historia.

#### Cuales son los años dorados de los videos juegos? tomando en cuenta la mayor cantidad de copias de juegos vendidas por años?

![Años con mas Ventas](https://live.staticflickr.com/65535/52781441942_274be33e45_c.jpg "Años con mas Ventas")

Esta lista la encabeza el año 2010 como el año en que mas video juegos se vendieron tomando en cuenta desde los inicios  de los videos juegos hasta el 2020, seguido por el año 2011 y 2006 superando estos mencionados las mas de 200 millones de copias vendidas, parace increible no? para este punto la industria de los video juegos cada dia tomaba mas terreno.

#### Ventas y lanzamientos de video juegos a lo largo de los años, han disminuido o aumentado? las ventas estan relacionadas con  los lanzamientos realizados por años?

![Ventas y lanzamientos por años](https://live.staticflickr.com/65535/52782252709_36ef5df3ce_w.jpg "Ventas y lanzamientos por años")

Este grafico aunque es el mas sencillo me parece que tiene informacion muy relevante, ya que muestra la fluctuacion de las ventas a lo largo de los años (Linea Azul) pero me di cuenta que en todos los años donde las ventas disminuyeron hubo menos lanzamientos (Circulos azules), ahora bien respondiendo a la pregunta podemos observar que el arranque de los video juegos se catapulto en muy pocos años pero de la misma manera en los ultimos años tuvo una disminucion increible, ahora bien porque se disminuyeron los lanzamientos? acaso las plataformas se anticiparon a sus predicciones de ventas futuras? usted que dicen? aunque mas adelante veremos una plataforma que aunque sus ventas disminuyeron, en terminos generales aunque tambien bajaban sus lanzamientos, las ventas se mantenian en un rango bastante aceptable para ser una nueva plataforma o consola.

#### Como se comportaron las ventas para las plataformas mas populares a lo largo de la ultima decada en el mercado? hubo hegemonia por parte de alguna o una nueva consola rompio el promedio de las mas antiguas?

![Promedio movil por plataforma](https://live.staticflickr.com/65535/52781510102_cccee6be30_z.jpg "Promedio movil por plataforma")

Elegir plataformas mas populares podria estar sesgada por los gustos personales pero habia que elegir y yo elegi 4, haciendo un promedio movil con una venta de 2 años para evitar picos que afectaran la visualizacion.

Podemos observar que para el 2013 habia una competencia clara entre PC y PS4 como las plataformas con mas copias vendidas y que para ese año ambas tuvieron un impulso alcista, es decir que su popularidad estaba en aumento y eran preferidas por muchos usuarios, para el 2017 llego Nintendo Switch, una consola que arranco vendiendo el triple que PC y PS4 en el año anterior a su salida y no solo eso mientras Nintendo Switch aumentaba sus ventas para ese mismo año PC y PS4 llevaban una tendencia a la baja, ustedes que piensan, destrono nintendo switch a PC y PS4 como plataformas preferidas? prefirieron los usarios los juegos vintage como Mario Kart y compañia? me gusta creer que si.

Si tienes un Nintendo Switch debes estar reafirmando que hiciste una buena compra.

Como conclusion, se evidencia una caida que podria considerarse catastrofica en los ultimos años de los videos juegos o  al menos hasta el 2020, habra recuperado terrendo esta industria? lo averiguaremos en cuanto tengamos los datos que se hayan recopiado desde el 2020 hasta la presente fecha.

#### Dashboard completo
![Dashboard](https://live.staticflickr.com/65535/52782079201_f0694056a9.jpg "Dashboard")

Si quieres interactuar con este dashboard puedes hacerlo a traves de mi cuenta de Tableau Public, aca te dejo el enlace [Tableau Public](http://https://public.tableau.com/views/Visualizaciones_16801965730580/Dashboard1?:language=es-ES&:display_count=n&:origin=viz_share_link "Tableau Public")

#### Desarrollo
Si quieres ver como se desarrollo el proceso de consultas con SQL sobre la base de datos puedes revisar el archivo main de este repositorio donde tambien encontraras otros puntos relevantes que no fueron visualizados, pero que te podrian interesar.

#### Redes Sociales
Si quieres dejarme un mensaje con respecto a este analisis o cualquier otro tema puedes hacerlo en mis redes sociales [Twitter](http://https://twitter.com/madriz03 "Twitter") / [Linkedin](http://https://www.linkedin.com/in/javiermadriz3/ "Linkedin")

#### Data
Si quieres hacer tu propio analisis dobre este tema te dejo el enlace donde podras descargar la data  [Kaggle dataset](http://https://www.kaggle.com/datasets/holmjason2/videogamedata "Kaggle dataset")
