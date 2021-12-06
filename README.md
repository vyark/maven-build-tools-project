Multimodule project ***maven-gradle-build-tools-project*** contains 4 modules: admin, services, utils and web.
The project has the following structure:

jar<--admin\

|----services --- utils

war<-- web/

###Maven build instructions
To build the ***maven-gradle-build-tools-project***
1. open `cmd`
2. navigate to project folder (i.e. `C:\Users\{username}\IdeaProjects\maven-gradle-build-tools-project>`)
3. run `mvn clean install`

###Gradle build instructions
To build the ***maven-gradle-build-tools-project***
1. open `cmd`
2. navigate to project folder (i.e. `C:\Users\{username}\IdeaProjects\maven-gradle-build-tools-project>`)
3. run `gradlew classes` to compile the project
4. run `gradlew jar` to package jar
5. run `gradlew war` to package war
6. run `gradlew test` to execute tests

