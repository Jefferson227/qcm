# QCM
QCM means Questionnaires à Choix Multiple (English: Multiple Choice Questionnaires). This project is about creating an application for parents to make their children work based on questions/answers. What i want to do is exercices that can be modified easily by the parents (json files ?). Next steps will be to add a database, and parents will be able to submit their exercices.

## Features

* Expres
* JADE
* MVC
* Stylesheets can be CSS, Grid, Flex, bootstrap.
* Embedded resources like images or fonts use DataUrls if appropriate

## Local Installation

Install [node.js](https://nodejs.org)

``` text
npm install
```

## Development server

``` text
# Start the application
node bin/www

# open this url in your browser if it doesn't open automatically
http://localhost:3000/
```

## Project structure

```
*qcm*
├───*bin*
│   └────*www* Main entry point via nodejs `node www will make the app live on localhost:PORTNUMBER 
│
├───*public*
│   └───*stylesheets*
│       └────*style.css* Styling
│
├───*routes*
│   └────*index.js* File with all the routes
│
├───*views* Views
│   └────*error.jade* Error page
│   └────*index.jade* Index page
│   └────*layout.jade* Layout page
├───*app.js* Main file for import libraries and stuff
├───*LICENSE*
├───*package.json* the whole package.json with every dependency and script, nothing is kept hidden
└───*README.md* this file

```

## Contribution
Feel free to contribute.