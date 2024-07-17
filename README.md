## COMMANDS: 

- project name is `azcadea`
- `ng add @angular/localize` to install localize package.
- configuration of angular.json.
- `ng extract-i18n --output-path src/locale` to extract all the locales in source locale file.
- `ng build --localize` to generate build separate build for each locale in dist
- serve the build using `serve dist/azcadea` or `npx http-server dist/azcadea`
- run local build using `ng serve` (doesn't work as expected, problem in routing).
- to run hindi build in local, use `ng serve --configuration hi-IN`

## REFERENCES

- #### [github repo](https://github.com/PhraseApp-Blog/angular-i18n-2022)
- #### [article/blog](https://phrase.com/blog/posts/angular-localization-i18n/)

# Azcadea

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
