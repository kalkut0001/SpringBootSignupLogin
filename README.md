# SpringBoot with MongoDB

Install mongodb.
Add db name : moon_db
Add collections: users, roles

insert below data:
db.roles.insertMany([
{ name: "ROLE_USER" },
{ name: "ROLE_MODERATOR" },
{ name: "ROLE_ADMIN" },
])


## Run Spring Boot application
```
mvn spring-boot:run
```
