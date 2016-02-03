# sailsSimpleAuth

In future updates this sails application will include an authentication based on
passport.js. The idea is to use this backend with an emberjs frontend and connect
the authentication.

The goal of this repo is to help to understand how authentication can be handled
in the backend and let the login and registration tasks to the frontend.


## Intro

Passport authentication is based on this tutorial:

* [Sails.js: User authentication](http://miscposts1.blogspot.com.es/2014/09/sailsjs-user-authentication.html)

Instal the following dependencies:

* `npm install bcrypt-nodejs --save`
* `npm install passport --save`
* `npm install passport-local --save`

The reason for using bcrypt-nodejs instead of bcrypt is that gives less Installation
problems. The usage is basically the same.
