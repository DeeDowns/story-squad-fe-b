# Story Squad Team B

[![Maintainability](https://api.codeclimate.com/v1/badges/0a3a11c6f1e83568a5cf/maintainability)](https://codeclimate.com/github/Lambda-School-Labs/Labs26-StorySquad-FE-TeamB/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/0a3a11c6f1e83568a5cf/test_coverage)](https://codeclimate.com/github/Lambda-School-Labs/Labs26-StorySquad-FE-TeamB/test_coverage)

[<img src="https://avatars2.githubusercontent.com/t/4044276?s=280&v=4" width="200" />](https://avatars2.githubusercontent.com/t/4044276?s=280&v=4)


## Current State Of The App

see the latest work done on the app here: [Click Here](https://docs.google.com/spreadsheets/d/1ZdhfQEAsz3IhgVa8zMZ0JkuD6-oasDI4hplPFXZaXNQ/edit?usp=sharing)

## Project Overview
[Product Roadmap](https://www.notion.so/Story-Squad-Roadmap-2682f21ae48b420cbb0caafa3f500b5e)
<br>
[UX Design](https://www.figma.com/file/WaHXdLK2NASoFWYVMZLVNt/Story_Squad?node-id=962%3A211)
<br>
[Architecture Layout](https://whimsical.com/428nXLpzshbbb32xF67Lu4)
<br>

---

Welcome to Story Squad! We are an interactive learning platform targeted at grade school children, and we help build reading comprehension as well as artistic, writing, and analytical/critical thinking skills through weekly competitions.

Each week features a new chapter in an exciting novel, written and serialized specifically for Story Squad by author and educator Graig Peterson. Children are provided with prompts based on the chapter they've just read, and participants are then divided into teams of two. Students create art and fanfiction to match the prompt, before going head to head in a bracket-style tournament.

In addition to growing their literary and artistic skills, students learn team building and critical thinking skills through a unique voting system, where each child must weight their own work against their teammate in order to increase their odds of winning. Badges and points incentivize winning and encourage participation.

Story Squad is a paid service; parents are required to create the account for their children and pay a monthly subscription fee in order for their children to compete. This brings the platform into compliance with COPPA and ensures a long future for the project.

### Key Features

- A Custom, Serialized Novel geared toward children in 3rd-6th grade
- Parental Controls which allow parents to add and customize child accounts

<br>

## Tech Stack

### Front end built using:

React

- First Class Performance with Virtual DOM
- Lightweight Library resulting in low bundle size/improved load times
- Easy cross-platform development via progressive web app
- Simple routing
  <br>

Ant Design

- A set of high-quality React components out of the box
- Powerful theme customization
- Whole package of design resources and development tools

React Plotly

- Easy to use to embed D3 charts
- This React component takes the chart type, data and styling as Plotyly.JSON in its data and layout props, then draws the chart using Plotly.js.

Redux state management

- Redux helps you write applications that behave consistently,
- Centrilize your application's state and logic
- The Redux DevTools make it easy to trace bugs

### [Backend](https://github.com/Lambda-School-Labs/story-squad-be-b.git) built using:

Express

- Built in routing and middleware
- Useful add-ons such as helmet and CORS

Swagger Editor Documentation

- Defines and documents RESTful APIs

## API's

### JWT & BCrypt

JSON Web Tokens are an industry standard authentication solution. Paired with BCrypt for hashing passwords, this allows secure local password authentication without reliance on third party solutions.

### Environment Variables

In order for the app to function correctly, the user must set up their own environment variables. There should be a .env file containing the following:

```
*  BROWSER=none
*  REACT_APP_ENDPOINT=http://localhost:3000
```

## Testing

Jest

- Simple testing
- Mocking of dependencies
- Promotes consistent unit testing

## Installation Instructions

Clone repo

```
git clone https://github.com/Lambda-School-Labs/story-squad-fe-b.git

cd story-squad-fe-b/
```

Install Dependencies

```
npm install
```

Run Test

```
npm test
```

Clone and download the [backend](https://github.com/Lambda-School-Labs/story-squad-be-b.git)

Follow backend [set up guides](https://github.com/Lambda-School-Labs/story-squad-be-b.git)
<br>
<br>
Run the application locally

```
npm dev
```

## Other Scripts

```
* build - creates a build of the application
* dev - runs the development server
* test - runs tests as defined in *.spec.ts files
* lint - format and correct errors with prettier
```

<br>

![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)
![React](https://img.shields.io/badge/react-v16.7.0--alpha.2-blue.svg)
![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)


