# Angular Quick Start - Completed Project (Unofficial)

This is a working project following completion of the quick start tutorial at https://angular.io/start, with some minor modifications.

### Modifications

- This project is set up with `"strict": true` in `tsconfig.json` as that is how I intended to build further projects using Angular. Some further modifications were made as a result, such as specifying the `any` type where it would otherwise have been implicit.
- A new application was created with more recent versions of Angular and TypeScript based on the standard `ng new` template: https://angular.io/guide/setup-local
- The project has been configured with routing included during project scaffolding.
- Less CSS preprocessing was selected during project scaffolding and a simple settings file has been added.  
- Some minor troubleshooting was completed where it had not been fully clear (to me at least) what needed importing for [allowing a formGroup attribute](https://stackoverflow.com/questions/39152071/cant-bind-to-formgroup-since-it-isnt-a-known-property-of-form) in the 'Using Forms for User Input' section.

### To Run:

```
$ npm install
$ ng serve
```

Browse to http://localhost:4200 to the running project. See below for further options.

---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.3.

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
