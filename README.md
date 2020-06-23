# P2Interim

## Project Demo 
https://mighty-caverns-14844.herokuapp.com/

## Application MVP
- A full stack application using **Node.js, Mongoose, Express and EJS** - backend oriented
- Build based on the **MVC** file structure: Models, Views, Controllers
- Include all **RESTful routes** and a full **CRUD** application.
- Deployed online via **Heroku**

## Technologies / Node.JS libraries used and rationale
### 1. EJS
To generate HTML with plain javascript to append to frontend.
### 2. Method-override
To use HTTP verbs such as PUT or DELETE in places where the client doesn't support it
### 3. Bcrypt
To hash and store passwords in database
### 4. PassportJS
To handle authenticate requests
### 5. Mongoose
Database for application, which helps in schema validation, and to translate between objects in code and the representations of those objects in MongoDB
### 6. Connect-flash
Storing of messages, and displaying it on frontend whenever user perform a CRUD operation and is being redirected.
### 7. Express-session
- To store the user state with each given being assiged a unique session. 
- Ecrypting cookies
### 8. MomentJS
Wrapper to handle Date object
### 9. DataTables
Enhanced features for HTML table
### 10. Nodemailer
To allow server to send email notification to user
### 11. Node-cron
To schedule task on specific timing for server to send email
### 12. Bootstrap
CSS framework for HTML and CSS design templates




