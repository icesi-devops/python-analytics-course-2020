# Curso de actualización en Python 2020B
# Enfasis en manejo de IDE y guiado por una aplicación de analítica de datos

## Objetivos

* Diseñar e implementar aplicaciones para la analítica de datos empleando arquitecturas orientadas a servicios
* Emplear un Ambiente integrado de desarrollo (IDE) para las etapas de vida de un proyecto de analítica de datos

## Metología

* Clases 20% teoricas , 80% practicas.
* Actividades previas a la clase, durante la clase y posterior a clase
* Videos, Documentación y código fuente disponible en GitHub
* Canal de Slack y Discord para solución de dudas

## Contenido

* Descripción general del curso
  * Objetivos
  * Metodología
  * Caso de Uso

* Herramientas de versionamiento de código 
  * Introducción
  * Conceptos básicos: rama, commit, pull request, merge request
  * Herramientas: Proveedores en Internet, Editores, Plugins
  * Flujo de trabajo con Git: Github Flow, Gitlab Flow, BitBucket Flow

* Metodologías Ágiles
  * Introducción
  * Como escribir un proyecto, funcionalidades, historias de usuario, tareas
  * Importancia de las métricas y como usarlas: velocidad, capacidad
  * Integración con herramientas de versionamiento

* Configuración de ambientes virtuales en Python
  * Manejo de version de Python con pyenv
  * Gestión de ambientes virtuales con mkvirtualenvwrapper
  * Gestión de librerias a nivel de ambiente

* PyCharm IDE Basics 
  * Creación de un proyecto
  * Creación de una plantilla de proyecto
  * Configuración de ambientes virtuales
  * Presentación de ejemplo básico de analítica
  * Creación de una biblioteca de Python y publicación en servidor
  * Gestión de Logs y niveles
  * Analisis de código estatico con Flake8,
  * Covertura con pycoverage
  * Pruebas unitarias with pytest and tox
  * Diseño guiado por las pruebas (TDD)
  * Diseño guiado por el comportamiento (BDD)
  * Pruebas de integración 
  * Pruebas de humo
  * Pruebas de carga

* Diseño guiado por el dominio (DDD)
  * Introducción
  * Táctica y Estrategia
  * Dominios acotados, lenguaje ubícuo
  * Arquitectura hexagonal 
  * Comunicación entre dominios

* SOA
  * Introduccion a las arquitecturas orientadas a servicios (SOA)
  * Implementacion SOA
  * Implementacion REST
  * Implementacion GRAPHQL
  * Implementación GRPC

* REST
  * Introducción a OpenAPI
  * Diseño de API y buenas prácticas
  * Creación de la especificación de un API usando OpenAPI 3.0
  * Conexión de una especificación en OpenAPI 3.0 con código en Python 3
    * Párametros en la URL
    * Párametros en la consulta
    * Carga útil
  * API authentication/authorization using JWT Tokens (Auth0)
  * Empaquetando la aplicación en un contenedor de Docker
  * Configuración de un servidor de aplicación: UWSGI, AIO, Unicorn
  * Pruebas locales de la API empleando la aplicación Postman

* REST en AWS
  * Descripción de recursos de AWS y buenas prácticas
    * Etiquetado
    * Políticas
    * Infrastructura como servicio
  * Creación y recomendaciones para el ajuste inicial de una cuenta de AWS
  * Empaquetando el código para despliegue como función lambda en AWS
    * Creación de la especificación por medio de AWS API Gateway
    * Filtrado de parámetros en la URL, consulta y carga útil
    * Autenticación y autorización empleando JWT tokens y AWS Cognito
  * Empaquetando el código para despliegue como contenedor de docker en AWS
    * Consideraciones para el despliegue: AWS EKS, AWS ECS, AWS Fargate
  * Pruebas de la API usando la aplicación Postman

* **Polyglot Persistence layer && Not-Only SQL (NoSQL)**:
  * **Relational Databases**:
    * Relational Database modeling, principles and best practices.
  * **Time Series Databases**: [InfluxDB](https://www.influxdata.com/).
  * **Document Databases**: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_americas_colombia_search_brand_atlas_desktop&utm_term=mongodb%20atlas&utm_medium=cpc_paid_search&utm_ad=e&gclid=CjwKCAjw4KD0BRBUEiwA7MFNTaXgR5gxbpm9vmvLtPLnBkdaqBr9fWxMFSpO9orpBlAC0zC0R5RAGBoCnVEQAvD_BwE).
  * **Key-value store**: [AWS Dynamodb](https://aws.amazon.com/es/dynamodb/).
  * **BONUS - Graph Databases**: [Neo4j](https://neo4j.com/) && [OrientDB](https://orientdb.com/).
  * Persistent python objects in SQL and NoSQL databases
  * Unittests for database call with docker

* Visualización
  * Configurando un ambiente con InfluxDB y Grafana
  * Creacíon de tableros de información
  * Generación de estadísticas en tiempo real
  * Consideraciones para un despliegue a producción

* Integración continua y despliegue continuo (CI/CD)
  * Definición de flujos de desarrollo
    * Bateria de pruebas
    * Entrega continua
    * Despliegue continuo
    * Reversión de cambios
    * Correciones
    * Escaneo de vulnerabilidades
    * Validación de RFCs para despliegue
  * Empleo de herramientas de integración continua: Travis, Github Actions, Drone, CircleCI 
  * Uso de Python para la ejecución de tareas de automatización
  * Empleo de herramientas para implementación de ChatOPS
  * Diseño e implementación de un sistema de alertas: PagerDuty, NewRelic

* Monitoreo
  * Pila de monitoreo ElasticSearch-Fluentd-Kibana
    * Introducción y despliegue de Elasticsearch
    * Introducción y despliegue de Kibana
    * Introducción a los recolectores de logs y despliegue de fluentd

* Monitoreo en AWS
  * Pila de monitoreo ElasticSearch-Fluentd-Kibana
  * AWS CloudWatch

* Optimización
  * Mejora del desempeño de apliciones en Python empleando herramientas de perfilado

## Referencias
* https://www.jetbrains.com/help/pycharm/quick-start-guide.html

## En Proceso
Definición de subtemas en el temario
Mapeo de caso de uso y temario
Definición de tiempo por cada sesión
