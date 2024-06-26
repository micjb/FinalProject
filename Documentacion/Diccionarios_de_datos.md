# Diccionarios de datos

## Diccionarios de datos originales

### Tabla green/yellow 2019-2020 original

| Nombre de la columna    | Descripción                                            | Tipo de dato | Tipo de variable |
|-------------------------|--------------------------------------------------------|--------------|------------------|
| Vendor ID               | Identificador de proveedor                             | int          | Cualitativa      |
| tpep_pickup_datetime    | Fecha inicio del viaje                                 | datetime     | Cuantitativa     |
| tpep_dropoff_datetime   | Fecha fin del viaje                                    | datetime     | Cuantitativa     |
| Passenger_count         | Número de pasajeros                                    | float        | Cuantitativa     |
| Trip_distance           | Distancia del viaje                                    | float        | Cuantitativa     |
| PULocationID            | Identificador de la ubicación de inicio                | int          | Cualitativa      |
| DOLocationID            | Identificador de la ubicación final                    | int          | Cualitativa      |
| RateCodeID              | Identificador de tarifa final vigente al finalizar el viaje | float   | Cualitativa      |
| Store_and_fwd_flag      | Marca de almacenamiento y reenvío                      | object       | Cualitativa      |
| Payment_type            | Forma de pago                                          | float        | Cualitativa      |
| Fare_amount             | Tarifa de tiempo y distancia calculada                 | float        | Cuantitativa     |
| Extra                   | Recargos por hora pico y por noche                     | float        | Cuantitativa     |
| MTA_tax                 | Impuesto MTA que se cobra según la tarifa              | float        | Cuantitativa     |
| Improvement_surcharge   | Recargo por mejora                                     | float        | Cuantitativa     |
| Tip_amount              | Propinas                                               | float        | Cuantitativa     |
| Tolls_amount            | Importe total de todos los peajes                      | float        | Cuantitativa     |
| Total_amount            | Importe total cobrado a los pasajeros                  | float        | Cuantitativa     |
| airport_fee             | Importe por recoger en aeropuerto                      | float        | Cualitativa      |
| Congestion_Surcharge    | Monto total cobrado por congestión en NY               | float        | Cuantitativa     |
| Trip_type               | Identifica si el viaje fue en calle o asignado         | float        | Cualitativa      |


### Tabla green/yellow 2022 - 2023 Original
| Nombre de la columna    | Descripción                                            | Tipo de dato | Tipo de variable |
|-------------------------|--------------------------------------------------------|--------------|------------------|
| Vendor ID               | Identificador de proveedor                             | int          | Cualitativa      |
| tpep_pickup_datetime    | Fecha inicio del viaje                                 | datetime     | Cuantitativa     |
| tpep_dropoff_datetime   | Fecha fin del viaje                                    | datetime     | Cuantitativa     |
| Passenger_count         | Número de pasajeros                                    | float        | Cuantitativa     |
| Trip_distance           | Distancia del viaje                                    | float        | Cuantitativa     |
| PULocationID            | Identificador de la ubicación de inicio                | int          | Cualitativa      |
| DOLocationID            | Identificador de la ubicación final                    | int          | Cualitativa      |
| RateCodeID              | Identificador de tarifa final vigente al finalizar el viaje | float   | Cualitativa      |
| Store_and_fwd_flag      | Marca de almacenamiento y reenvío                      | object       | Cualitativa      |
| Payment_type            | Forma de pago                                          | float        | Cualitativa      |
| Fare_amount             | Tarifa de tiempo y distancia calculada                 | float        | Cuantitativa     |
| Extra                   | Recargos por hora pico y por noche                    | float        | Cuantitativa     |
| MTA_tax                 | Impuesto MTA que se cobra según la tarifa              | float        | Cuantitativa     |
| Improvement_surcharge   | Recargo por mejora                                     | float        | Cuantitativa     |
| Tip_amount              | Propinas                                               | float        | Cuantitativa     |
| Tolls_amount            | Importe total de todos los pasajes                      | float        | Cuantitativa     |
| Total_amount            | Importe total cobrado a los pasajeros                  | float        | Cuantitativa     |
| airport_fee             | Importe por recoger en aeropuerto                      | float        | Cualitativa      |
| Congestion_Surcharge    | Monto total cobrado por congestión en NY               | float        | Cuantitativa     |
| Trip_type               | Identifica si el viaje fue en calle o se asignó        | float        | Cualitativa      |

### Tabla HighVolume 2022 - 2023 Original

