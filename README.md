# Symmetrical Disco - Angular SSR Project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 20.3.3 and includes Server-Side Rendering (SSR) support.

## Features

- **Angular 20.3.0** - Latest version of Angular framework
- **Server-Side Rendering (SSR)** - Using Angular SSR for improved performance and SEO
- **Express Server** - Node.js server for serving the SSR application
- **TypeScript** - Full TypeScript support
- **Routing** - Angular Router configured
- **Testing** - Jasmine and Karma testing setup
- **CSS Styling** - CSS support configured

## Development Server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Server-Side Rendering

### Development SSR
For SSR development, use the regular development server which includes SSR support:
```bash
npm start
```

### Production SSR
To build and serve the SSR version:
```bash
npm run build
npm run serve:ssr
```

The SSR server will be available at `http://localhost:4000`.

## Running Tests

Run `npm test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Code Scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Further Help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
