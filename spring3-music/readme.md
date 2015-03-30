
Minimal swagger-spring-mvc config using web jar for swagger ui import.
```
./gradlew :swagger-ui:publishToMavenLocal
./gradlew :spring3-music:tomcatRun
```


http://localhost:9080/spring3-music/sdoc.jsp
You'll need to change the API url to be:
http://localhost:9080/spring3-music/api-docs