| Nombre de la columna   | Descripción                                                                                                         | Tipo de dato | Tipo de variable |
|------------------------|---------------------------------------------------------------------------------------------------------------------|--------------|------------------|
| hvfhs_license_num      | El número de licencia TLC de la base o negocio de HVFHS.                                                           | str          | cualitativa      |
| dispatching_base_num   | El número de licencia base TLC de la base que despachó el viaje.                                                  | datetime     | cualitativa      |
| originating_base_num   | Número de base de la base que recibió la solicitud de viaje original.                                              | datetime     | cualitativa      |
| request_datetime       | Fecha/hora en que el pasajero solicitó ser recogido.                                                                | datetime     | cualitativa      |
| on_scene_datetime      | Fecha/hora en que el conductor llegó al lugar de recogida.                                                          | datetime     | cualitativa      |
| pickup_datetime        | La fecha y hora de recogida del viaje.                                                                             | datetime     | cualitativa      |
| dropoff_datetime       | La fecha y hora de regreso del viaje.                                                                              | datetime     | cualitativa      |
| PULocationID           | TLC Zona de Taxis en la que inició el viaje.                                                                       | int          | cualitativa      |
| DOLocationID           | Zona de Taxi TLC en la que finalizó el viaje.                                                                      | int          | cualitativa      |
| trip_miles             | Millas totales por viaje de pasajero.                                                                              | float        | cuantitativa     |
| trip_time              | Tiempo total en segundos para el viaje del pasajero.                                                                | float        | cuantitativa     |
| base_passenger_fare    | Tarifa base de pasajero antes de peajes, propinas, impuestos y tarifas.                                             | float        | cuantitativa     |
| tolls                  | Importe total de todos los peajes pagados en el viaje.                                                              | float        | cuantitativa     |
| bcf                    | Monto total recaudado en viaje para Black Car Fund.                                                                 | float        | cuantitativa     |
| sales_tax              | Monto total recaudado en el viaje por el impuesto sobre las ventas del estado de Nueva York.                        | float        | cuantitativa     |
| congestion_surcharge   | Monto total recaudado en el viaje por el recargo por congestión del estado de Nueva York.                           | float        | cuantitativa     |
| airport_fee            | $2.50 para dejar y recoger en LaGuardia, Newark y John Aeropuertos F. Kennedy.                                     | float        | cuantitativa     |
| tips                   | Cantidad total de propinas recibidas del pasajero.                                                                  | float        | cuantitativa     |
| driver_pay             | Pago total del conductor (sin incluir peajes ni propinas y neto de comisión, recargos o impuestos).                | float        | cuantitativa     |
| shared_request_flag    | ¿Aceptó el pasajero un viaje compartido o conjunto, independientemente de si eran coincidentes? (sí/no)          | str          | cualitativa      |
| shared_match_flag      | ¿El pasajero compartió el vehículo con otro pasajero que se reserva por separado en algún momento durante el viaje? (sí/no) | str          | cualitativa      |
| access_a_ride_flag     | ¿El viaje fue administrado en nombre del Metropolitano? Autoridad de Transporte (MTA)? (sí/no)                     | str          | cualitativa      |
| wav_request_flag       | ¿El pasajero solicitó un vehículo accesible para sillas de ruedas (WAV)? (sí/no)                                   | str          | cualitativa      |
| wav_match_flag         | ¿El viaje se realizó en un vehículo accesible para sillas de ruedas (WAV)? (sí/no)                                 | str          | cualitativa      |


## Diccionario de datos una vez que se realizó el proceso de ETL

### Tabla green/yellow enviroment 2019-2020

