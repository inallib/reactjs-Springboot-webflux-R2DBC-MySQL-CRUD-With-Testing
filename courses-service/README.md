# Running the service
- Download the maven dependency and build the project with JDK 8 - Go to `cd course-service` and run `mvn install`
- You may change the mysql connection string (if you are not running mysql locally or database name is not `db`) in `./resources/application.properties`
- Run the application `mvnw spring-boot:run`

# Running the unit test suit
run `mvn test`
