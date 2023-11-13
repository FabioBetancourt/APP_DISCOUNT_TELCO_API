# SISTEMA DE GESTIÓN ADMINISTRATIVA DE TELECOMUNICACIONES - MVP

**Desarrollado por:** Fabio Betancourt.

**Fecha de desarrollo:** octubre-noviembre, 2023.


## DESCRIPCION
A continuación, encontrará una serie de pasos para poder tener la API corriendo en el sistema para el uso completo de TELCO.

## REQUISITOS OPERATIVOS
- Java - JDK Version 11.
- Spring Boot - Version 2.7.6.
- Gradle - Version 8.3
- Editor de codigo intellij idea

### DEPENDENCIAS 
*en caso de tener problema con las dependencias las puede encontrar a continuacion debera colocarlas en el archivo "build.gradle"*

```plaintext
implementation 'org.springframework.boot:spring-boot-starter-data-jdbc'
	implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
	implementation 'org.springframework.boot:spring-boot-starter-web'
	implementation 'com.oracle.database.jdbc:ojdbc8:19.3.0.0'
	compileOnly 'org.projectlombok:lombok:1.18.22'
	annotationProcessor 'org.projectlombok:lombok:1.18.22'
	runtimeOnly 'com.oracle.database.jdbc:ojdbc8'
	annotationProcessor 'org.projectlombok:lombok'
	testImplementation 'org.springframework.boot:spring-boot-starter-test'
	implementation 'org.apache.poi:poi:5.2.3'
	implementation 'org.apache.poi:poi-ooxml:5.2.3'.
```

## PASO PARA USO
1. descargue la carpeta zip de este repositorio
2. abre la carpeta con el editor de codigo
3. corra la aplicacion
4. *Preferiblemente use DBeaver para correr la base de datos ya que fue el gestor usado durante el proceso*
   

