# Article Service


1. A system for creating and maintaining the articles. Article can have
fields like title, content, author and tags. 
2. I have used H2 as in memory database.
3. For API specifications I have used swagger for ease of testing and validating the response.
4. I have used default health check endpoint of actuator for this application. It can be accessed via `http://localhost:8080/actuator/health` this url. I have provided the custom health check endpoint as well.
5. You can access the swagger via `http://localhost:8080/swagger-ui.html`.


There are APIs present for:
1. Creating a new article
2. Updating an article
3. Deleting an article
4. Fetching an article
5. Fetching all the articles as per the title
### How to start the application?
```
For starting the application please import the application in any of the preferred IDE (Intellij, Eclipse, STS, etc.)

Application can be started by executing the main method present in class ArticlesApplication.
```

Tech-stack used
Spring Boot, Java, H2,Spring data Jpa, Swagger, Mockito

To run this application execute the `ArticlesApplication.java` file and visit the url `http://localhost:8080/swagger-ui.html`