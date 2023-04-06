# order-management-system-spring-boot-
Order Management app using Spring Boot

### Start the server to make sure the app is running properly
```
./mvnw spring-boot:run
```

### Close the server by Ctrl+C

### Package the application as a JAR file
```
./mvnw clean package -DskipTests
```

### Make a new dir and copy the application JAR file there
```
cp target/order-management-system-0.0.1-SNAPSHOT.jar src/main/app
```
### Build the docker image
```
docker build -t order-management-system-app .
```

### Running with Docker Compose
```
docker-compose up
```

### Stop all the containers
```
docker-compose down
```
