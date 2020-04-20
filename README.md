# Angular & Jest Project Template


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests Jest

## Process to generate this template
* ng new t_angularjest
* npm remove karma karma-chrome-launcher karma-coverage-istanbul-reporter karma-jasmine karma-jasmine-html-reporter
* rm src/karma.conf.js src/test.ts karma.conf.js test.ts
* npm install -D jest @angular-builders/jest @types/jest
* Use the tsconfig.spec.json file here
* Update tsconfig.json file with the info here
* Update angular.json to replace the angular build karma 
* Create new file jest.config.js


