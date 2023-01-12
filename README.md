## REST API Express Server

This is our REST API for React Apps.

## First clone this REST API for React JS Apps.

```console
$ npm install
```

## Server Structure

```js
const express = require('express');
const colors = require('colors');
const dotenv = require('dotenv');


//init enviroment variable
dotenv.config();
const PORT = process.env.PORT || 8080;

//express init 
const app = express();

//express middleware 
app.use(express.json());
app.use(express.urlencoded({ extended : false }));

//listen port
app.listen(PORT, () => {
    console.log(`server is running on port ${PORT}`.bgCyan);
})


```

## packages

*Express Js
*Nodemon
*Colors
*dotenv
*multer
*nodemailer

## Live Project Link
[Edu Bord REsult](http://www.educationboardresults.gov.bd/)