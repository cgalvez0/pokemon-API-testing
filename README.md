# Pokemon Back-end Automation Testing
Back-end Automation Challenge

## Introduction

The purpose of this challenge is aimed to make the mentee to experiment a role play making a proposal with the client on a backend testing architecture, explaining What and Why was it designed that way.

# Pokemon Back-End

## Tech Stack

* [Postman](https://www.postman.com/) - An API platform for building and using APIs.
* [Newman](https://www.npmjs.com/package/newman) - A command-line Collection Runner for Postman. 
* [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra) - A Newman HTML reporter.

## Project structure
```
.
├──
├──pokemon-API-testing
│    ├── pokemon_backend_testing		# API testing collection and environment variables are here.
│    │	  ├── collection
│    │    │   └── pokemonAPI.postman_collection.json
│    │    └── envVariables
│    │        └── pokemonAPI.postman_environment.json  
│    ├── package-lock.json      
│    ├── package.json      
│    ├── README.md
```

## Pre-requisites

* NodeJS (Latest version or up to 12.22.0)
* npm
* Git

## Installation

Clone this repository.
```
git clone https://github.com/wizeline/qa-buddy-program-cinthia-galvez
```
Go to the repository folder and once inside open a new terminal and type:
```
sudo npm install
sudo npm i newman -g
```
That last command line will install newman globally. Now let's install the reporter. Type in the terminal:
```
sudo npm i newman-reporter-htmlextra
```
Now you are ready to have fun.

## Execution 

In the root of the project, run in the terminal:
```
npm run pokemonAPI
```
This command will initialize all the API tests requested, and will create a pokemon_backend_report.html in the report folder, inside the pokemon_backend_testing folder. To visualize the report just open the html file on chrome and enjoy!

** This project was developed on MacOS Monterrey 12.5.1
