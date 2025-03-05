# Masterclass: Spark para Data Engineers en Databricks



## Objetivo
Aprender a usar PySpark en Databricks para procesar datos a gran escala con DataFrames, Delta Lake, optimización de consultas y particionamiento.

## Contenido

### 1. Introducción a PySpark en Databricks
- Qué es Databricks y cómo optimiza el uso de PySpark.
- Uso de Delta Lake para almacenamiento optimizado.
- Ingesta de datos en tiempo real con AutoLoader.
- Ejecución optimizada de Spark con Photon.

### 2. Configuración y SparkSession
- Verificación de la versión de Spark.
- Configuración del clúster y ajustes importantes.
- Cómo gestionar el número de particiones y habilitar el caching en Databricks.

### 3. Lectura y escritura de datos en Databricks
- Cómo acceder a los archivos almacenados en el Databricks File System (DBFS).
- Cargar datos desde diferentes formatos (CSV, JSON, Parquet, Delta).
- Guardar dataframes en Delta Lake y cómo leerlos.

### 4. Transformaciones con DataFrames
- Transformaciones "Lazy" y su diferencia con Pandas.
- Filtrado de datos y transformaciones básicas.
- Agrupaciones y agregaciones utilizando funciones estándar de PySpark.

### 5. Optimización de performance en Databricks
- Ventajas del uso de Parquet en lugar de CSV.
- Cacheo de DataFrames para mejorar la performance.
- Cómo verificar el número de particiones y optimizar consultas.

### 6. Uso de Delta Lake en Databricks
- Qué es Delta Lake y sus ventajas (ACID Transactions y versionado de datos).
- Cómo crear y gestionar tablas Delta.
- Uso de Time Travel para acceder a versiones anteriores de los datos.
- Ejecución de MERGE INTO (Upsert) en tablas Delta.

### 7. Carga de Datos en tiempo real con AutoLoader
- Configuración de AutoLoader para ingestión de datos en streaming.
- Cómo escribir en una tabla Delta en modo streaming.

### 8. Estrategias de manejo de datos en Databricks
- Actualización y eliminación de registros en tablas Delta.
- Técnicas avanzadas para manejo eficiente de datos en tablas Delta.

### 9. Funciones avanzadas en PySpark
- Uso de funciones de ventana para ranking y ordenación de datos.
- Creación de UDFs (User Defined Functions) para personalizar transformaciones.

## Cómo Usar este material
Este material está diseñado para ayudarte a aprender y practicar con PySpark en Databricks. Asegúrate de tener una cuenta en Databricks para seguir los ejemplos prácticos. 
Los ejercicios te permitirán familiarizarte con la lectura, escritura, transformación y optimización de datos en un entorno de datos a gran escala.

## Requisitos
- Conocimientos básicos de Python y Spark.
- Cuenta en Databricks.
