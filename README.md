# Repositorio Pyspark-Jupyter-Poetry

Este repositorio proporciona una configuración para desplegar un entorno de Apache Spark utilizando Docker Compose. Facilita la creación de un clúster de Spark con un maestro y varios trabajadores listos para ejecutar aplicaciones distribuidas.

## Composición del repositorio

- **Docker Compose:** Contiene un archivo `docker-compose.yml` que define los servicios necesarios para el clúster Spark, incluyendo un maestro y varios trabajadores.

- **Configuración de Spark:** Utiliza la imagen oficial de Bitnami Spark para la implementación del clúster. Se configuran los parámetros como el número de núcleos y la memoria para cada trabajador.

- **Requisitos del entorno:** Se especifican las dependencias del proyecto en el archivo `pyproject.toml` usando Poetry, incluyendo Python, Pandas, PySpark, entre otros.

## Configuración del clúster Spark

El clúster Spark está configurado con un maestro y tres trabajadores, cada uno con la capacidad de ejecutar tareas distribuidas. El archivo `docker-compose.yml` define la configuración de red y los puertos expuestos para acceder al tablero de control del clúster y a los servicios de Spark.

## Contacto

Este repositorio es mantenido por Kuautli. Si tienes alguna pregunta, sugerencia o problema, no dudes en ponerte en contacto con él a través de [cuauhtemocbe@gmail.com](mailto:cuauhtemocbe@gmail.com).
