# CustomValidator-SpringBoot
 Custom Validator in spring boot with expection handler mechanism which helps to display appropriate errors in postman or any testing tools.
 Validtor check for unique email, IF exists in database throws email in use and username and password cannot be null.

Testing STEPS : (8080) /users

a)  Inserting data into the in memory database (h2)

{
  "username" : "admin",
  "password" : "password",
  "email" : "amdin1@gmail.com"
}

successful insert.

b) try the same with different option and the exception handler will pass customised message.
