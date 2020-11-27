# Node Express Handlebars

### Overview

In this assignment, I created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). The assignement required to follow the MVC design pattern; use Node and MySQL to query and route data in the app, and Handlebars to generate the HTML.


* **This assignment was required to be deployed.** Utilized the [MYSQL Heroku Deployment Guide](../../03-Supplemental/MySQLHerokuDeploymentProcess.pdf) in order to deploy the assignment.

### What is Eat-Da-Burger?

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

* Your app will store every burger in a database, whether devoured or not.

(../assets/images/da burger app.png)

* **This assignment must be deployed.** * The links were submitted for both the deployed Heroku AND the Github Repository.


#### Directory structure

All the recommended files and directories of the app:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars



Link to Heroku: 
