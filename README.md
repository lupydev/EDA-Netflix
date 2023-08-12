<!-- ![Logo_netflix](./Imagenes/Netflix.png) -->
<img src='/Imagenes/Netflix.png' width = 1000 heigth=500>


## Developers

| <img src="https://res.cloudinary.com/diyk4to11/image/upload/v1664465504/Integrantes/LuisMi_yvmw6a.png" width=50>| <img src="https://avatars.githubusercontent.com/u/92761637?v=4" width=50>|
|:-:|:-:|
| **LuMi**| **Naren**|
| <a href="https://github.com/lumiguz"><img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a> <a href="https://www.linkedin.com/in/dataluis/"><img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a> | <a href="https://github.com/Naren-7"><img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a> <a href="https://www.linkedin.com/in/narenfragozo7/"><img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a> |



# Análisis exploratorio de datos de Netflix

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre el contenido de Netflix.


## Dataset
El dataset utilizado es una base de datos de títulos de películas y series disponibles en Netflix del 1945 al 2023. El dataset cuenta con más de 6137 registros/filas y 15 variables.
[**🔗 Link de la fuente de datos**](https://www.kaggle.com/datasets/dgoenrique/netflix-movies-and-tv-shows?select=credits.csv)

## Variables

Las variables incluidas en el dataset son las siguientes:

- `id`: identificador único de cada título.
- `title`: título del programa o película.
- `type`: indica si el título es una película o un programa de televisión.
- `description`: una descripción breve del título.
- `release_year`: el año de lanzamiento del título.
- `age_certification`: la clasificación por edad del título (Ej: PG, R, TV-14, etc.).
- `runtime`: la duración en minutos para las películas o el número de temporadas para los programas de televisión.
- `genres`: el género o géneros del título.
- `production_countries`: los países donde se produjo el título.
- `seasons`: el número de temporadas que tiene el programa de televisión.
- `imdb_id`: el identificador único de la película o programa de televisión en la base de datos de IMDB.
- `imdb_score`: la calificación que tiene el título en IMDB.
- `imdb_votes`: el número de votos que tiene el título en IMDB.
- `tmdb_popularity`: la popularidad del título en la base de datos de TMDB.
- `tmdb_score`: la calificación que tiene el título en la base de datos de TMDB.

## Objetivos del análisis exploratorio de datos

Los objetivos principales del análisis exploratorio de datos son los siguientes:

1. ¿Cuáles son las variables y tipos de datos presentes en el conjunto de datos?
2. ¿Hay más películas o series en el conjunto de datos?
3. ¿Cuáles son las 10 películas y series más populares según el ranking?
4. ¿Cuál es el país que produce más contenido en comparación con el país que produce menos contenido?
5. ¿Qué país produce más contenido, series o películas?
6. ¿Cuáles son las palabras que más se repiten en la descripción de las películas y series?
7. ¿Cuál es la película y serie con la mayor duración?
8. ¿Cuáles son las 10 películas y series con mayor número de puntaje?
9. ¿Quiénes son los actores y directores de las películas más populares?
10. ¿Quiénes son los directores más populares en cada región?
11. ¿Cuál es la mejor película de cada década según el puntaje de IMDB?

## Resultados

Los resultados del análisis exploratorio de datos se presentan en el archivo `EDA_Netflix.ipynb`. En este archivo se incluyen visualizaciones y estadísticas descriptivas que responden a los objetivos planteados.

Entre los hallazgos más destacados se encuentran:

- Se ha observado que los usuarios tienden a otorgar una calificación más alta a las series que a las peliculas.
- Se pudo observar que las películas con la duración más larga fueron "A Lion in the House", "A Sinister Sect: Colonia Dignidad" y "The Irishman".
- Se puede observar que, de acuerdo con las puntuaciones, "The Dark Knight" es la mejor película de las últimas siete décadas.
- Se observa una clara predominancia de los Estados Unidos en cuanto a la producción de películas y series, no obstante, es importante destacar que el director más popular en este ámbito proviene de Noruega (NO).

## Conclusiones

En este proyecto se realizó un análisis exploratorio de datos sobre el contenido de Netflix, con el objetivo de identificar patrones y tendencias en los datos. Los resultados obtenidos permiten conocer mejor la distribución de películas y Series en Netflix, así como los países, géneros, actores y calificaciones más comunes. Este análisis puede ser de utilidad para entender mejor las preferencias de los usuarios de Netflix.

