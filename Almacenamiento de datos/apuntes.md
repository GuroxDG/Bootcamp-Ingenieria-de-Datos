# Temas

* Entendimiento el almacenamiento de datos
* Tipos de bases de datos
* Tendencias modernas y consideraciones

# La importancia del almacenamiento de datos

No consiste solo en guardar datos; es la base de como accedemos, analizamos y aprovechamos los datos en todas las formas. Conocer las opciones de almacenamiento nos ayuda a diseñar soluciones eficientes, escalables y seguras.

# Objetivos

1. Tipos de almacenamiento de datos
2. Sistemas de bases de datos
3. Tendencias modernas

# Entendimiento el almacenamiento de datos

* Fundamentos del alamacenamiento
* Tipos de almacenamiento
* Caso de uso

## Definición y necesidad de almacenamiento

El almacenamiento de datos es el conjunto de métodos y técnologías utilizados para capturar y conservar información digital. Dicta como organizamos, accedemos y manipulamos los datos.

Ha evolucionado a sistemas modernos com bases de datos relacionales y almacenamiento en la nube.

## Tipos de alamacenamiento 

Datos estructurados vs no estructurados

__En general__, los datos estructurados son organizados y fáciles de recolectar y buscar (datos tabulares), mientras que los datos no estructurados son más libres y menos fáciles de buscar.
                                                                                                          
### Sistemas transaccionales (OLTP) vs sistemas analíticos (OLAP)

OLTP, optimizados para gestionar transacciones diarías y se caracterizan por un gran número de transacciones cortas en línea.

OLAP, diseñado para el análisis y el apoyo de la toma de decisiones y se caracterizan por consultas menos frecuentes y complejas sobre grandes conjuntos de datos.


# Tipos de bases de datos

* Bases de datos relacionales
* Bases de datos NoSQL

## Bases de datos relacionales

Almacenan los datos en tablas, conectadas entre sí mediante relaciones.

Utilizan un esquema para definir la estructura de los datos y garantizar su coherencia e integridad

### SQL y operaciones CRUD

Se utiliza para interectuar con bases de datos relacionales, permite operaciones como:
* CREATE
* READ
* UPDATE
* DELETE

Son ideales para situaciones que requieren consultas complejas e integridad de los datos. (MySQL, PostgreSQL, SQLite3)

## Bases de datos no relacionales

Están diseñadas para modelos de datos específicos y no requieren un esquema fijo. Ofrecen flexibilidad y escalabilidad, especialmente útiles para aplicaciones web a gran escala.

* NoSQL = Not Only SQL

### Basadas en documentos (por ejemplo MongoDB)

ALamcenan los datis en documentos tipos JSON sin esquema, Ideales para aplicaciones que necesitan iteraciones rápidas. (__Document-base stores__)

### Almacenes clave-valor (por ejemplo Redis)

Tiene alto rendimiento y almacenan datos como pares clave-valor. Ideales para almacenar en caché información de sesión. (__key-Value Stores__)

### Column-Family Stores (por ejemplo, Cassandra)

Optimizados para consultas sobre grandes conjuntos de datos y adecuados para datos de series temporales.


### Bases de datos de grados (por ejemplo, Neo4j)

Se centran en la relación entre puntos de datos. Perfectas para redes sociales, detección de fraudes y generadores de recomendaciones.


# Caso de estudio

Aplicación móvil para maestros y padres se pueden comunicar
* ¿Tipo de base de datos para la Aplicación?
* ¿Tipo de base de datos para el análisis de los datos?


# Tendencias modernas y consideraciones

* Data Lakes vs Data Warehouses
* Almacenamiento en la nube
* Seguridad y cumplimiento de normas


## Data Lake vs Data Warehouse

__Data Lake__ es un depósito de almacenamiento que contiene una gran cantidad de datos sin procesar en su formato nativo.

__Data Warehouses__ es un sistema utilizado para la elaboración de informes y el análisis de datos en el que los datos están estructurados y filtrados.


### Casos de uso 

Los Data Lake son ideales para escenarios de Big Data y aprendizaje automático, ya que permiten almacenar diversos tipos de datos.

Los Data Warehouses son mejores para la inteligencia empresarial (business intelligence) y el análisis de datos estructurados




