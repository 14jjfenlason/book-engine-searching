# Book Search Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The Book Search Engine is a web application that allows users to search for books using the Google Books API. Users can create an account, search for books, save books to their profile, and manage their saved books. The application is built using the MERN stack (MongoDB, Express.js, React, and Node.js) and utilizes GraphQL API for efficient data retrieval.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run the Book Search Engine locally, follow these steps:

1. Clone the repository
2. Navigate to the project directory
3. Install the dependencies for both the server and client
4. Set up the environment variables:
- Create a `.env` file in the `server` directory.
- Add the following environment variables to the `.env` file:
  ```
  MONGODB_URI=your-mongodb-uri
  JWT_SECRET=your-jwt-secret
  ```
- Replace `your-mongodb-uri` with your MongoDB connection URI and `your-jwt-secret` with a secure secret for JWT authentication.

5. Start the development server
6. Open your browser and visit `http://localhost:3000` to access the application.

## Usage

- Create an account or log in to an existing account.
- Use the search bar to search for books by title, author, or keywords.
- Click on a book to view more details.
- Click the "Save" button to save a book to your profile.
- Visit the "Saved Books" page to view and manage your saved books.
- Click the "Delete" button to remove a book from your saved books.

## Technologies

The Book Search Engine utilizes the following technologies:

- MongoDB: A NoSQL database for storing user and book data.
- Express.js: A web application framework for building the server-side API.
- React: A JavaScript library for building user interfaces.
- Node.js: A JavaScript runtime environment for server-side development.
- GraphQL: A query language for APIs, used for efficient data retrieval.
- Apollo Server: A GraphQL server for handling GraphQL requests and responses.
- JSON Web Tokens (JWT): A standard for securely transmitting information between parties as a JSON object.
- Bootstrap: A CSS framework for responsive and mobile-first web development.

## Contributing

Contributions are welcome! If you would like to contribute to the Book Search Engine, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

Please ensure that your code follows the project's coding conventions and includes appropriate tests.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to modify and distribute the code as per the terms of the license.
Made by Joshua Fenlason.
