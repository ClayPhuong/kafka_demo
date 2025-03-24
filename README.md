**This project use JDK 17, Gradle 8.10**  
**Ensure installed docker and docker compose**
1. Run docker complose: ``` docker compose up ```
2. Build gradle: ``` ./gradlew bootRun ```
3. Run Spring Boot application
  
**This is crul for testing in postman**
```
curl --location --request POST 'http://localhost:8080/api/messages?message=Interesting'
```
