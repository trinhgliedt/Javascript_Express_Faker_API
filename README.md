  # Javascript_Express_Faker_API
<h1>An api that generates a random user on a GET request. Using Postman to make GET requests.</h1>

2 javascript libraries are used to create a simple API that generates a User and/or Company depending on the route:

 - Express (Server)
 - Faker (Fake data generator)
 
 
 * User class
    * _id
    * firstName
    * lastName
    * phoneNumber
    * email
    * password
 
* Company class
  * _id
  * name
  * address
  * street
  * city
  * state
  * zipCode
  * country
  
  <h3>Tasks:</h3>
  
  - [x] Create a new project folder "Faker_API" and with your terminal, navigate into your new folder
  - [x] Create a package.json file using the "npm init -y" command in your terminal
  - [x] Install express and faker
  - [x] Create a server.js file
  - [x] In your server.js file, Import express and faker
  - [x] Create 2 classes: User, Company with the same attributes as listed above
  - [x] Create an api route "/api/users/new" that returns a new user
  - [x] Create an api route "/api/companies/new" that returns a new company
  - [x] Create an api route "/api/user/company" that returns both a new user and a new company
  - [x] Run your server.js file using nodemon
  - [x] Using Postman to new GET routes
