# Natural Language to SQL Query Converter

This project is a full-stack application designed to transform natural language input into SQL queries by leveraging OpenAI's GPT-3.5 architecture and its text completion API. The app structure comprises two main parts: the client and the server, each with separate npm packages.

## Initial Setup

To get started, clone the repository to your local machine and navigate to the project's root directory. You will find two main folders: `client` and `server`. Each of these directories contains its own `package.json` file and `node_modules` folder.

### Installing Dependencies

To set up the client dependencies, go to the `client` directory and execute:

```bash
npm install
```

For the server dependencies, navigate to the `server` directory and run:

```bash
npm install
```

## Starting the Client

To launch the client, move to the `client` directory and use the following command:

```bash
npm run dev
```

The client will then be accessible at [http://localhost:3000/](http://localhost:3000/).

## Starting the Server

To start the server, go to the `server` directory and execute:

```bash
npm start
```

## Technologies Used

The front-end of the application is built using React, while the back-end is constructed with Node.js and Express.

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)