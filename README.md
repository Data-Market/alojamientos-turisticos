# Datasets de Alojamientos Turísticos

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/alojamientos-turisticos-banner.png">
</a>

## Descripción

Anuncios de inmuebles de __alquiler turístico en las principales plataformas__.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: cada 7 días
* __Volumen estimado__: 
* __Histórico__: 

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#alojamientos-turisticos-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/alojamientos-turisticos/blob/main/alojamiento-turistico-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre           | tipo     | descripción                                                                                                                                            | ejemplo                                                                                                                 |
|------------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| website          | str      | Plataforma de alquiler turístico de donde se han extraído los datos (encriptado). Visible tras la suscripción al dataset.                              | 7592FA175D6EEF5711D311A6516A6A9D                                                                                        |
| province         | str      | Provincia donde se ubica el inmueble en alquiler turístico.                                                                                            | Granada                                                                                                                 |
| town             | str      | Localidad donde se encuentra el inmueble en alquiler turístico.                                                                                        | Granada                                                                                                                 |
| url              | str      | Url del inmueble en alquiler turístico (hash), disponible tras la suscripción al dataset.                                                              | 702B70346E3EDA42063F0362C98B7BB3                                                                                        |
| location         | str      | Localización aproximada del inmueble en alquiler turístico.                                                                                            | Granada, Andalucía, Spain                                                                                               |
| lat              | geo      | Para aquellos casos en los que esté disponible, la latitud de la posición del inmueble en alquiler turístico.                                          | 37.176953                                                                                                               |
| lon              | geo      | Para aquellos casos en los que esté disponible, la longitud de la posición del inmueble en alquiler turístico.                                         | -3.605664                                                                                                               |
| photo_urls       | json     | Lista con las URLs de las fotografías del inmueble en alquiler turístico (hash en muestras, visible tras la compra del dataset).                       | ['912EC803B2CE49E4A541068D495AB570', 'ADCA4977CB42016071530FB8888105C7']                                                |
| name             | str      | Nombre del anuncio del inmueble en alquiler turístico.                                                                                                 | Stunning Apartment, perfect location on Gran Via                                                                        |
| price            | json     | Árbol de precios del alquiler del inmueble en función de la fecha, en Euros.                                                                           | {'2020-12-13': 400, '2020-12-14': 350, '2020-12-15': 350}                                                               |
| min_stay         | int      | Número mínimo de noches que se pueden reservar.                                                                                                        | 30                                                                                                                      |
| guests           | int      | Número de plazas (huéspedes) permitidos en el inmueble en alquiler turístico.                                                                          | 4                                                                                                                       |
| rooms            | int      | Número de habitaciones en el inmueble en alquiler turístico.                                                                                           | 2                                                                                                                       |
| beds             | int      | Número de camas en el inmueble en alquiler turístico.                                                                                                  | 2                                                                                                                       |
| wcs              | int      | Número de baños en el inmueble en alquiler turístico.                                                                                                  | 1                                                                                                                       |
| wifi             | bool     | Indica si el inmueble tiene conexión wifi.                                                                                                             | True                                                                                                                    |
| parking          | bool     | Indica si el inmueble cuenta con plaza de aparcamiento.                                                                                                | False                                                                                                                   |
| kitchen          | bool     | Indica si el inmueble cuenta con cocina disponible para su uso por parte de los huéspedes.                                                             | True                                                                                                                    |
| heating          | bool     | Indica si el inmueble cuenta con calefacción.                                                                                                          | False                                                                                                                   |
| tv               | bool     | Indica si el inmueble cuenta con TV.                                                                                                                   | True                                                                                                                    |
| air_conditioning | bool     | Indica si el inmueble cuenta con aire acondicionado.                                                                                                   | False                                                                                                                   |
| washing_machine  | bool     | Indica si el inmueble cuenta con lavadora.                                                                                                             | False                                                                                                                   |
| clothes_dryer    | bool     | Indica si el inmueble cuenta con secadora.                                                                                                             | False                                                                                                                   |
| iron             | bool     | Indica si el inmueble cuenta con plancha disponible para los huéspedes.                                                                                | True                                                                                                                    |
| elevator         | bool     | Indica si el inmueble cuenta con ascensor.                                                                                                             | False                                                                                                                   |
| description      | str      | Descripción del inmueble en alquiler turístico escrita por el anunciante del mismo.                                                                    | Acogedor estudio con una excelente ubicación, cocina equipada, cama doble y baño remodelado, y todo lo que necesitas. |
| rules            | json     | Normas del inmueble definidas por el anfitrión. Se incluyen conceptos como la posibilidad de fumar, hacer fiestas, traer mascota, etc.                 | {'arrival': 'A partir de las 15:00', 'exit': None, 'children_friendly': None}                                           |
| host_id          | str      | ID del anfitrión en la plataforma de origen del inmueble.                                                                                              | 263394602                                                                                                               |
| host_meta        | json     | Información adicional del anfitrión, como su nombre, descripción, número de evaluaciones, ratio de respuesta, fecha de registro en la plataforma, etc. | {'name': 'Urban Vida', 'joined': 'Se registró en mayo de 2019, 'description': None}                                     |
| reviews          | int      | Número total de valoraciones del inmueble en alquiler turístico.                                                                                       | 3                                                                                                                       |
| score            | int      | Media de las valoraciones del alojamiento turístico. Dependiendo de la plataforma puede variar entre 1-5, 1-10, etc.                                   | 3.56                                                                                                                    |
| insert_date      | datetime | Fecha de extracción del anuncio.                                                                                                                       | 2020-11-19 00:00:00                                                                                                     |
