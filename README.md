# Guess the Capital
![Screenshot](public/images/background.jpg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Setup Instructions](#setup-instructions)
5. [Usage](#usage)
6. [Testing](#testing)
7. [Contributions](#contributions)
8. [License](#license)

## Description
This web application allows users to guess the capital cities of various countries. It is built using EJS for templating, JavaScript for both client and server-side logic, and PostgreSQL for database management.

## Features
- Dynamic Templating: Uses EJS to create reusable templates and dynamic content.
- Interactive Frontend: Implements JavaScript for enhanced user interactions and responsive UI.
- Database Integration: Connects to a PostgreSQL database for storing and retrieving application data.
- Express Framework: Utilizes the Express.js framework for efficient routing and middleware management.

## Prerequisites
- Node.js
- PostgreSQL
- npm (Node Package Manager)

## Setup Instructions
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/umeshkarthik1606/guess-the-capital.git

2. **Install Dependencies**:
   ```sh
   npm install express body-parser pg

3. **Configure Database**:

   [Download CSV file](https://github.com/umeshkarthik1606/guess-the-capital/blob/main/capitals.csv) <br>
   Set up your PostgreSQL database and update the connection settings in the .env file.

5. **Run the Application**:
   ```sh
   node index.js

## Usage
+ Development:
  ```sh
  npm run dev

+ Production:
  ```sh
  npm start

## Testing
+ To run tests:
  ```sh
  npm test

## Contributions

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the [MIT License](https://github.com/umeshkarthik1606/guess-the-capital/blob/main/LICENSE).


