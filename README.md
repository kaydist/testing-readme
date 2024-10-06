# Perlego Assessment

This project implements a grid component that displays books a user might enjoy, using React JS, SCSS Modules, and state management with Redux.

## Table of Contents
- [Description](#description)
- [Base dependencies](#base-dependencies)
- [Installation](#installation)
- [Running the application](#run-the-application)
- [Running the automated tests](#run-automated-unit-and-integration-tests)
- [Video Recording](#video-recording)
- [Screenshots](#screenshots)

## Description
The "Books You Might Like" grid component is designed to show a collection of recommended books based on user preferences. The frontend is built with React JS, styled using SCSS Modules, and Redux for state management. Axios is used to fetch data from the API, and Formik with Yup manages form validation.

## Base dependencies

- [axios](https://github.com/axios/axios 'Axios') for networking.
- [scss modules](https://sass-lang.com/) to manage styling.
- [react-router-dom](https://reactrouter.com/en/main 'React Navigation') navigation library.
- [formik](https://formik.org/docs/overview) to manage forms.
- [redux](https://redux.js.org/ 'Redux') for state management.
- [redux-persist](https://github.com/rt2zz/redux-persist 'Redux Persist') as persistance layer.
- [redux-toolkit](https://github.com/gaearon/redux-thunk 'Redux Toolkit') to dispatch asynchronous actions.

## Installation
To install dependencies, run the following command:

```bash
yarn install
```

## Run the application
To start the application, run the following command:

```bash
yarn start
```

## Run automated unit and integration tests
To run all automated unit and integration tests, run the following command:

```bash
yarn test
```

## Environment Variables
The following environment variables are required to run the application:

- `REACT_APP_BASE_URL`: The base URL for API calls.
- `REACT_APP_IMAGE_BASE_URL`: The base URL for all image.

To set these variables, create a `.env` file in the root of your project and add the following line:

```plaintext
REACT_APP_BASE_URL=
REACT_APP_IMAGE_BASE_URL=
```

