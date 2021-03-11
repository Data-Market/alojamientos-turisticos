# Datasets de Alojamientos Turísticos

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/alojamientos-turisticos-banner.png">
</a>

## Descripción

Anuncios de inmuebles de __alquiler turístico en las principales plataformas__.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: cada mes
* __Volumen estimado__: variable debido a la Covid-19
* __Histórico__: desde enero 2017

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#alojamientos-turisticos-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/alojamientos-turisticos/blob/main/alojamiento-turistico-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| accommodates | int | Capacidad del apartamento (en personas). | 4 |
| amenities_list | str | Lista de comodidades que presenta el alojamiento turístico. | {TV,Wifi,"Air conditioning",Kitchen,"Free parking on premises",Elevator,"Free street parking",Hea... |
| apartment_id | int | Identificación del alojamiento turístico. | 17691214 |
| availability_30 | int | Número de días disponibles del alojamiento turístico en un plazo de 30 días (desde la fecha de extracción). | 29 | 
| availability_365 | int | Número de días disponibles del alojamiento turístico en un plazo de 365 días (desde la fecha de extracción). | 30 |
| availability_60 | int | Número de días disponibles del alojamiento turístico en un plazo de 60 días (desde la fecha de extracción). | 30 |
| availability_90 | int | Número de días disponibles del alojamiento turístico en un plazo de 90 días (desde la fecha de extracción). | 30 |
| bathrooms | int | Número de cuartos de baño disponibles en el alojamiento turístico. | 2 | 
| bedrooms | int | Número de habitaciones disponibles en el alojamiento turístico. | 2 | 
| beds | int | Cantidad de camas disponibles en el alojamiento turístico. | 3 | 
| city | str |  Ciudad en la que se encuentra el alojamiento turístico. | sevilla |
| country | str | País en el que se encuentra el alojamiento turístico. | Spain |
| description | str | Descripción detallada del alojamiento turístico. | Viviendas Villalobos is located in Seville, 2.1 km from Plaza de España. This property is 3 km fr... |
| first_review_date | datetime | Fecha del primer comentario del alojamiento turístico. | 2017-05-01 |
| has_availability | bool | Disponibilidad o no reserva del alojamiento turístico. | True | 
| host_id | int | Número de identificación de la persona que pone a disposición un apartamento turístico. | 90583625 |
| insert_date | datetime | Fecha de extracción de la información. | 2018-07-31 |
| is_instant_bookable | bool | Si puede reservarse sin necesidad de revisión por parte del propietario. | True |
| last_review_date | datetime | Fecha del último comentario del alojamiento turístico. | 2018-04-30 | 
| latitude | geo | Latitud en la que se encuentra el alojamiento turístico. | 37.374494145490765 | 
| license | str | Tipo de licencia que posee el alojamiento turístico. | VTC-SE-02002 |
| longitude | geo | Longitud en la que se encuentra el alojamiento turístico. | -5.962028304816549 | 
| maximum_nights | int | Número de noches máximas permitidas en el alojamiento turístico. | 1125 | 
| minimum_nights | int | Número de noches mínimas a alquilar del alojamiento turístico. | 1 | 
| name | str | Nombre del alojamiento turístico. | Apartment at 20 min. from the center of Seville | 
| neighborhood_district | str | Nombre del distrito donde se encuentra un alojamiento turístico. | Cerro - Amate |
| neighborhood_name | str | Nombre del barrio donde se encuentra el alojamiento turístico. | El Cerro |
| neighborhood_overview | str | Información sobre la zona donde se encuentra el alojamiento turístico. | Cerro del Águila is a neighborhood founded in the 20s of the last century in the province of Sevi... |
| number_of_reviews | int | Número de comentarios que tiene el alojamiento turístico. | 4 |
| price | float | Precio del alojamiento turístico en euros. | 63 | 
| review_scores_accuracy | int | Puntuación de 0 a 10 sobre la precisión de los detalles del alojamiento turístico. | 10 | 
| review_scores_checkin | int | Puntuación de 0 a 10 sobre el momento de entrada al alojamiento turístico. | 10 |
| review_scores_cleanliness | int | Puntuación de 0 a 10 sobre las condiciones higiénicas del alojamiento turístico. | 9 |
| review_scores_communication | int | Puntuación de 0 a 10 sobre la comunicación del propietario con los usuarios del alojamiento turístico. | 10 |
| review_scores_location | int | Puntuación de 0 a 10 sobre la zona donde se encuentra el alojamiento turístico. | 8 |
| review_scores_rating | int | Puntuación de 0 a 100 dada por los usuarios del alojamiento turístico. | 85 | 
| review_scores_value | int | Puntuación de 0 a 10 sobre la evaluación del alojamiento turístico. | 9 | 
| reviews_per_month | float | Número de comentarios que recibe el alojamiento turístico al mes. | 0.26 | 
| room_type | str | Tipo de alojamiento turístico. | Entire home/apt | 
| url | str | Url del alojamiento turístico en alquiler. | F4E9FF4A1D1E29BB3E620E8B0B175CFA | 
