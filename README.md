# AngularPOC

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Steps to run

Once downloaded extract the files into a folder.
Place folder in a location where you can remember the path.
Run CommandPrompt as an Administrator
Navigate to project folder where you have the source code.
Execute the following npm install command to install all the required npm packages.
npm install
Once all the npm packages are installed, open the project in Visual Studio Code.
Open Integrated Terminal in Visual Studio Code by clicking on "View" menu and then "Integrated Terminal"
Execute the following command to install/start JSON SERVER
npm install -g json-server
json-server --watch db.json
Now in the command prompt window or in another Visual Studio Code integrated terminal execute the following command to run the project
ng s -o
