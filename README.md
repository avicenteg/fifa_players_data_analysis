# Análisis de datos FIFA 17

## Autores
+ Pablo Román-Naranjo Varela
+ Adrián Vicente Gómez

## Antecedentes
En la actualidad, el fútbol forma parte de nuestra vida cotidiana y es el **deporte con mayor impacto social**. Aunque no deja de ser un videojuego, FIFA maneja tantos detalles sobre los jugadores que los ojeadores y los empleados de los clubes lo usan como herramienta para buscar nuevos jugadores que de otra manera no podrían ver. Por ello, realizar un análisis estadístico de los datos de este juego podría permitir arrojar cordura por encima de los sentimientos a la hora de tomar diferentes decisiones

## Justificación
Este repositorio es parte de la segunda práctica de la asignatura Tipología y Ciclo de Vida de los Datos del **Máster en Ciencia de Datos** de la UOC. El dataset utilizado, fifa.csv, está disponible en [Kaggle](https://www.kaggle.com/artimous/complete-fifa-2017-player-dataset-global). Este dataset contiene las estadísticas de los jugadores en el videojuego Fifa 17.

## Objetivo principal y específicos
El **objetivo principal** de esta práctica será el tratamiento del dataset, llevando a cabo su limpieza, análisis y representación. Los **objetivos específicos** de este proyecto son dar respuesta a diversas preguntas mediante análisis de datos. Por ejemplo:

+ Si en el año 2017, la diferencia entre valoración global entre los jugadores del Real Betis y el Real Madrid era mayor a 5 puntos.
+ Si existe correlación entre la media de un jugador y el hecho de que sea convocado o no con su selección nacional.
+ Obtener un modelo de regresión que nos permita estimar la valoración de un jugador a partir de un subjconjunto de sus atributos.

## Descripción del dataset
El dataset, fifa.csv, contiene 17588 filas con 53 variables diferentes para describir a cada jugador. Entre estas variables nos encontramos con las siguientes:

+ Name (Nombre del jugador)
+ Nationality (Nacionalidad del jugador)
+ National_Position (Posición de juego en equipo nacional).
+ National_Kit (Número de equipación en equipo nacional)
+ Club (Nombre del club)
+ Club_Position (Posición de juego en club)
+ Club_Kit (Número de equipación en club)
+ Club_Joining (Fecha en la que empezó en el club)
+ Contract_Expire (Año finalización del contrato)
+ Rating (Valoración global del jugador, entre 0 y 100)
+ Height (Altura)
+ Weight (Peso)
+ Preffered_Foot (Pie preferido)
+ Birth_Date (Fecha de nacimiento)
+ Age (Edad)
+ Preffered_Position (Posición preferida)
+ Work_Rate (valoración cualitativa en términos de ataque-defensa)
+ Weak_foot (valoración de 1 a 5 de control y potencia de la pierna no preferida)
+ Skill_Moves (valoración de 1 a 5 de la habilidad en movimientos del jugador)
+ El resto de variables son los distintos atributos que definen a un jugador en este juego.

## Licencia
Este proyecto y los datasets son publicados bajo licencia CC BY-NC-SA 4.0. [Más info](https://github.com/avicenteg/euraxess_scraping/blob/master/LICENSE.md).
