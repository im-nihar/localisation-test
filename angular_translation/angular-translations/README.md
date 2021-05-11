# AngularTranslations

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.7.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


Upload on Horeku:

npm install express  --save

npm install nodemon  --save

create server.js

package.json
    1.  "start": "nodemon server.js",

angular.json
    1. outputParth //same name as porject


For me, Check ng build
1. Build your app: ng build --prod
2. Install http-server for serving the app: npm i -g http-server
3. cd (change directory) into the the build location and run the app with: http-server
4. Open http-server url appending /index.html to it, should look something like this http://127.0.0.1:8080/index.html


//deploy on horeku
https://www.agiratech.com/blog/how-to-deploy-angular-application-to-heroku/

create a new app
git init
heroku git:remote -a angular-app-deploy  //app name

deploye using
git add .
git commit -am "initial commit deploy"
git push heroku master