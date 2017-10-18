# Node.js Passport Password Reset Example

This is a working node.js app that implements sign up, login, logoff, and password reset via email.

This is code described in the blog post
[How To Implement Password Reset In Node.js by Sahat Yalkabov](http://sahatyalkabov.com/how-to-implement-password-reset-in-nodejs/)

* This is not my creation. Credit should go to Sahat Yalkabov for creating an excellent tutorial.


## Prerequisites

* [MongoDB](https://www.mongodb.com/download-center)

## Instructions (for *nix)

1. git clone git@github.com:tonydiep/nodejs-passport-password-reset.git
2. cd nodejs-passport-password-reset
3. npm install
4. cp env.example.sh env.sh
5. edit env.sh
6. start mongo
7. npm start

## Changes from the blog

* I have followed the blog post and used current (Oct 2017) versions of libraries
* The code has been updated to fix syntax errors due to changes in libraries
* Library versions have been explicitly set to prevent similar syntax errors in the future due to library changes
