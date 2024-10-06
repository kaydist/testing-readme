# Books You Might Like

This project implements a grid component that displays books a user might enjoy, using React JS, SCSS Modules, and state management with Redux.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Running Tests](#running-tests)
- [Video Recording](#video-recording)
- [Screenshots](#screenshots)

## Description
The "Books You Might Like" grid component is designed to show a collection of recommended books based on user preferences. The frontend is built with React JS, styled using SCSS Modules, and Redux for state management. Axios is used to fetch data from the API, and Formik with Yup manages form validation.

## Features
- Dynamic book grid layout
- Responsive design with SCSS Modules
- Form management using Formik and Yup for validation
- API calls managed with Axios
- Global state management using Redux
- Unit testing with Jest

## Environment Variables
The following environment variables are required to run the application:

- `REACT_APP_BASE_URL`: The base URL for API calls.
- `REACT_APP_IMAGE_BASE_URL`: The base URL for all image.

To set these variables, create a `.env` file in the root of your project and add the following line:

```plaintext
REACT_APP_BASE_URL=
REACT_APP_IMAGE_BASE_URL=

## Installation
To install dependencies, run the following command:

```bash
yarn install

## Run the application
To start the application, run the following command:

```bash
yarn start

## Run automated unit and integration tests
To run all automated unit and integration tests, run the following command:

```bash
yarn test

