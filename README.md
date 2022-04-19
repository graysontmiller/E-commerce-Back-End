# E-commerce-Back-End

# Description

The Back end for an e-commerce site. utilizes the Sequelize ORM library to interact with a MySQL db. A user is able to perform CRUD requests on various items, tags, and categories within the online store's database to help manage product inventory.

# Installation

1. Clone the repository to desired location.
2. Download NPM packages: <code> npm i </code>
3. Create your .env file with the following code:
    - <code>DB_NAME='ecommerce_db'</code>
    - <code>DB_USER='your username here'</code>
    - <code>DB_PW='your password here'</code>
4. Open the MySQL shell and run these commands:
    - <code> SOURCE db/schema.sql; </code>
    - <code> USE ecommerce_db; </code>
5. Optionally seed the database in the bash terminal with <code> npm run seed </code>
6. Start application <code> npm start </code>

# Technologies employed

- Express
- Node.js
- MySQL2
- Sequelize
- Insomnia (for testing routes)

# Video DEMO
