# Burger

The burger logger application allows the user to add new burger, devour it or delete it from the list. 
The application uses MySQL, Node, Express, Handlebars and ORM. The application has following HTML routes:

    * GET `/` -renders all the burgers in the db and displays on the page
    * POST `/burgers` - adds new burger to the db
    * PUT `/burgers/:id` - changes status when burger is devoured
    * DELETE `/burgers/:id` - removes burger from the db
## Application Features

The user accesses the application deployed on Heroku. The application has following features:
  * The user can enter the name of the new burger and add it to the list
  * The user can select any burger from New Burgers list and devvour it. This will move the burger to devoured list
  * The user can remove the burger from the list by clicking the delete burtton
## Application Features
  * node.js
  * express.js
  * handlebars
  ^ MYSQL
## Usage
  * Fork application from [github](https://github.com/asheth22/Burger/tree/main/public/assets)
  * Initialize npm and install npm packages: express, express-handlebars, and mysql
  * Run application from command line with: node server.js

 ## Application URL

* The URL of the deployed application in Heroku [Eat-Da-Burger](https://polar-castle-85742.herokuapp.com/)

## Application Demo

* Demo of the application [Burger](https://github.com/asheth22/Burger/tree/main/public/assets/Burger.gif )

