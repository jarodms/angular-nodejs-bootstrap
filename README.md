# Fully contained 'db', server and app
This is not meant to be a full. amazing, awesome app....just an example.

## Get Started
After cloning/downloading source, run:

`npm install`


Run all three (DB, NodeJS server, and App) to have a fully contained and running app.

`npm run start-dev`

### Goto http://localhost:4200/ to view the running app. 
1) Add a ToDo item with a description
2) ToDo's not complete are marked as Green
3) ToDo's that are complete have a grey background 
4) Delete any ToDo you don't need any more
5) ToDo's are saved in the `db.json` file, so restarting the app will load your previous ToDo's

# The Pieces
## DB
`npm run db`

The 'DB' is a JSON file named `db.json`. Data is retrieved and stored in this file. View the JSON server and it's data at `http://localhost:3000/` 

## NodeJS server
`npm run server`

The file `server.js` is our Node server for our REST API. The web services (used within the Angular app) are located at `http://localhost:8000/api`


## Angular app
start the Angular app with `npm serve`

Start the Angular app and goto `http://localhost:4200/`




############################################################
# AngularNodejsBootstrap

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
