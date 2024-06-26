# TO DO LIST

A simple CRUD (Create, Read, Update, Delete) operations project using PostgreSQL for the database, Express.js for the backend, and EJS for the frontend.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project serves as a basic template for building web applications that require CRUD functionality. It utilizes PostgreSQL as the database to store and manage data, Express.js as the backend framework to handle server-side logic and API endpoints, and EJS (Embedded JavaScript) as the templating engine for generating dynamic HTML content on the frontend.

## Features

- **Create**: Add new items to the database.
- **Read**: Retrieve and display existing items from the database.
- **Update**: Modify and update existing items in the database.
- **Delete**: Remove items from the database.

## Installation

1. Clone the repository:

2. Navigate to the project directory:

   ```bash
   cd To-do-list
3. Install dependencies:

   ```bash
   npm install
4. Set up the PostgreSQL database:
   
   - Create a PostgreSQL database named permalist and create a table named items.
   - Run the queries from `queries.sql`
   - Update the database connection in index.js
5. Run the application:

   ```bash
   npm start
6. Open your web browser and go to `http://localhost:3000` to view the application.

## Usage

- To add a new item, press the symbol "+" 
- The items or tasks will be added to the list present at the center of the view.
- To update an item, click on the "pencil" icon to edit.
- To delete an item, check the box on left to make it complete or delete the existing item.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvement.
   
