# ORM eCommerce Backend

## Description
![badge](https://img.shields.io/badge/license-MIT-blue)

A backend for an e-commerce site. Uses MySQL2 database and Sequelize as the Object-Relational Mapping (ORM) tool to connect to an Express.js API. Uses the dotenv package to protect sensitive data.

Accessing the API routes in Insomnia:
![Screenshot](https://user-images.githubusercontent.com/54341829/118383986-66570e00-b5c8-11eb-81e1-16ae24c3eebe.png)

Watch a walkthrough video here: https://drive.google.com/file/d/1IHbTx-ri2u1sEMDGRf-YlrJZKk9gfgeR/view

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## Installation
Download the code, and do a npm install. Review the package.json and create a .env file with your own data. Run "mysql -u root -p" and then "source db/schema.sql" to create initial tables. Then, execute "npm run seed" to populate the database with seed data. Start the server with "npm start" and the API will start responding on localhost:3001.

## Usage
Use Insomnia or Postman to interact with the API. Consult the models for detailed information of each table and the association methods.

CATEGORIES ROUTES
http://localhost:3001/api/categories

- VieW All Employees
- View Single Category
- Create a new Category
- Update a Category
- Delete a Category

PRODUCTS ROUTES
http://localhost:3001/api/products

- VieW All Products
- View Single Product
- Create a new Product
- Create a new Product using minimal data
- Update a Product
- Update a Product using minimal data
- Delete a Product

TAGS ROUTES
http://localhost:3001/api/tags

- VieW All Tags
- View Single Tag
- Create a new Tag
- Update a Tag
- Delete a Tag

## License

MIT License Copyright
(view most recent version at https://spdx.org/licenses/MIT.html)

Permission is hereby granted, free of charge, to any person obtaining a copy 
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights 
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell 
copies of the Software, and to permit persons to whom the Software is 
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 
SOFTWARE.

## Questions
Find me on Github as: [luiscabrera77](https://github.com/luiscabrera77)

The best way to reach out with additional questions is to write me a detailed email. 

Happy coding!

luis.cabrera@gmail.com
