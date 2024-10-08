# Perlego Frontend Assessment

This project implements a grid component that displays books a user might enjoy, using React JS, SCSS Modules, and state management with Redux.

[Loom Video](https://www.loom.com/embed/a0070a1aa8af448a9f1e8701ace9c90d?sid=1fbc215c-4b28-4348-8761-c4470631edf6)



## Table of Contents
- [Description](#description)
- [Base dependencies](#base-dependencies)
- [Installation](#installation)
- [Running the application](#run-the-application)
- [Running the automated tests](#run-automated-unit-and-integration-tests)
- [Screenshots](#screenshots)

## Description
The "Books You Might Like" grid component is designed to show a collection of recommended books based on user preferences. The frontend is built with React JS, styled using SCSS Modules, and Redux for state management. Axios is used to fetch data from the API, and Formik with Yup manages form validation.

## Frontend Base dependencies

- [axios](https://github.com/axios/axios 'Axios') for networking.
- [scss modules](https://sass-lang.com/) to manage styling.
- [react-router-dom](https://reactrouter.com/en/main 'React Navigation') navigation library.
- [formik](https://formik.org/docs/overview) to manage forms.
- [redux](https://redux.js.org/ 'Redux') for state management.
- [redux-persist](https://github.com/rt2zz/redux-persist 'Redux Persist') as persistance layer.
- [redux-toolkit](https://github.com/gaearon/redux-thunk 'Redux Toolkit') to dispatch asynchronous actions.

## Backend Base dependencies

- [bcryptjs](https://www.npmjs.com/package/bcryptjs) for password hashing.
- [body-parser](https://www.npmjs.com/package/body-parser) to parse incoming request bodies.
- [celebrate](https://www.npmjs.com/package/celebrate) for Joi-based request validation.
- [cors](https://www.npmjs.com/package/cors) to enable Cross-Origin Resource Sharing.
- [express](https://www.npmjs.com/package/express) as the backend framework.
- [joi](https://www.npmjs.com/package/joi) for data schema validation.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) for generating and verifying JWT tokens.
- [knex](https://www.npmjs.com/package/knex) for SQL query building and migrations.
- [mysql2](https://www.npmjs.com/package/mysql2) to connect to MySQL databases.
- [pino](https://www.npmjs.com/package/pino) for fast logging.

## Backend Dependency Installation
To install all frontend dependencies, run the following command:

```bash
cd frontend && npm install && cd ..
```

## Backend Dependency Installation
To install all backend dependencies, run the following command:

```bash
cd backend && npm install && cd ..
```

## Run the application
To get started with docker-compose, you must execute:

```bash
docker-compose build 
```

To start the application, the url the frontend should be http://localhost:800., run the following command:

```bash
docker-compose up
```

## Run automated unit and integration tests
To run all automated unit and integration tests, run the following command:

```bash
- email: test@email.com
- password: Password123#
```

## Run automated unit and integration tests
To run all automated unit and integration tests, run the following command:

```bash
npm run coverage
```

## Frontend Environment Variables
The following frontend environment variables are required to run the application:

- `REACT_APP_API_BASE_URL`: The base URL for API calls.
- `REACT_APP_IMAGE_BASE_URL`: The base URL for all image.

To set these variables, create a `.env` file in the root of your project and add the following line:

```plaintext
REACT_APP_API_BASE_URL=
REACT_APP_IMAGE_BASE_URL=
```

## Backend Environment Variables
The following frontend environment variables are required to run the application:

- `SERVICE`: The name of the service.
- `PORT`: The port the service will run on.
- `NODE_ENV`: The environment (development, production, etc.).
- `SALT_ROUND`: The number of rounds for password hashing.
- `JWT_SECRET_KEY`: Secret key for signing JWT tokens.
- `JWT_EXPIRY_TIME`: Expiration time for JWT tokens.
- `JWT_ISSUER`: The issuer of the JWT token.
- `DATABASE_NAME`: The name of the database.
- `DATABASE_HOST`: The host address of the database.
- `DATABASE_USER`: The username for the database.
- `DATABASE_PASSWORD`: The password for the database.
- `DATABASE_PORT`: The port number for the database.
- `DATABASE_TIMEZONE`: The timezone for the database.

To set these variables, create a `.env` file in the root of your project and add the following line:

```plaintext
SERVICE=
PORT=
NODE_ENV=
SALT_ROUND=
JWT_SECRET_KEY=
JWT_EXPIRY_TIME=
JWT_ISSUER=
DATABASE_NAME=
DATABASE_HOST=
DATABASE_USER=
DATABASE_PASSWORD=
DATABASE_PORT=
DATABASE_TIMEZONE=
```

## Screenshots

**Desktop view**
![](grid-desktop.png)

**Mobile view**
![](grid-mobile.png)

**Desktop view**
![](login.png)

**Mobile view**
![](sign-up.png)

