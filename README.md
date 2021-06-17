# React Boilerplate

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
This is an opinionated version of CRA. This repository is a vanilla boilerplate for future React projects to reduce the time setting up the opinionated packages used for this project.

## Opinionated packages

### SASS

<h1><img width="200px" alt="Sass" src="https://rawgit.com/sass/sass-site/master/source/assets/img/logos/logo.svg" /></h1>
I prefer to use SASS for its styling sheet flexibility: nesting rules, variables, mixins, selector inheritance, etc.

### Jest and Enzyme

Over other testing suites like Mocha/Chai, Jest has the most seamless integration to React projects and require less set up. There are pros and cons to each tool, but Jest seems to be the simplest and easiest to use.

### ESLint

ESLint was a seamless integration to the React workflow. This helps standardize across the board for all future React projects to have the same styling and help with any syntax issues.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run lint`

Automatically runs `eslint` to fix any syntax issues and to tidy up the code.
