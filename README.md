# ORM Challenge
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Demonstration](#demonstration)
- [Challenges Faced](#challenges-faced)
- [Author](#author)

## Description
The ORM Challenge involves building a functional Express.js API using Sequelize ORM for interacting with a MySQL database. The goal is to implement CRUD (Create, Read, Update, Delete) operations for managing categories, products, and tags.

## Installation
1. Clone the repository: `git clone https://github.com/Vontemilly/orm-challenge-dm.git`

2. Navigate to the project directory: `cd orm-challenge-dm`

3. Install dependencies: `npm install`

4. Create a `.env` file and add your database name, MySQL username, and MySQL password as environment variables.

## Usage
1. Ensure that your database name, MySQL username, and MySQL password are correctly set in the `.env` file.

2. Run `npm run seed` command in terminal to create and seed the development database with test data.

3. Start the application by running `npm start`.

4. Your server will be started, and the Sequelize models will be synced to the MySQL database.

5. Use Insomnia Core or any other API testing tool to test the API endpoints:
    - Use GET routes to retrieve data for categories, products, or tags. Verify that the data is displayed in a formatted JSON.
    - Test POST, PUT, and DELETE routes to create, update, and delete data in the database.

## Demonstration
[Watch the demonstration video](https://drive.google.com/file/d/17LHkEu1CdcZhaIzsVrzFhRMw3LIlway3/view?usp=sharing)

## Challenges Faced
- **Server Initialization**: Ensuring that the server is started correctly and Sequelize models are synced to the database upon application launch.
- **API Testing**: Testing API endpoints using Insomnia Core or similar tools to verify the functionality of CRUD operations.

## Author
### Devonte Miller
