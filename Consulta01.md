# Consulta 01: Git, Gradle y Maven

# Git
[comment]: <> (Cristhian)



## Github, Gitlab y Bitbucket
[comment]: <> (Alejandro)


# Gradle
[comment]: <> (Janer)

Gradle es una herramienta de código abierto para automatizar la construcción de proyectos, se centra en la flexibilidad y el rendimiento. 

Los scripts de compilación de Gradle se escriben utilizando **Groovy**, el cual es un lenguaje de programación orientado a objetos implementado sobre la plataforma Java, o **Kotlin DSL (Domain Specific Language)** el cual es también un lenguaje de programación de tipado estático que corre sobre la máquina virtual de Java y que también puede ser compilado a código fuente de JavaScript.
![Texto alternativo opcional si no se carga la imagen](https://gradle.org/images/gradle-knowledge-graph-logo.png?20170228)
> Imagen tomada de: https://gradle.org/images/gradle-knowledge-graph-logo.png?20170228 

Gradle fue seleccionado como la herramienta **oficial** de construcción para Android y cuenta con soporte para diversas tecnologías y lenguajes.

Algunas de las características que ofrece esta herramienta:

  - Altamente personalizable
  - Rápido
  - Potente
  - Flexibilidad
  - Permite trabajar en varios lenguajes
  - Tiene lenguaje DSL que simplifica
  - Tiene gestión de tendencias bastante optimizada

Gradle tiene una gran flexibilidad y nos permite hacer usos otros lenguajes además de **Java**, también cuenta con un sistema de **gestión de dependencias** muy estable. Gradle es altamente **personalizable y rápido** ya que completa las tareas de forma rápida y precisa **reutilizando** las salidas de las ejecuciones anteriores, sólo procesa las entradas que presentan cambios en paralelo.

![Texto alternativo opcional si no se carga la imagen](https://www.arquitecturajava.com/wp-content/uploads/diagramaGradle.gif)
> Imagen tomada de: https://www.arquitecturajava.com/wp-content/uploads/diagramaGradle.gif

### Iniciar en Gradle
Comenzar con Gradle es fácil, solo debe seguir las guías para [Descargar e Instalar Gradle](https://docs.gradle.org/current/userguide/installation.html) y luego consulte las [Guías de Introducción a Gradle](https://gradle.org/guides/#getting-started) para crear su primer proyecto, extraído desde la pagina oficial de Gradle. 

### Funcionalidades de la herramienta
Gradle al ser una herramienta tan flexible y potente, tiene una gran cantidad de funciones que puedes implementar en su uso, algunas de ellas son:
  - **Depuración colaborativa:** Permite compartir los resultados de la compilación para resolver en equipo de forma eficiente posibles problemas que aparezcan.
  - **Construcción incremental:** Valida en el proceso de compilación si la entrada, salida o implementación de una tarea ha cambiado, en caso de no existir algún cambio la considera actualizada y no se ejecuta.
  - **Diseño de repositorio personalizado:** Podremos tratar prácticamente cualquier estructura de directorios del sistema de archivos como un repositorio de Artifacts.
  - **Dependencias transitivas:** Es uno de los principales beneficios que ofrece al utilizar la gestión de dependencias ya que se encarga de descargar y administrar las dependencias transitivas.
  - **Soporte a Groovy y Scala incorporado:** Compatibilidad con los proyectos de Groovy, permitiendo trabajar con código Groovy o código Scala e inclusive desarrollar código mixto Java y Groovy o Java y Scala.
  - **Integración con Android Studio:** Android Studio no cuenta con un generador interno, sino que delega todas las tareas de compilación en Gradle, garantizando la corrección en todas las construcciones, ya sea que se ejecuten desde Android Studio, la línea de comandos o un servidor de construcción de integración continua.
  - **TestKit para pruebas funcionales:** Permite la ejecución prágramática de builds inspeccionando los resultados de compilación, ésta es una prueba de compatibilidad entre versiones.
  - **Lee el formato POM:** Es compatible con el formato de metadatos POM, por lo que es posible recuperar dependencias de cualquier repositorio compatible con Maven.
  - **Caché de dependencia de terceros:** Las dependencias de repositorios remotos se descargan y almacenan en caché localmente, las compilaciones posteriores utilizan los artifacts almacenados en caché para evitar el tráfico de red innecesario.
  - **Compara builds:** Resalta de forma rápida las diferencias entre compilaciones, lo que hace que el análisis de la causa raíz sea mucho más rápido y eficaz.


### Complementos de Gradle
Gradle permite construir desde **microservicios** hasta **aplicaciones móviles**, puede ser utilizado por pequeños **startups** como por grandes empresas, ya que ayuda a los equipos a desarrollar, automatizar y entregar software de calidad en un menor tiempo, aumentando su eficiencia.




# Maven
[comment]: <> (Hernan)
