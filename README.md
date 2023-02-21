# Cinema-app

---
![markdown_logo](https://www.pngall.com/wp-content/uploads/13/Movie-Hollywood-PNG-File.png)

### Project description:
This is a simple application, which supports authentication, creating shopping cart and buying tickets on 
different movie sessions. Also, the application supports registration for new customers and *CRUD* operations.

### Features:

---
- register or login as user
- create and find movies
- create and find cinema-hall
- create and find available movie sessions
- creating shopping cart
- add tickets to shopping cart
- complete an order;

### Project structure (3-layer architecture):

---
1. *DAO* - handle CRUD operations to database.
2. *Service* - there are all business logic.
3. *Controllers* - handle requests, call services and send responses.

### Used technologies and libraries:

---
- Java 11
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- Hibernate
- Spring
- Spring Security
- Spring Web
- Checkstyle plugin
- Apache Log4j 2

### Instructions to run the project:

---
- Install [IDE](https://www.jetbrains.com/help/idea/installation-guide.html);
- Install [MySQL](https://dev.mysql.com/downloads/installer/);
- Install [Apache Tomcat version: 9.0.xx](https://tomcat.apache.org/download-90.cgi);
- Clone the repo: [https://github.com/AntonKalenskiy/cinema-app](https://github.com/AntonKalenskiy/cinema-app);
- Configure Apache Tomcat version: 9.0.xx;
- Configure [/src/main/resources/db.properties](./src/main/resources/db.properties) with your URL, USERNAME, PASSWORD, DRIVER;
- Configure [/src/main/resources/log4j2.xml](./src/main/resources/log4j2.xml) at line 7 with your ABSOLUTE_PATH to this project;
- Enjoy the application.
