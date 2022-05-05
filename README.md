# Shop Lyft E-Commerce Back End

## Description
As a manager at an internet retail company, I wanted to produce a back end for our e-commer website 'Shop Lyft'. This will allow our company to remain competitive against other e-commerce stores by keeping all of our products organized and on record. 

Refer to the [Walkthrough Demonstration Video](https://github.com/gemsjohn/shop-lyft/blob/main/assets/shop-lyft-demo.mp4) for this application. The demo will demonstrate the following:

<u>Launch</u>

- Ability to start the server and sync with the function Express.js API

<u>Categories</u>

- Use GET /api/categories to retrieve all categories
- Use GET /api/categories/:id to review a specific category
- Use POST /api/categories to create a new category
- Use PUT /api/catergories to update an existing category
- Use DELETE /api/categories/:id to delete an existing category

<u>Products</u>

- Use GET /api/products to retrieve all products
- Use GET /api/products/:id to review a specific product
- Use POST /api/products to create a new product
- Use PUT /api/products to update an existing product
- Use DELETE /api/products/:id to delete an existing products

<u>Tags</u>

- Use GET /api/tags to retrieve all tags
- Use GET /api/tags/:id to review a specific tag
- Use POST /api/tags to create a new tag
- Use PUT /api/tagsto update an existing tag
- Use DELETE /api/tags/:id to delete an existing tag

## Installation
- `git clone git@github.com:gemsjohn/shop-lyft.git`
- Open the cloned folder in Visual Studio
- Create a .env file with the following content:
    `DB_NAME='shop_lyft'`
    `DB_USER='root'`
    `DB_PW='password'`
- Right click /seeds/index.js and select Open in Integrated Terminal
- Enter `node index.js` : this will load the seed files
- Enter `cd ..`
- Enter `node server.js` : this will start the Express.js server
- Open Insomnia and create GET, POST, PUT, DELETE requests as needed
- Use http://localhost:3001/api/ 
    - categories
    - products
    - tags

## Usage
- Express.js
- dotenv
- Insomnia
- MySQL2
- Sequelize

## Images
![Example Image](https://github.com/gemsjohn/shop-lyft/blob/main/assets/insomnia-screenshot.png)