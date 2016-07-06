TODO: Update this file with relevant information.

**FYI** this is just a template :P

## Synopsis

At the top of the file there should be a short introduction and/ or overview that explains **what** the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

**Have an instance of mongodb running**

git clone git@github.com:Andhu/NodeServerStarter.git {what you wanna name the project}
for example

**In Teminal**

git clone git@github.com:Andhu/NodeServerStarter.git server

cd server

npm install

**After that you will need to create a config.js file in the root directory**

insert the following content in it

module.exports = {
  secret: 'yourSecretKey'
};

**Back in the terminal**

npm run dev

**Voila**

**Usage guide coming soon**


## API Reference

post an email and password in a json format. to the signup route. 

sign in using those credentials..

enter the root route with the provided token in the requests 'authorization' header.

routes:

localhost:3090/  // Requires for you to be authenticated.

localhost:3090/signup

localhost:3090/signin

**i really should have called it register & log in /fail** 

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

This server is available under the MIT license.
