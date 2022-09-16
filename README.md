# CloudFileStorage
Project "CloudFileStorage"  Multi-user file cloud. Service users use it to download and store files. source of inspiration for project is Google Drive.

## Functional Applications
### Working with users:

* Registration.

* Authorization.

* logout.

### Working with files and folders:

* Uploading files and folders.

* Create a new empty folder (similar to creating a new folder in conductor).

* Removal.

* Renaming.

### Application work plan:

* Docker Compose - Add MySQL.

* Spring Boot - with Spring Security, Thymeleaf and Spring Data JPA implement user registration and authorization.

* Docker Compose - add MinIO.

* Spring Boot - Integrate AWS Java SDK and learn how to operate with files in a bucket, write a service that encapsulates the necessary operation applications.

* Implement the upload of files and folders through the form (forms) on the main page.

* Implement file display and directory structure navigation, actions with files (delete, rename). 

* Search Files - Service, Controller and Thymeleaf Template.

* Docker Compose - Add Redis.

* Spring Sessions - configure session storage inside Redis.
