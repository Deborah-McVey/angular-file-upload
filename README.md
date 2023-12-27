# AngularFileUpload

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.8.

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

To be read..., tutorial from: https://www.bezkoder.com/angular-16-file-upload/ from December 26, 2023. Technology: Angular 17 RxJS 7 Bootstrap 4 ,  
angular 17 globally installed in cmd, project set up in VS Code, VS terminal: cd to folder on my computer create project, cli commands: ng new angular-file-upload --no-standalone --no-strict --style=css --routing=false , Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? No, open folder, see: no app.routes.ts, no app.config.ts, no app.config.server.ts , open new terminal, Bootstrap framework: npm i bootstrap@4.6.2 , angular.json path in styles above styles/css put "../node_modules/bootstrap/dist/css/bootstrap.min.css", , 
add components and services with --skip-tests, 
– file-upload.service provides methods to save File and get Files from Rest API Server using HttpClient.
– file-upload.component contains upload form, progress bar, display of list files.
– app.component is the container that we embed all components.
– styles.css for importing the Bootstrap library.
app.module.ts: import HttpClientModule,
file-upload.service.ts,
file-upload.component.ts: import fileuploadcomponent,
file-upload.component.html,
app.component.html,
app.component.ts
https://github.com/bezkoder/angular-17-file-upload/blob/master/src/app/components/file-upload/file-upload.component.ts (do not copy all from this, it's not the same)
added components and imported commonmodule, 
app.module.ts changed fileupload component from declarations to import to de-bug,
