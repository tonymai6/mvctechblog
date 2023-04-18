# MVC Tech Blog

This repository contains the source code for an MVC (Model-View-Controller) Tech Blog, a web application where users can create, edit, and delete blog posts and comments about the latest developments in technology.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Contributing](#contributing)
6. [License](#license)

## Installation

To set up the MVC Tech Blog on your local machine, follow these steps:

1. Clone this repository to your local machine.
git clone https://github.com/tonymai6/mvctechblog.git

2. Change directory to the project folder.
cd mvc-tech-blog

3. Install required dependencies.
npm install

4. Set up the required environment variables by creating a `.env` file in the root directory. Configure it with the following variables:
DB_NAME='your_database_name'
DB_USER='your_database_user'
DB_PASSWORD='your_database_password'
SESSION_SECRET='your_session_secret'

5. Create the database using the schema.sql file located in the `db` folder.

6. Seed the database (optional):
npm run seed

## Usage

To start the server and launch the application, run the following command in the terminal:
npm start

Open your browser and navigate to `http://localhost:3001` to access the MVC Tech Blog.

## Features

- User authentication with secure password hashing
- Create, edit, and delete blog posts
- Add and delete comments on blog posts
- User dashboard for managing personal blog posts
- Responsive design for both desktop and mobile devices

## Technologies Used

- Node.js
- Express.js
- Handlebars.js
- Sequelize (ORM)
- MySQL (database)
- bcrypt (password hashing)
- express-session and connect-session-sequelize (session management)
- Bootstrap (front-end framework)

## Contributing

If you'd like to contribute to the development of the MVC Tech Blog, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes with descriptive messages.
4. Push your changes to your fork.
5. Open a pull request describing your proposed changes.

## License

This project is licensed under the MIT License.
