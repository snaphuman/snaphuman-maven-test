# Prueba de proyecto en Maven

## Pasos para iniciar un proyecto

* Generar el arquetipo del proyecto

> mvn archetype:generate -DgroupId=edu.uniandes.ecos.ASE.app -DartifactId=mi-primera-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

* Generar y compilar el paquete

> mvn package

* Ejecutar el programa

> java -cp target/mi-primera-app-1.0-SNAPSHOT.jar edu.uniandes.ecos.ASE.app.App 
