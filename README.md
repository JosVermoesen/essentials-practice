# EssentialsPractice

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.0.6.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Updating to latest Angular 18

This app is now on Angular 18.

### update app to latest Angular 18

`ng update @angular/cli@18 @angular/core@18`

### update from older Angular versions to the latest

Follow the instructions in the [Angular Update Guide](https://update.angular.io/) to fix your app.

Please note that then the --force flag is mostly required to be sure that the update command runs even if there are dependency conflicts for thirth party libraries.

### standalone components

You can switch older Angular programs to standalone with `ng generate @angular/core:standalone`

#### npm outdated

In terminal use `npm outdated` to see what packages are requiring updates and what their current and wanted versions are.

This will also show you which packages are deprecated.

If you want to update a package to a version newer than what is specified in your package.json, you can do so by running npm update [package-name]@[version-number].

### vulnerabilities

In terminal use `npm audit fix` to automatically install compatible updates to vulnerable dependencies.

You can first run `npm audit` to see vulnerabilities in your project for one or more packages.

Run `npm ls [package-name]` to see which packages depend on the vulnerable package.
