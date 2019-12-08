### ANGULAR
The first version was AngularJS. Javascript framework was created by Google in 2009.
### NEXT ANGULAR VERSION WAS:
##### Angular2
Angular 2.0 was announced at the ng-Europe conference 22–23. October 2014.
##### Angular4
On 13 December 2016 Angular 4 was announced, skipping 3 to avoid a confusion due to the misalignment of the router package's version which was already distributed as v3.3.0. The final version was released on March 23, 2017. Angular 4 is backward compatible with Angular 2.
##### Angular5
Angular 5 was released on November 1, 2017. Key improvements in Angular 5 include support for progressive web apps, a build optimizer and improvements related to Material Design.
##### Angular6
Angular 6 was released on May 4, 2018.
##### Angular7
Angular 7 was released on October 18, 2018.
##### Angular8 
Angular 8 was released on May 28, 2019. Featuring Differential loading for all application code, Dynamic imports for lazy routes, Web workers and TypeScript 3.4 support.
### NAMING
Originally, the rewrite of AngularJS was called "Angular 2" by the team, but this led to confusion among developers. To clarify, the team announced that separate terms should be used for each framework with "AngularJS" referring to the 1.X versions and "Angular" without the "JS" referring to versions 2 and up.
### DIFFERENCES BETWEEN ANGULAR AND ANGULARJS:
- Angular was designed as a ground-up rewrite of AngularJS;
- Angular does not have a concept of "scope" or controllers, instead it uses a hierarchy of components as its primary architectural characteristic;
- Angular has a different expression syntax, focusing on "[ ]" for property binding, and "( )" for event binding.
Modularity – much core functionality has moved to modules;
- Angular recommends the use of Microsoft's TypeScript language, which introduces the following features:
    - Static Typing;
    - including Generics Annotations;
- TypeScript is a superset of ECMAScript 6 (ES6), and is backwards compatible with ECMAScript 5 (i.e.: JavaScript);
- Dynamic loading;
- Asynchronous template compilations;
- Iterative callbacks provided by RxJS. RxJS limits state visibility and debugging, but these can be solved with reactive add-ons like ngReact or ngrx;
- Support for Angular Universal, which runs Angular applications on servers.
### WHAT IS THE MEANING OF SPA AND ITS APPLICATION
Single Page Application (SPA or single-page application) implements user-friendly, interactive services. The simplest example is Gmail.
Are you interested in what resources Angular has implemented? On the Made with Angular site you will find a list listing sites created using different versions of the framework.
SPA is a web application hosted on a single physical HTML page. This page loads all necessary resources (JavaScript, CSS, images, etc.) once and no longer reloads. Links to links do not actually reload the page, and its content changes on the fly, that is, dynamically. If necessary, a request is made to the server to receive the data, and after receiving it, the content of the "new" page is generated. Each individual virtual page is registered in a router. In our application there are two routes: home and chat.
### MAIN POINTS OF ANGULAR ARCHITECTURE:
#### MODULE
-structural units of application that encapsulate a certain logic. In Angular, these are structures that store certain components, directives, and services that are combined with a certain logic. An example would be a user profile, a module for writing a letter, an overview of a list of letters, and more.
#### COMPONENT
-typescript class that stores data and logic for displaying this data in a template. The template is closely related to the component. Component data can be easily displayed in a template using a special syntax. The component can also "capture" data from the template and retrieve it directly in the script.
#### TEMPLATE
-HTML code snippet with custom syntax added. It allows you to embed data from a component into the template without using innerHTML and similar methods. The template is specified in the component and is part of its configuration.
#### SERVICE
-in Angular is a typescript class that performs tasks related to retrieving, storing, and processing data. For example, logging, converting data for later transfer to a component, accessing the backend, and more. Unlike components and directives, services do not work with views (templates) directly.
TASKS OF SERVICES:
- Provide application data. The service itself may store the data in memory or, to retrieve the data, access a data source, such as a server;

- The service can encapsulate business logic, various computing tasks, logging tasks that are better off taking components out. This way, the component code will be focused directly on the presentation. In addition, we can solve the problem of code repetition if we need to perform the same task in different components and classes.
#### ROUTER
-is a router that is designed to switch between screens to display different content.
In other words, when you change the URL snippet in the browser's address bar, the router monitors these changes and downloads one or the other part of the application.
#### PIPE
-a pipe takes in data as input and transforms it to a desired output.
#### DIRECTIVE
-allow direct access to the DOM of your elements.
