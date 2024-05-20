# Luis's E-Commerce Website Back End


## This Challenge contains Luis's E-Commerce Website Back End to include the following functions:
- Allows users to save data for thier E-Commerce Websites for their internet retail company
- The following data can be saved and reviewed:
1. Category:
 - Allows user to GET routes for all the categories
 - Allows user to GET route for a single category(:id number)
 - Allows user to POST(create a new category), PUT(update an existing category), and DELETE(delete an existing category) routes

2. Product:
 - Allows user to GET routes for all the products
 - Allows user to GET route for a single product(:id number)
 - Allows user to POST(create a new product), PUT(update an existing product), and DELETE(delete an existing product) routes


3. Tag:
 - Allows the user to GET routes for all the Tags
 - Allows user to GET route for a single Tag(:id number)
 - Allows user to POST(create a new Tag), PUT(update an existing Tag), and DELETE(delete an existing Tag) routes





## Installation
- To Access the E-Commerce Website Back End repository: https://github.com/ricanlonghorn23/E-Commerce-Backend-Website.git

- To Access video to see E-Commerce Website Back End demonstration: https://drive.google.com/file/d/14BwPKGNjsh45U1jzp-u0adkelNSmkjMC/view?usp=sharing



## Usage
The user will go to the file in which the E-Commerce-Backend-Website code is located. They will type in “npm install sequelize” via the terminal to install the sequelize. The user will then type in "npm install pg" to install the Postgres package. The user will then type in "npm install dotenv --save" to install dotenv package. The user will then navigate via the terminal to the db folder. They will then run 'psql -U postgres'. They will then run "\i schema.sql". They will then type \q to exit Postgres. The user will then navigate via terminal back to the Develop folder. The user will type in “npm run seed” via the terminal to seed data to the user's database. The user will type in “npm start” via the terminal to start user's server. The user will then access the insomnia application ot test their routes. The following can be run:

1. Category:
 - Run the following to GET routes for all the categories: GET http://localhost:3001/api/categories
 - Run the following to GET routes for a single product(:id number): GET http://localhost:3001/api/categories/(type Id # here)
 - Run the following to POST(create a new category), PUT(update an existing category), and DELETE(delete an existing category) routes:
   - POST http://localhost:3001/api/categories/
   - PUT http://localhost:3001/api/categories/(type Id # here)
   - DELETE http://localhost:3001/api/categories/(type Id # here)

2. Product:
 - Run the following to GET routes for all the products: GET http://localhost:3001/api/products
 - Run the following to GET routes for a single product(:id number): GET http://localhost:3001/api/products/(type Id # here)
 - Run the following to POST(create a new product), PUT(update an existing product), and DELETE(delete an existing product) routes:
   - POST http://localhost:3001/api/products/
   - PUT http://localhost:3001/api/products/(type Id # here)
   - DELETE http://localhost:3001/api/products/(type Id # here)


3. Tag:
 - Run the following to GET routes for all the Tags: GET http://localhost:3001/api/tags
 - Run the following to GET routes for a single Tag(:id number): GET http://localhost:3001/api/tags/(type Id # here)
 - Run the following to POST(create a new tag), PUT(update an existing tag), and DELETE(delete an existing tag) routes:
   - POST http://localhost:3001/api/tags/
   - PUT http://localhost:3001/api/tags/(type Id # here)
   - DELETE http://localhost:3001/api/tags/(type Id # here)
   

## Credits
Luis Aldaz
