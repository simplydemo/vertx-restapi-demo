# vertx-restapi-demo

This is a demo project that includes Restful API samples and JUnit 5 test classes based on vertx 4.x and java 17.

<br>

## Build
```
mvn clean package
```

<br>

## Run
```
java -jar target/vertx-rest-demo-*.jar
```

<br>

## Check
```
curl -v -l http://localhost:8080/health

curl -v -l http://localhost:8080/users/hello
```

<br>

## References
- [vertx-examples](https://github.com/vert-x3/vertx-examples)
