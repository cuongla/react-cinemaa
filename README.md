# React-Cinemaa

An online database of information related to films, television programs, home videos, video games, and streaming content online. A clone of IMDb

## Installation

`$ git clone https://github.com/tinla94/react-cinemaa` or click `Clone or download`.

### Code Folder

1. Install node packages: `npm install`
2. Start up browser to see UI: `npm start`.
3. Electron will load its own window

## Technology Use

### Front-End

1. `React` - an open-source JavaScript library which is used for building user interfaces specifically for single page applications

2. `React Hooks` - functions that let us hook into the React state and lifecycle features from function components

3. `SCSS` ( Syntactically Awesome Style Sheet ) - superset of CSS.

4. `Prop-types` - runtime type checking for React props and similar objects.

### Other Tools

1. `TMDb API` - a popular, user editable database for movies and TV shows.

2. `ESLint` - A pluggable and configurable linter tool for identifying and reporting on patterns in JavaScript. Maintain your code quality with ease.

3. `prettier` -  an opinionated code formatter;

## Setup for build

1. Setup eslint & prettier

You can check .eslintrc.json and .prettier.json for more information.

```
    "lint": "eslint 'src/**/*.js*'"
    "prettier:check": "prettier --check 'src/**/*.{js,jsx,json}'"
    "prettier:write": "prettier --write 'src/**/*.{js,jsx,json}'"
```

#### eslintrc.json

```
{
    "env": {
        "browser": true,
        "es6": true
    },
    "extends": [
        "plugin:react/recommended",
        "standard"
    ],
    "globals": {
        "Atomics": "readonly",
        "SharedArrayBuffer": "readonly"
    },
    "parserOptions": {
        "ecmaFeatures": {
            "jsx": true
        },
        "ecmaVersion": 2018,
        "sourceType": "module"
    },
    "settings": {
      "react": {
        "version": "16.0"
      }
    },
    "plugins": [
        "react"
    ],
    "rules": {
        "semi": [2, "always"],
        "space-before-function-paren": [0, {"anonymous": "always", "named": "always"}],
        "camelcase": 0,
        "no-return-assign": 0
    }
}
```

#### prettierrc.json

```
{
  "trailingComma": "none",
  "tabWidth": 2,
  "semi": true,
  "singleQuote": true
}
```


## Deployment

You can use any Cloud Server to deploy your application.

In this project, I have used `Netlify` service to deploy my application.

### Who is Netlify?

`Netlify` a web developer platform that multiplies productivity. By unifying the elements of the modern decoupled web, from local development to advanced edge logic, `Netlify` enables a 10x faster path to much more performant, secure, and scalable websites and apps.

You can learn more about how to deploy your app with `Netlify` here: https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/

## Authors

- **Tin La**

## Tutorial 

https://www.udemy.com/course/build-a-modern-react-and-redux-app-with-circleci-cicd-aws/