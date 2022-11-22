
# Intro

Aplicación desarrollada y deployada por Carla Velasco y Eva Berbel como prueba final del Curso DevOps.

![[books.png]]

Aplicación de una API de biblioteca para consultar los libros disponibles en un listado o ver los detalles de un libro concreto. Realizada en  [SpringBoot](https://spring.io/projects/spring-boot) con Java 17 y  [Maven](https://maven.apache.org/)  , con una base de datos  en memoria([H2 Database ](https://www.h2database.com/html/main.html)) y con IntelJidea [IntelliJ IDEA ](https://www.jetbrains.com/idea/) como IDE.



## + SOBRE LA APLICACIÓN

### GIT Y GITHUB Repositorios

>  **Locales**:
> 	Local 1: en SO Windows 11
> 	Local 2: en SO Linux Mint 20.04



> **Remotos**:
>		Producción: [PROD-projecte-DevOps](https://github.com/carla-velasco7e4/PROD-projecte-DevOps)  (_Forqueado a desarrollo_)
>		Desarrollo: [DEV-projecte-DevOps](https://github.com/Berbelev/DEV-projecte-DevOps) (_Creadas Ramas TODO_)


>
	**GitHub CLI** o **gh** como comand-line interfaz de GitHub usado desde terminal.
	
	
```
gh auth login --hostname <hostname>
```

```
gh repo clone <repository> [<directory>] [-- <gitflags>...]
```


(Reposiorio Origen  de [AlbertProfe](https://github.com/AlbertProfe/libraryH2command) )

### JENKINS (CI/CD) 

Utilizado como servidor de atomoción, con el que se ha generado el pipeline **github-s3-elastic** ( [[pagina-entera.png]] ).
En este workflows están configuarados y automátizados GitHub, S3 y Elastic Beanstalk a través del ejecutable .jar .

![[packaging-config.png]]

#### AWS S3
Un bucket primerbucketmeu en S3 de Amazon Web Service conectado a  AEB.

![[config-bucket.png]]`

#### AWS EB
Host utilizado para deploy con webhooks conectados a GitHub de Producción.

![[environment-elastic.png]]


#### INTELJIDEA como IDE.

#### FRAMEWORK SPRINGBOOT 

![[springinitializr.png]]
![[pakaging_java.png]]


MAVEN como gestor de dependencias y para la realizacíon de procesos build.


### H2  Database Engine (Java SQL database)

Aplicación de consola basada en navegador. Base de datos en memoria.

![[h2.png]]




### OTRAS 
Como complemento a la gestión de desarrollo y planificación, también se ha hecho uso de las siguientes herramientas:


 - **OBSIDIAN** y **MARKDOWN** para generar la documentación.

 - **NOTION** para la puesta en común en el proceso de planificación.