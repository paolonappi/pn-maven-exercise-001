# pn-maven-exercise-it-academy
Simple exercise for new Maven learners of the IT Learning & Training Academy

Exercise goals 

1. Understand and describe POM.xml strucutre
2. Edit POM adding dependecies and plugins 
3. Use properly Maven commands like "mvn clean, install..."

Precondition

1. Maven is installed on your machine, you should able to invoke mvn -version using your shell

2. You have read the https://maven.apache.org/what-is-maven.html

3. You have read https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

Exercise Steps

1. Download the code, navigate using a shell to the folder, open with a text notepad the file pom.xml, read comments 

2. Uncomment and update the "properties section", if you need please update you pom file using favorite java version, maven compiler source, maven compiler target

3. Invoke mvn commands "mvn clean install" using a shell, see Maven logs
 
4. Read the following text, you should know mvn commands

"mvn clean", removes the build artifacts and temporary files generated during the build process.

"mvn compile", compiles the source code of the project.

"mvn test", runs the unit tests for the project.
"mvn package", packages the compiled code and resources into an artifact (e.g., JAR, WAR).
"mvn install", builds the project, runs tests, packages the artifact, and installs it into the local Maven repository.
"mvn deploy", deploys the built artifact to a remote Maven repository, such as Nexus or Artifactory.
"mvn site", generates project documentation and reports, such as code coverage reports and JavaDoc.
"mvn dependency:tree", displays the dependency tree of the project, showing all the project's dependencies.
"mvn clean install", cleans the project, builds it, runs tests, packages the artifact, and installs it.
"mvn clean package", cleans the project, builds it, and packages the artifact.


5. Update "group id, artifact id, name" using you project informations 

6. Invoke mvn commands "mvn clean install", see Maven logs

7. Create the following structure "src/main/java", "src/main/resources"

8. Create a "main" Java class able to "Print Hello World" inside src/main/java folder

9. Add some dependency to the POM file and use it in the Hello World class

10. Create a Runnable Java JAR using the appropriate Maven JAR plugin

11. Use Maven profiles to customize builds for different environments activating different properties

