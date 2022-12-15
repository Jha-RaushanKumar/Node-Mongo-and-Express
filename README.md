## Topic:(Node, Express & MongoDB)

Author: `Raushan Kumar Jha`  
Instructor: `Vishal Chawla`
## INFO 6150 Assignment8

Node, Mongo, and Express (No need for UI, you can run the APIs on postman). Use bcrypt for password security.

1. Create a user which takes 3 parameters full name, email and password. Enforce strong password rule and add validation for email and full name.  
API Endpoint:  
    POST: `/user/create` – User creation with a meaningful message if the user email or password is invalid)

2. Update the user details (full name and password only). Email should not get updated at any point. Proper error msg should be thrown if user is not present in the database.  
API Endpoint:  
    PUT: `/user/edit` – Add validations for full name and password

3. Delete the user by taking the user's email as input.  
API Endpoint:  
    DELETE: `/user/delete`

4. Get all the user's full name, email addresses and passwords stored in the database.  
API Endpoint:  
    GET: `/user/getAll`

## Technologies used:

1. MongoDB
2. NodeJS
3. Express
