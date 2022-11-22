
# Header 1

Aplicación desarrollada por Carla Velasco y Eva Berbel como prueba final del Curso DevOps.

SOBRE LA APLICACIÓN



### GIT Y GITHUB Repositorios

>  **Locales**:
> 	Local 1: en SO Windows 11
> 	Local 2: en SO Linux Mint 20.04
> **Remotos**:
>		Producción: [PROD-projecte-DevOps](https://github.com/carla-velasco7e4/PROD-projecte-DevOps)  (_Forqueado a desarrollo_)
>		Desarrollo: [DEV-projecte-DevOps](https://github.com/Berbelev/DEV-projecte-DevOps) (_Creadas Ramas TODO_)
	**GitHub CLI** o **gh** como comand-line interfaz de GitHub usado desde terminal.

(Reposiorio Origen procedente de [PROD-projecte-DevOps](https://github.com/carla-velasco7e4/PROD-projecte-DevOps) )

### JENKINS (CI/CD) 

Utilizado como servidor de atomoción, con el que se ha generado el pipeline **github-s3-elastic** ( [[pagina-entera.png]] ).
En este workflows están configuarados y automátizados GitHub, S3 y Elastic Beanstalk a través del ejecutable .jar .

![[packaging-config.png]]

#### AWS S3
Un bucket primerbucketmeu en S3 de Amazon Web Service conectado a  AEB.

![[config-bucket.png]]`

#### AWS EB
Host utilizado para deploy con webhooks conectados a GitHub de Producción.

![[environment-elastic.png]]`



FRAMEWORK SPRINGBOOT



MAVEN como gestor de dependencias.


H2 SQL

INTELJIDEA como IDE.

JAVA



OBSIDIAN y MARKDOWN para generar la documentación.

NOTION para la puesta en común en el proceso de planificación.