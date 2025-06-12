# M3 - Fundamentos de Maven - Grupo 6

## 📌 Descripción del proyecto

Proyecto práctico sobre los fundamentos de Apache Maven para la gestión de dependencias.

---

## 💻 Comandos usados con Maven

### Comando de inicialización:

```bash
mvn archetype:generate \
  "-DgroupId=com.equipo.taskmaster" \
  "-DartifactId=taskmaster" \
  "-DarchetypeArtifactId=maven-archetype-quickstart" \
  "-DinteractiveMode=false"

- Dependencias.

org.junit:junit-bom:5.11.0

org.junit.jupiter:junit-jupiter-api

org.junit.jupiter:junit-jupiter-params

org.apache.commons:commons-lang3:3.12.0

- Plugins.

org.apache.maven.plugins:maven-clean-plugin:3.4.0

org.apache.maven.plugins:maven-resources-plugin:3.3.1

org.apache.maven.plugins:maven-compiler-plugin:3.13.0

org.apache.maven.plugins:maven-surefire-plugin:3.3.0

org.apache.maven.plugins:maven-jar-plugin:3.4.2

org.apache.maven.plugins:maven-install-plugin:3.1.2

org.apache.maven.plugins:maven-deploy-plugin:3.1.2

org.apache.maven.plugins:maven-site-plugin:3.12.1

org.apache.maven.plugins:maven-project-info-reports-plugin:3.6.1

org.apache.maven.plugins:maven-compiler-plugin:3.8.1

org.codehaus.mojo:exec-maven-plugin:3.1.0

- Mayor aprendizaje técnico al usar Maven:

Aprendí cómo organizar un proyecto Java correctamente y manejar las dependencias con Maven. También descubrí cómo usar plugins para compilar y probar el código, automatizando todo el proceso. Además, aprendí a configurar diferentes entornos con perfiles y a integrar pruebas con JUnit para asegurar que todo funcione bien.

- Desafío enfrentado al usar Maven

El mayor desafio enfrentado al usar Maven fueron los comandos deprecados y tener que realizar una investigación de la forma de importar Junit5, ya que los comandos incluidos en el ejercicio pertencian a Junit4, ademas de entender como pasar la variable de entorno desde pom.xml a App.java

