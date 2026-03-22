# Create Node Spark 🚀

![GitHub Release](https://img.shields.io/github/release/Advanced-vyra/create-node-spark.svg?style=flat-square)

Welcome to **Create Node Spark**, a command-line interface (CLI) tool designed to help you scaffold scalable, production-ready Node.js backends quickly and efficiently. With this tool, you can set up your project with Express, JWT, dotenv, ESM, and ESLint in just seconds. This README will guide you through the installation, usage, and features of Create Node Spark.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [License](#license)
- [Contributing](#contributing)
- [Support](#support)
- [Changelog](#changelog)

## Features

- **Fast Setup**: Create a complete backend structure in seconds.
- **Production-Ready**: Built with best practices in mind.
- **Modular Architecture**: Easily extendable and maintainable.
- **Support for JWT**: Secure your API with JSON Web Tokens.
- **Environment Variables**: Use dotenv for configuration management.
- **Modern JavaScript**: Leverage ESM for module support.
- **Code Quality**: ESLint integration ensures clean code.
- **MongoDB and Mongoose**: Seamlessly integrate with MongoDB for data management.

## Installation

To get started with Create Node Spark, first ensure you have Node.js installed on your machine. You can download it from [Node.js official website](https://nodejs.org/).

Once Node.js is installed, you can install Create Node Spark globally using npm:

```bash
npm install -g create-node-spark
```

## Usage

After installation, you can scaffold a new project by running:

```bash
create-node-spark my-new-project
```

This command will create a new directory called `my-new-project` with all the necessary files and folders.

For more information on the command-line options, you can run:

```bash
create-node-spark --help
```

## Project Structure

When you scaffold a new project, you will see the following structure:

```
my-new-project/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .env
├── .eslintrc.js
├── package.json
└── README.md
```

### Description of Folders

- **src/**: Contains all the source code.
  - **config/**: Configuration files, including database connections.
  - **controllers/**: Business logic for handling requests.
  - **models/**: Mongoose models for MongoDB.
  - **routes/**: API routes for your application.
  - **server.js**: The entry point for your application.
  
- **.env**: Environment variables for configuration.
- **.eslintrc.js**: ESLint configuration file.
- **package.json**: Contains project metadata and dependencies.

## Configuration

### Environment Variables

Create a `.env` file in the root of your project to manage your environment variables. Here’s an example:

```
PORT=3000
DB_URI=mongodb://localhost:27017/mydatabase
JWT_SECRET=mysecretkey
```

### ESLint Configuration

You can customize your ESLint rules in the `.eslintrc.js` file. This file contains various settings that help maintain code quality and consistency.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

We welcome contributions to Create Node Spark! If you would like to contribute, please fork the repository and submit a pull request. 

Before submitting, ensure that your code follows the ESLint rules defined in the project.

## Support

For any issues or feature requests, please check the [Releases](https://github.com/Advanced-vyra/create-node-spark/releases) section or open an issue in the GitHub repository.

## Changelog

For the latest updates, features, and bug fixes, please refer to the [Releases](https://github.com/Advanced-vyra/create-node-spark/releases) section.

## Conclusion

Create Node Spark is your go-to tool for quickly scaffolding Node.js backends. Whether you are a beginner or an experienced developer, this CLI tool streamlines your workflow and helps you focus on building great applications.

Explore the [Releases](https://github.com/Advanced-vyra/create-node-spark/releases) for the latest versions and updates. Happy coding!