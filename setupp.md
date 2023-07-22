## MySQL Setup and Import to RestAPI project

#### MySQL 8 version was used in this project. First, we install the Shell and Workbench options with the setup file downloaded from its website.
#### Secondly, we create a class named "User" and set the necessary parameters as private. After that, once we write the getter and setter codes, our user model class is ready.
#### After creating an interface named "UserRepo," we extend it from the User class using JPARepository. We will use this interface in the ApiController class.
#### Once we have set up the ApiController class, we can create a User object from the UserRepo class. Afterward, we write the codes for CRUD operations using the GetMapping technique. We prepare the written codes for the database and the API platform we are using to make them ready to use.
#### Once the code section is completed, we can proceed to configure the integration of the database in the application.properties file. Firstly, we specify the database URL path. Then, we define the username and password used, and set the database schema to update.

![bir](https://github.com/sefaerkan/Java-RestAPI/assets/36763407/1b591a6b-d522-4b19-9eb7-86f8d5d2f539)

![iki](https://github.com/sefaerkan/Java-RestAPI/assets/36763407/4b08ba91-db74-4664-95d4-3aaca1b8aea6)

![üc](https://github.com/sefaerkan/Java-RestAPI/assets/36763407/d0a857b5-617e-438d-b856-f4fd3e333373)

#### As a final step, we are adding specific dependencies to the "pom.xml" file present in our project to utilize the database.

![dort](https://github.com/sefaerkan/Java-RestAPI/assets/36763407/2ffe8018-d011-46b3-8e1b-3b5b3aade2e2)