| Nombre de la Columna    | Descripción                        | Tipo de dato  | Tipo de variable | Renombrada | Nombre original       |
|-------------------------|------------------------------------|---------------|------------------|------------|-----------------------|
| VendorID                | Eliminada                          | -             | -                | NO         | Vendor ID             |
| anio                    | Año de viaje                       | int           | cuantitativa     | Si         | tpep_pickup_datetime  |
| mes                     | Mes de viaje                       | int           | cuantitativa     | Si         | tpep_pickup_datetime  |
| dia_inicio              | Día en que inicio el viaje         | int           | cuantitativa     | Si         | tpep_pickup_datetime  |
| hora_inicio             | Hora en que inicio el viaje        | Datetime      | cuantitativa     | Si         | tpep_pickup_datetime  |
| dia_fin                 | Día en que finalizó el viaje       | int           | cuantitativa     | Si         | tpep_dropoff_datetime |
| hora_fin                | Hora en que finalizó el viaje      | Datetime      | cuantitativa     | Si         | tpep_dropoff_datetime |
| pax                     | Número de pasajeros                | int           | cuantitativa     | Si         | Passenger_count       |
| distancia_viaje         | Distancia que se recorrió en el viaje | float      | cuantitativa     | Si         | Trip_distance         |
| ubicacion_inicio        | Ubicación en que se inició el viaje | int          | cualitativa      | Si         | PULocationID          |
| ubicación_fin           | Ubicación en que finalizó el viaje  | int          | cualitativa      | Si         | DOLocationID          |
| tipo_tarifa             | Eliminada                          | -             | -                | No         | RateCodeID            |
| conexión_servidor       | Eliminada                          | -             | -                | No         | Store_and_fwd_flag    |
| forma_pago              | Eliminada                          | -             | -                | No         | Payment_type          |
| viaje_bruto             | Eliminada                          | -             | -                | No         | Fare_amount           |
| extra                   | Eliminada                          | -             | -                | No         | Extra                 |
| impuesto_mta            | Eliminada                          | -             | -                | No         | MTA_tax               |
| cargo_mejora            | Eliminada                          | -             | -                | No         | Improvement_surcharge |
| propina                 | Eliminada                          | -             | -                | No         | Tip_amount            |
| peajes                  | Eliminada                          | -             | -                | No         | Tolls_amount          |
| monto_total             | Eliminada                          | -             | -                | No         | Total_amount          |
| tipo_inicio             | Eliminada                          | -             | -                | No         | Trip_type             |
| cargo_congestion        | Eliminada                          | -             | -                | No         | Congestion_Surcharge  |
| tipo_color              | Color de taxi                      | str           | cualitativa      | Agregada   | type_color            |
| total_tiempo            | Tiempo que duró el viaje           | str           | cuantitativa     | Agregada   | total_tiempo          |
| airport_fee             | Eliminada                          | -             | -                | No         | airport_fee           |

### Tabla green/yellow 2022-2023

| Nombre de la Columna   | Descripción                                           | Tipo de dato | Tipo de variable | Renombrada | Nombre original       |
|------------------------|-------------------------------------------------------|--------------|------------------|------------|-----------------------|
| viaje_id             | Asigna un id para el viaje                              | int          | Cuantitativa     | Columna nueva                  |
| Vendor ID              | Eliminada                                             | -            | -                | No         | Vendor ID             |
| anio                   | Año de viaje                                          | int          | Cuantitativa     | Si         | tpep_pickup_datetime  |
| mes                    | Mes de viaje                                          | int          | Cuantitativa     | Si         | tpep_pickup_datetime  |
| dia_inicio             | Día en que inicio el viaje                            | int          | Cuantitativa     | Si         | tpep_pickup_datetime  |
| hora_inicio            | Hora en que inicio el viaje                           | Datetime     | Cuantitativa     | Si         | tpep_pickup_datetime  |
| dia_fin                | Día en que finalizó el viaje                         | int          | Cuantitativa     | Si         | tpep_dropoff_datetime |
| hora_fin               | Hora en que finalizó el viaje                        | Datetime     | Cuantitativa     | Si         | tpep_dropoff_datetime |
| pax                    | Número de pasajeros                                  | int          | Cuantitativa     | Si         | Passenger_count       |
| distancia_viaje        | Distancia que se recorrió en el viaje                | float        | Cuantitativa     | Si         | Trip_distance         |
| ubicacion_inicio       | Ubicación en que se inició el viaje                  | int          | Cualitativa      | Si         | PULocationID          |
| ubicación_fin          | Ubicación en que finalizó el viaje                   | int          | Cualitativa      | Si         | DOLocationID          |
| tipo_tarifa            | Identificador de tarifa final vigente al finalizar el viaje | int     | Cualitativa      | Si         | RateCodeID            |
| conexión_servidor      | -                                                     | str          | Cualitativa      | No        | Store_and_fwd_flag    |
| forma_pago             | Forma de pago                                         | int          | Cualitativa      | Si         | Payment_type          |
| viaje_bruto            | Tarifa de tiempo y distancia calculada               | float        | Cuantitativa     | Si         | Fare_amount           |
| extra                  | Recargos por hora pico y por noche                   | float        | Cuantitativa     | Si         | Extra                 |
| impuesto_mta           | Impuesto MTA que se cobra según la tarifa            | float        | Cuantitativa     | Si         | MTA_tax               |
| cargo_mejora           | Recargo por mejora                                   | float        | Cuantitativa     | Si         | Improvement_surcharge |
| propina                | Propinas                                              | float        | Cuantitativa     | Si         | Tip_amount            |
| peajes                 | Importe total de todos los pasajes                   | float        | Cuantitativa     | Si         | Tolls_amount          |
| monto_total            | Importe total cobrado a los pasajeros                | float        | Cuantitativa     | Si         | Total_amount          |
| tipo_inicio            | Identifica si el viaje fue en calle o se asignó      | int          | Cuantitativa     | Si         | Trip_type             |
| cargo_congestion       | Monto total cobrado por congestión en NY             | float        | Cuantitativa     | Si         | Congestion_Surcharge  |
| cargo_aeropuerto       | Importe por recoger en aeropuerto                    | float        | Cuantitativa     | Si         | Airport_fee           |
| tipo_color             | Asigna el color del taxi                             | str          | Cualitativa      | Agregada   | type_color            |
| total_tiempo           | Tiempo que duró el viaje                             | str           | Cuantitativa     | Agregada   | total_tiempo          |


