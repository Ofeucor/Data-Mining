# Grupo A2SJ: GamePredRater
## Minería de Datos

Bienvenido al repositorio del equipo de trabajo A2SJ de la asignatura de Minería de Datos de la Escuela Superior de Informatica de Ciudad Real (UCLM).

Nuestro proyecto recibe el nombre de GamePredRater, y su objetivo es predecir la valoración de los videojuegos acorde a las características que tengan.




## Jerarquía de archivos

En el siguiente esquema se puede ver la estructura de directorios de nuestro repositorio.


```python
├── README.md                                                      <- README para los usuarios de este proyecto.
├── data
|   ├── processed                                                  <- Datasets Preprocesados
│   |      ├── auxiliar1.csv                                                                     <- Dataset resultante del cuaderno Auxiliar.
│   |      ├── auxiliar3.csv                                                                     <- Dataset resultante del cuaderno Auxiliar.
|   |      └── Enlaces_tarjeta_de_datos_&_auxuliar4.md                                           <- Enlace a los Datasets resultante del cuaderno Auxiliar y la Tarjeta de Datos.
│   └── raw                                                        <- Datasets Originales
│          ├── steam.csv                                                                         <- Dataset Principal
│          ├── steam_description_data.csv                                                        <- Dataset Auxiliar con las descripciones de los juegos.
│          ├── steam_requirements_data.csv                                                       <- Dataset Auxiliar con los requisitos hardware de los juegos.
│          ├── hours_played.csv                                                                  <- Dataset Auxiliar con las horas medias de los juegos. 
|          └── steamspy_tag_data.csv                                                             <- Dataset Auxiliar con los tags de los juegos.             
│
├── notebooks
|   ├── Modelos                                                   <- Notebooks dirigidos a la generación de Modelos.
│   |      ├── Algoritmos_de_Regresión_Mineria_de_Datos.ipynb                                    <- Notebooks dirigidos a la generación de Modelos de Regresión.
|   |      └── Arbol_de_Decisión_Mineria_de_datos.ipynb                                          <- Notebooks dirigidos a la generación de Modelos de Arbol de Decisión.  
|   └── Preprocesado                                              <- Notebooks dirigidos al preprocesado y Transformación de los datos.
│          ├── Grupo_A2SJ_Cuaderno_Auxiliar_1.ipynb                                              <- Notebook dirigido al preprocesado y Transformación de los datos del         
|          |                                                                                        Dataset Auxiliar 1.
│          ├── Grupo_A2SJ_Cuaderno_Auxiliar_2.ipynb                                              <- Notebook dirigido al preprocesado y Transformación de los datos del         
|          |                                                                                        Dataset Auxiliar 2.
│          ├── Grupo_A2SJ_Cuaderno_Auxiliar_3.ipynb                                              <- Notebook dirigido al preprocesado y Transformación de los datos del         
|          |                                                                                        Dataset Auxiliar 3.
│          ├── Preproceso_y_Transformación_de_los_datos_Minería_de_Datos.ipynb                   <- Notebook dirigido al preprocesado y Transformación de los datos del         
|          |                                                                                        Dataset principipal y adicción de los dataset auxiliar.
|          └── Selección_de_características_y_últimos_detalles_sobre_la                          <- Notebook dirigido a la Selección de Caracteristicas. 
|              _tarjeta_de_datos_Minería_de_datos.ipynb
└── reports                                                
    ├── figures                                                   <- Imagenes usadas durante el Informe
    └── Entrega Final - Mineria de Datos.pdf                      <- Informe
                                                       

```

Además, puedes encontrar más información suplementaria en nuestra [wiki](https://github.com/Ofeucor/Data-Mining/wiki).

## Componentes del grupo
Agustín Mora Acosta

Andrés González Díaz

Sergio Sevilla Ballesteros

José Ángel Villamor Carrillo
