# analitica-arboles-regresion
Proyecto final para la materia de "Analítica basada en árboles de clasificación y regresión"

El problema a resolver es el siguiente:

José es un diseñador de juegos de mesa. Crea las reglas, diseña los gráficos, escoge su tema, número de jugadores y duración promedio del juego que tiene en mente. José es una persona tímida, y a pesar de que sus juegos suelen gustarle a sus amigos, él nunca ha querido publicarlos por miedo a que no sean bien recibidos. Se quiere demostrar a José, con una base de datos de calificaciones históricas de juegos de mesa, cómo hubieran sido recibidos sus juegos en promedio en la época que los fue creando.

Los datos a utilizar vienen de esta base de datos: https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-03-12; que, en cambio, vienen de la página Board Game Geek. Las características que tiene este dataset son:

|variable       |description |
|:--------------|:-----------|
|game_id        | Identificador único         |
|description    | Descripción corta       |
|image          | URL con imagen del juego    |
|max_players    | Jugadores máximos           |
|max_playtime   | Tiempo máximo de juego           |
|min_age        | Edad mínima          |
|min_players    | Jugadores mínimos         |
|min_playtime   | Tiempo mínimo de juego           |
|name           | Nombre del juego           |
|playing_time   | Tiempo promedio de juego           |
|thumbnail      | URL con thumbnail del juego           |
|year_published | Año de publicación           |
|artist         | Diseñador gráfico del juego           |
|category       | Categorías del juego (separadas por coma)           |
|compilation    | Si es parte de una compilación, nombre de la compilación           |
|designer       | Diseñador del juego           |
|expansion      | Si hay una expansión, el nombre de la expansión           |
|family         | Familia, equivalente a editora          |
|mechanic       | Mecánicas, separadas por coma         |
|publisher      | Compañía o persona que publicaron el juego (separadas por coma)        |
|average_rating | Calificación promedio en Board Game Geek        |
|users_rated    | Número de usuarios que calificaron el juego           |  
