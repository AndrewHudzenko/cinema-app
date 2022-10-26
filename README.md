# 📽️ Cinema-app 📽️
### Description:
This is a simple version of the cinema app. \
You can send various HTTP requests(GET, POST, PUT, DELETE) \
to add or receive some info about movies, cinema halls, orders, movie sessions.

### Structure:
The project has N-Tier Architecture:
> - DAO(data access object) layer - all work with database(CRUD)
> - Service layer - all business logic
> - Controller layer - accept requests and send responses

### Technologies:
> - Java 11
> - Hibernate
> - Spring MVC
> - Spring Security
> - Tomcat (9.0.50)
> - MySQL
> - Maven

### Functionality:
> - Registration
> - Log in / Log out
> - User has the opportunity to purchase tickets for a movie session
> - Admin has the ability to create/delete new session, new movie

### To run the project - follow steps below:
1. Fork this repository
2. git clone <your link>
3. Configure db.properties - set necessary parameters:
>```properties
>db.driver=YOUR_DRIVER
>db.url=YOUR_URL
>db.user=YOUR_USERNAME
>db.password=YOUR_PASSWORD
>```
4. Install **[Tomcat](https://tomcat.apache.org/download-90.cgi)**
5. Configure Tomcat in IDE
6. Run project
