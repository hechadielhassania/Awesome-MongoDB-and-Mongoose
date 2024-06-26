# MongoDB and Mongoose with Node.js and ExpressJS
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hechadielhassania/Awesome-Express.js)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

Welcome to the MongoDB and Mongoose with Node.js and ExpressJS starter kit! This repository provides a comprehensive guide and resources to help you get started with building web applications using MongoDB, Mongoose, Node.js, and ExpressJS.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
   - [1. Installation](#1-installation)
   - [2. Setting Up Your Node.js App](#2-setting-up-your-nodejs-app)
   - [3. Connecting to MongoDB](#3-connecting-to-mongodb)
3. [Tutorials and Learning Resources](#tutorials-and-learning-resources)
4. [Books](#books)
5. [Articles and Guides](#articles-and-guides)
6. [Videos](#videos)
7. [Plugins and Tools](#plugins-and-tools)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

MongoDB is a popular NoSQL database known for its flexibility and scalability. Mongoose is an elegant MongoDB object modeling tool designed for Node.js. Together with Node.js and ExpressJS, they form a powerful stack for building modern web applications.

## Getting Started

### 1. Installation

- **Node.js**: Install Node.js from the [official website](https://nodejs.org/).
- **MongoDB**: Download and install MongoDB from the [MongoDB Download Center](https://www.mongodb.com/try/download/community).

### 2. Setting Up Your Node.js App

1. **Initialize Your Node.js Project**:
   - Create a new directory for your project.
   - Run `npm init` to initialize your project and follow the prompts.

2. **Install Dependencies**:
   ```bash
   npm install express mongoose

3. Create Your Express.js App:
  - Require Express and Mongoose in your main application file (app.js or server.js).
  - Initialize Express and set up your routes.

### 3. Connecting to MongoDB

1. **Connect to MongoDB:
  - Use Mongoose to connect to your MongoDB database.
  - Configure Mongoose connection options such as useNewUrlParser and useUnifiedTopology.
    ```bash
    const express = require('express');
    const mongoose = require('mongoose');
    
    const app = express();
    
    // Connect to MongoDB
    mongoose.connect('mongodb://localhost:27017/my_database', { useNewUrlParser: true, useUnifiedTopology: true });
    
    // Start the server
    const PORT = process.env.PORT || 3000;
    app.listen(PORT, () => {
      console.log(`Server is running on port ${PORT}`);
    });

## Tutorials and Learning Resources
  - **[MongoDB University](https://learn.mongodb.com/)**: Official MongoDB training and certification.
  - **[Mongoose Documentation](https://mongoosejs.com/docs/)**:  Official documentation for Mongoose.
  - **[Express.js Documentation](https://expressjs.com/)**:  Official documentation for Express.js.
  - **[Node.js Documentation](https://nodejs.org/docs/latest/api/)**: Official documentation for Node.js.

## Books
  - **["MongoDB: The Definitive Guide"](https://www.amazon.com/MongoDB-Definitive-Powerful-Scalable-Storage/dp/1491954469)**: by Kristina Chodorow and Shannon Bradshaw.
  - **["Mastering MongoDB 4.x"](https://www.amazon.com/Mastering-MongoDB-4-x-high-fault-tolerant/dp/1789617871)**: by Alex Giamas.

## Articles and Guides
  - **["Getting Started with MongoDB"](https://www.mongodb.com/docs/)**: Official MongoDB getting started guide.
  - **["Building RESTful APIs with Node.js, Express, and MongoDB"](https://www.mongodb.com/resources/languages/express-mongodb-rest-api-tutorial)**

## Videos
  - **["Node.js and MongoDB Tutorial Series by The Net Ninja"](https://www.youtube.com/playlist?list=PL4cUxeGkcC9jpvoYriLI0bY8DOgWZfi6u)**
  - **["Mongoose.js Tutorial Series by The Net Ninja"](https://www.youtube.com/watch?v=ExcRbA7fy_A&list=PL4cUxeGkcC9h77dJ-QJlwGlZlTd4ecZOA)**

## Plugins and Tools

   ### Express Middleware
   
  - **["body-parser"](https://www.npmjs.com/package/body-parser)**: Parse incoming request bodies.
  - **["cors"](https://www.npmjs.com/package/cors)**: Enable Cross-Origin Resource Sharing (CORS).
  - **["helmet"](https://www.npmjs.com/package/helmet)**: Secure your Express apps with various HTTP headers.

   ### Mongoose Plugins
   
   - **["mongoose-paginate-v2"](https://www.npmjs.com/package/mongoose-paginate-v2)**: Paginate MongoDB queries.
   - **["mongoose-unique-validator"](https://www.npmjs.com/package/mongoose-unique-validator)**: Validate unique fields in Mongoose schemas.


## Contributing
Contributions are welcome! If you have any suggestions, improvements, or additional resources to add, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

To the extent possible under law, [El Hassania Hechadi](https://hechadielhassania.github.io) has waived all copyright and related or neighboring rights to this work.


