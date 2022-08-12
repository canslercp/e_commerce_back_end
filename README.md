# Object-Relational Mapping (ORM): E-Commerce Back End

## Description

Built the back end for an e-commerce site by modifying starter code from the Georgia Tech Coding Bootcamp curriculum. Essentially, I configured a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application does not include a front-end, you’ll need to open the link to a walkthrough video that demonstrates its functionality.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

## My contributions

* Created a database that contains the following four models: Category, Product, Tag, and ProductTag

* Executed association methods on the Sequelize models to create relationships between them.

* Filled out the API routes to perform RESTful CRUD operations

* Created the code needed in `server.js` to sync the Sequelize models to the MySQL database on server start.

## Video Walkthrough

The walkthrough video shows the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

[Link to video walk through](https://drive.google.com/file/d/1W7Ddxv5t27I4TI0GQtohsIoh8Yyh9qrj/view?usp=sharing)
