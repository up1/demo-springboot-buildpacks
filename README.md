# Spring boot 2.3.0 M1 with Buildpacks

### Run with Apache Maven
```
$mvnw clean spring-boot:build-image
```

### Woking with Layesred JAR
```
$mvn clean package
$java -Djarmode=layertools -jar target/demo_container-0.0.1-SNAPSHOT.jar list
$java -Djarmode=layertools -jar target/demo_container-0.0.1-SNAPSHOT.jar extract
```