### Tabla de Uber/Lyft

| Nombre de la Columna       | Descripción                               | Tipo de dato | Tipo de variable | Renombrada | Nombre original      |
|---------------------------|-------------------------------------------|--------------|------------------|------------|----------------------|
| numero_licencia           | Eliminada                                 | -            | -                | Si         | hvfhs_license_num    |
| numero_despacho           | Eliminada                                 | -            | -                | Si         | dispatching_base_num |
| tipo_color                | uber o lyft                               | str          | cualitativa      | Si         | originating_base_num|
| anio                      | año de pedido                             | int          | cualitativa      | Si         | request_datetime     |
| mes                       | mes                                       | int          | cualitativa      | Si         | request_datetime     |
| dia                       | día                                       | int          | cualitativa      | Si         | request_datetime     |
| hora_pedido               | hora en que se pidió el viaje            | object       | cualitativa      | Si         | request_datetime     |
| hora_encuentro            | hora en que se encontró el viaje          | object       | cualitativa      | Si         | on_scene_datetime    |
| hora_inicio               | hora en que inició el viaje              | object       | cualitativa      | Si         | pickup_datetime      |
| hora_fin                  | hora en que finalizó el viaje            | object       | cualitativa      | Si         | dropoff_datetime     |
| ubicacion_inicio          | ubicación de inicio del viaje            | int          | cuantitativa     | Si         | PULocationID         |
| ubicacion_fin             | ubicación en que finalizó el viaje       | int          | cuantitativa     | Si         | DOLocationID         |
| millas_viaje              | Recorrido en millas                      | float        | cuantitativa     | Si         | trip_miles           |
| tiempo_viaje              | tiempo que duró el viaje                 | float        | cuantitativa     | Si         | trip_time            |
| viaje_bruto               | Eliminada                                 | -            | -                | Si         | base_passenger_fare  |
| peajes                    | Eliminada                                 | -            | -                | Si         | tolls                |
| impuesto_bcf              | Eliminada                                 | -            | -                | Si         | bcf                  |
| impuesto_viaje            | Eliminada                                 | -            | -                | Si         | sales_tax            |
| cargo_congestion          | cargo por congestión                     | float        | cuantitativa     | Si         | congestion_surcharge |
| cargo_aeropuerto          | Eliminada                                 | -            | -                | No         | airport_fee          |
| tips                      | Eliminada                                 | -            | -                | Si         | tips                 |
| pago_total                | pago total del viaje                      | float        | cuantitativa     | Si         | driver_pay           |
| viaje_compartido_pedido   | se pidió un viaje compartido             | object       | cualitativa      | Si         | shared_request_flag  |
| viaje_compartido_encontrado| se encontró un viaje compartido          | object       | cualitativa      | Si         | shared_match_flag    |
| access_a_ride_flag        | Eliminada                                 | -            | -                | Si         | access_a_ride_flag   |
| accesibilidad_requerida   | se accedió a un viaje                    | object       | cualitativa      | Si         | wav_request_flag     |
| accesibilidad_espontanea  | se accedió a un viaje para sillas de ruedas | object    | cualitativa      | Si         | wav_match_flag       |

### Tabla approvedModels (Tabla propia)

