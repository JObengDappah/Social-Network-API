# Social-Network-API

## Table of Contents

  [Description](#description)
  [Acceptance Requirement](#acceptance requirement)
  [Installation Instructions](#installation-instructions)
  [Testing Instructions](#testing-instructions)
  [Questions](#questions)

## Description

  This project serves as the backend API for a social networking platform. It utilizes MongoDB to define models for users and their shared thoughts. Through this API, users can be created, share and react to thoughts, as well as add or remove friends. The project is built using Express for routing, MongoDB for database management, Mongoose ODM for data modeling, and is developed with Node.js and JavaScript.

## Acceptance Requirement

* GIVEN a social network API
* WHEN I enter the command to invoke the application
* THEN my server is started and the Mongoose models are synced to the MongoDB database
* WHEN I open API GET routes in Insomnia for users and thoughts
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia
* THEN I am able to successfully create, update, and delete users and thoughts in my database
* WHEN I test API POST and DELETE routes in Insomnia
* THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
Mock-Up

## Installation Instructions

* To use this API on your local machine.
  
* clone this repository and ensure that node.js is installed.

* Run npm i in the command line and npm start to start the server.

* Optionally, run npm run seed to seed some sample data for testing purposes.
  
## Testing Instructions

  A video demo of the routes being tested can be found [here.] (<https://drive.google.com/file/d/1MW6hjQu8fbDzbPfaS3HzIbTk7IPs98SX/view?usp=drive_link>)

## Questions

  Please direct questions to [github.com/JObengDappah](github.com/jObengDappah) at [jacmo074@gmail.com](jacmo074@gmail.com).
