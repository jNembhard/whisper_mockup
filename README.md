# Secrets Authentication

## _A Whisper Inspired Mockup_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Requirements (Local Use)

- MongoDB
- Node.js
- Nodemon (optional)

## Purpose

This web application is intended for use by participants looking to share their secrets anonymously.

Users can create a username and password locally, or register with the site using their Gmail or Facebook login details. Please click the link to view the [whisper-secrets](https://whisper-secrets.herokuapp.com/) website.

## Setup

For local use, download the files and navigate into the Secrets Authentication folder and run the following command:

```
npm install
```

You will need to edit the code to test locally. In line 36 of app.js:

```js
mongoose.connect(URI, connectionParams);
```

```js
mongoose.connect(URL, connectionParams);
```

You can then run either of the following:

```
node app.js
nodemon app.js
```

## Demonstration

Below is a basic demo useful for navigationg the website.

## Dependencies

| Project               | Home Page                                                        |
| --------------------- | ---------------------------------------------------------------- |
| Express               | <https://expressjs.com/>                                         |
| Mongoose              | <https://mongoosejs.com/>                                        |
| Mongoose-Encryption   | <https://www.npmjs.com/package/mongoose-encryption/>             |
| Mongoose-Findorcreate | <https://www.npmjs.com/package/mongoose-findorcreate/>           |
| Passport              | <https://www.passportjs.org/>                                    |
| ssl-express-www       | <https://www.npmjs.com/package/ssl-express-www?activeTab=readme> |
| woke-dyno             | <https://github.com/fermentationist/wokeDyno/>                   |