| Nombre de la columna | Descripción                          | Tipo de dato | Tipo de variable |
|----------------------|--------------------------------------|--------------|------------------|
| modelosId PK         | Identificador del modelo             | int          | Cualitativa      |
| modelos              | Modelo del auto                      | string       | Cualitativa      |
| 2017                 | Año Modelo                           | int          | Cuantitativa     |
| 2018                 | Año Modelo                           | int          | Cuantitativa     |
| 2019                 | Año Modelo                           | int          | Cuantitativa     |
| 2020                 | Año Modelo                           | int          | Cuantitativa     |
| 2021                 | Año Modelo                           | int          | Cuantitativa     |
| 2022                 | Año Modelo                           | float        | Cuantitativa     |
| 2023                 | Año Modelo                           | int          | Cuantitativa     |
| tipo_color PK        | Color de Taxi                        | string       | Cualitativa      |
| tipo                 | Tipo de auto (van, sedan, etc)       | string       | Cualitativa      |
| pax                  | Cantidad de pasajeros                | int          | Cuantitativa     |

### Tabla economiaAutos

| Nombre de la columna | Descripción                                 | Tipo de dato | Tipo de variable |
|----------------------|---------------------------------------------|--------------|------------------|
| modelosId UK         | Identificador del modelo                    | int          | Cualitativa      |
| modelos              | Modelo del auto                             | string       | Cualitativa      |
| Type                 | Tipo de auto (van, sedan, etc)              | string       | Cualitativa      |
| Pax                  | Cantidad de pasajeros                       | int          | Cuantitativa     |
| MPGc                 | Millas por galon en ciudad                  | float        | Cuantitativa     |
| MPGr                 | Millas por galon en ruta                    | float        | Cuantitativa     |
| tanque               | Capacidad del tanque de combustible         | float        | Cuantitativa     |
| Autonomia ciudad     | Total de millas en ciudad                   | float        | Cuantitativa     |
| Autonomia Ruta       | Total de millas en ruta                     | float        | Cuantitativa     |
| Fuel 1               | Tipo de combustible principal               | string       | Cualitativa      |
| Fuel 2               | Tipo de combustible alternativo             | string       | Cualitativa      |
| Time to charge       | Tiempo total de carga electrica             | float        | Cuantitativa     |
| tipo_conector FK     | Tipo de conector para carga electrica       | string       | Cualitativa      |
| precio base          | Precio del vehiculo 0km en su precio base   | float        | Cuantitativa     |

### Tabla cargaElectrica

| Nombre de la columna | Descripción                                     | Tipo de dato | Tipo de variable |
|----------------------|-------------------------------------------------|--------------|------------------|
| estacionID PK        | Numero de identificador de la estacoin de carga | int          | Cuantitativa     |
| nombre               | Nombre del lugar donde se encuentra el cargador | string       | Cualitativa      |
| latitud              | Latitud de referencia                           | float        | Cuantitativa     |
| longitud             | Longitud de referencia                          | float        | Cuantitativa     |
| ocupacion_maxima     | Cantidad de vehiculos que pueden cargar         | string       | Cualitativa      |
| ciudad FK            | Nombre de la ciudad (Queen, Manhattan, Etc.)    | string       | Cualitativa      |
| red                  | Nombre del proveedor del cargador               | string       | Cualitativa      |
| tipo_conector FK     | Tipo de ficha de carga electrica                | string       | Cualitativa      |
| duenio               | Establece si es privada o estatal               | string       | Cualitativa      |
| tipo_estacion        | Descripcion del establecimiento                 | string       | Cualitativa      |


### Tabla zones

| Nombre de la columna | Descripción                                  | Tipo de dato | Tipo de variable |
|----------------------|----------------------------------------------|--------------|------------------|
| ubicacion_inicio PK  | Codigo de la zona dentro de Manhattan        | int          | Cuantitativa     |
| ciudad FK            | Nombre de la ciudad (Queen, Manhattan, Etc.) | string       | Cualitativa      |
| zone                 | barrio interno de cada ciudad                | string       | Cualitativa      |
| tipo_color           | Taxis permitidos para recojer pasajeros      | string       | Cualitativa      |


### Tabla puenteEstado

| Nombre de la columna | Descripción                                  | Tipo de dato | Tipo de variable |
|----------------------|----------------------------------------------|--------------|------------------|
| ubicacion_inicio PK  | Codigo de la zona dentro de Manhattan        | int          | Cuantitativa     |

### Tabla puenteColor

| Nombre de la columna | Descripción                                  | Tipo de dato | Tipo de variable |
|----------------------|----------------------------------------------|--------------|------------------|
| tipo_color PK        | Color de Taxi                                | string       | Cualitativa      |

### Tabla puenteCiudad

| Nombre de la columna | Descripción                                  | Tipo de dato | Tipo de variable |
|----------------------|----------------------------------------------|--------------|------------------|
| ciudad PK            | Nombre de la ciudad (Queen, Manhattan, Etc.) | string       | Cualitativa      |
