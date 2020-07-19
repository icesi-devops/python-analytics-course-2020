# Curso de actualización en Python 2020B

## Énfasis

* Manejo de Entornos Integrados de Desarollo (IDE)
* Guiado por la construcción de una aplicación de analítica de datos

## Objetivos

* Diseñar e implementar aplicaciones para la analítica de datos empleando arquitecturas orientadas a servicios
* Emplear un IDE para las etapas de vida de un proyecto de analítica de datos

## Metología

* Curso virtual
* Clases 20% teoricas, 80% practicas. 
* Actividades previas a la clase, durante la clase y posterior a clase
* Videos, Documentación y código fuente disponible en GitHub
* Canal de Slack y Discord para solución de dudas

## Contenido

### Unidad 1

### Objetivos
* Conocer los temas a tratar y la metodologia del curso
### Duración
1 hora
### Temas
* Descripción general del curso
  * Objetivos
  * Contenido
  * Metodología
  * Caso de Uso

### Unidad 2

### Objetivos
* Manejar una herramienta de versionamiento de codigo
* Entender la importancia del versionamineto de codigo
### Duración
6 horas
### Temas
* Herramientas de versionamiento de código
  * Introducción a Git 
  * Instalación de Git (Enlace a manuales/videos para instalación sugerida)
  * Herramientas
    * Proveedores en Internet
      * Gitlab
      * Github
      * Bitbucket
      * AWS CodeCommit
  * Editores
    * VSCode
      * Plugins
    * Pycharm
      * Plugins
  * Conceptos básicos ( A través de ejemplos ) (2 horas)
    * Fork
    * Clone
    * Reference: Branch, Tag, Commit
    * Pull request, Merge request
    * Merge
    * Rebase
    * Stash
      * Push
      * Pop
    * Reset
    * connection via SSH con keys
  * Flujo de trabajo con Git
    * Github Flow
    * Gitlab Flow
    * BitBucket Flow

# Realizar la planeación de un proyecto
# Emplear github como una herramienta que apoye el seguimiento de un proyecto
* Metodologías ágiles (3 horas)
  * Introducción
  * Planeación y seguimiento
    * Proyecto
    * Funcionalidades
    * Historias de usuario
    * Subtareas
  * Métricas
    * Velocidad
    * Capacidad
  * Integración con Git
    * Rally
    * Jira

# Entender la importancia de manejar ambientes virtuales
# Realizar aplicaciones que se ejecuten sobre ambientes virtuales
* Configuración de ambientes virtuales en Python (3 horas)
  * Gestión de versiones de Python con pyenv
  * Gestión de ambientes virtuales con mkvirtualenvwrapper
  * Gestión de librerias por ambiente de desarrollo

# Emplear un editor para la creación de un proyecto
# Hacer uso de las funcionalidades de un editor para optimizar el tiempo de programación
* PyCharm IDE Basics (6 horas)
  * Creación de un proyecto
  * Creación de una plantilla de proyecto
  * Configuración de ambientes virtuales
  * Presentación de ejemplo básico de analítica
  * Creación de una biblioteca de Python y publicación en servidor
  * Gestión de Logs y niveles
  * Analisis de código estatico con flake8,
  * Covertura con pycoverage

# Identificar los tipos de pruebas
# Realizar pruebas sobre una aplicación
* Bateria de pruebas (6 horas)
  * Diseño guiado por las pruebas (TDD)
  * Diseño guiado por el comportamiento (BDD)
  * Pruebas unitarias with pytest and tox
  * Pruebas de integración 
  * Pruebas de humo
  * Pruebas de carga

# Entender el concepto de arquitectura orientada a servicio
* SOA (3 horas)
  * Introduccion a las arquitecturas orientadas a servicios (SOA)
  * Implementacion SOA
  * Implementacion REST
  * Implementacion GRAPHQL
  * Implementación GRPC

# Implementar un API Rest para proveer un servicio
* REST (9 horas)
  * Introducción a OpenAPI
  * Diseño de API y buenas prácticas
  * Creación de la especificación de un API usando OpenAPI 3.0
  * Conexión de una especificación en OpenAPI 3.0 con código en Python 3
    * Párametros en el path
    * Párametros en el query
    * Información en la carga útil
  * Autenticación y autorización de API empleando JWT Tokens (Auth0)
  * Empaquetando la aplicación en un contenedor de Docker
  * Configuración de un servidor de aplicación: UWSGI, AIO, Unicorn
  * Pruebas locales de la API empleando la aplicación Postman

# Emplear mecanismos de integración continua para el despliegue de servicios
* Integración continua y despliegue continuo (CI/CD) (9 horas)
  * Definición de flujos de desarrollo
    * Bateria de pruebas
    * Entrega continua
    * Despliegue continuo
    * Reversión de cambios
    * Correciones
    * Escaneo de vulnerabilidades
    * Validación de RFCs para despliegue
  * Herramientas de CI/CD
    * Travis
    * Github Actions
    * DroneIO
    * CircleCI 
    * AWS CodePipeline
  * Uso de Python para la ejecución de tareas de automatización
  * Despliegue de API REST en Cloud
    * AWS
      * AWS Roles
      * AWS API Gateway
      * AWS Lambda
      * AWS S3
      * AWS CDK (Automating deployment)
    * Azure
    * Google Cloud 

## Referencias
* https://www.jetbrains.com/help/pycharm/quick-start-guide.html
