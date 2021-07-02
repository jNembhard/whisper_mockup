# Secrets Authentication

## _A Whisper Inspired Mockup_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Requirements (Local Use)

- MongoDB
- Node.js
- Nodemon (optional)

## Purpose

This web application is intended for use by people looking to share their secrets anonymously.

Users can create a username and password locally, or register with the site using their Gmail or Facebook login details. Please click the link to view the [whisper-secrets](https://whisper-secrets.herokuapp.com/) website.

## How to Use the Application

1. First click "Register" to create an account.
2. Choose to register your account by creating an username (email address) and password. You can also sign up with your Google or Facebook credentials.
3. Once logged in, you will be brought to a page to view each anonymous secret.
4. You may either click the "Log Out" button to logout, or click the "Submit a Secret" button to submit your own secret.
5. Type your secret and click the "Submit" button.
6. If you have logged out and already have an account, you may click the "Login" on the home page to enter your login credentials.

## Demonstration

Below is a basic demo useful for navigating the website.

![Whisper_Mockup](/public/css/images/secrets_authentication.gif)

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
