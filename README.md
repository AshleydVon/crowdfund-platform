# Crowdfunding-Platform


## Description
This is a crowdfunding web application built using Node.js, Express.js, Sequelize ORM, and Handlebars.js. Users can create, view, and fund projects.


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)


## Installation
1. Clone the repository
2. Install dependencies: `npm install`
3. Set up your PostgreSQL database
4. Create a `.env` file with your database credentials:
    
    DB_NAME='crowdfund_db'
    DB_USER='your_username'
    DB_PASSWORD='your_password'

5. Run database migrations: `npx sequelize-cli db:migrate`
6. Seed the database: `npm run seed`


## Usage
1. Start the server: `npm start`
2. Open your browser and navigate to `http://localhost:3001`
3. Create an account or log in
4. Create, view, or fund projects


## Features
- User authentication (signup, login, logout)
- Create and delete projects
- View all projects on the homepage
- View detailed project information
- Fund projects (frontend only, no actual payment processing)


## Technologies Used
- Node.js
- Express.js
- Sequelize ORM
- PostgreSQL
- Handlebars.js
- bcrypt for password hashing
- express-session for session management
- dotenv for environment variable management


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.





## License
This project is licensed under the ISC License.