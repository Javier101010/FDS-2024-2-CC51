# CREACION DE CONOCIMIENTO APLICANDO LA METODOLOGÍA CRISP-DM 
## Trabajo final de Ciencia de Datos

### Grupo: 1

### Integrantes
- Marcelo Paolo Murguía Lozano       (u202013543)                                            
- Renee Enriquez Montalvan           (U202221447)                                                 
- Wendy Carol Hernández Pérez        (U202422529)

## 1. Objetivo
El objetivo del presente informe es proporcionar información sobre las interacciones en youtube, esto se puede reflejar en los datos de los likes, dislikes, vistas, tendencias y otros datos que se encuentran en el dataset. 

## 2. Descripción del Dataset
El dataset contiene distintas variables, entre ellas hay numericas y categoricas

| **Variable**              | **Tipo**        | **Descripción**                                                                 |
|---------------------------|-----------------|---------------------------------------------------------------------------------|
| `video_id`               | Categórico      | Identificador único del video en YouTube.                                      |
| `trending_date`          | Categórico      | Fecha en la que el video fue tendencia (formato AAAA-DD-MM).                   |
| `title`                  | Categórico      | Título del video.                                                              |
| `channel_title`          | Categórico      | Nombre del canal que publicó el video.                                         |
| `category_id`            | Numérico        | ID numérico que representa la categoría del video.                             |
| `publish_time`           | Categórico      | Fecha y hora exacta de publicación del video.                                  |
| `tags`                   | Categórico      | Lista de etiquetas asociadas al video.                                         |
| `views`                  | Numérico        | Número total de vistas que ha tenido el video.                                 |
| `likes`                  | Numérico        | Número total de "me gusta" que ha recibido el video.                           |
| `dislikes`               | Numérico        | Número total de "no me gusta" que ha recibido el video.                        |
| `comment_count`          | Numérico        | Número total de comentarios realizados en el video.                            |
| `thumbnail_link`         | Categórico      | Enlace al thumbnail (miniatura) del video.                                     |
| `comments_disabled`      | Categórico      | Indica si los comentarios están deshabilitados.                                |
| `ratings_disabled`       | Categórico      | Indica si las calificaciones están deshabilitadas.                             |
| `video_error_or_removed` | Categórico      | Indica si el video fue eliminado o tiene un error.                             |
| `description`            | Categórico      | Descripción proporcionada por el creador del video.                            |
| `state`                  | Categórico      | Estado región asociado al video.                                               |
| `lat`                    | Numérico        | Latitud geográfica asociada al video.                                          |
| `lon`                    | Numérico        | Longitud geográfica asociada al video.                                         |
| `geometry`               | Categórico      | Representación geométrica combinada (latitud y longitud).                      |


## 3. Conclusiones
De acuerdo con el análisis realizado en este informe, podemos concluir que usando Regresion Multiple podemos predecir que videos estaran en los mas relevantes ya sean en likes, comentarios y vistas. Siendo esta una herramienta adecuada para poder crear un modelo predictivo


## 4. Licencias
Se ha acordado usar para este proyecto analítico la licencia Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)
