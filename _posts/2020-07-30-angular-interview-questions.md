---
layout: post
title:  "Angular Interview Questions"
categories: [ Angular, JavaScript, TypeScript ]
image: assets/images/14.jpg
---
You will find this post to be resourceful for the interview preparation.


##### What is Angular ?
* Angular is a platform and framework for building client side web applications that are cross platform.

##### Why Angular ?
* Component based architecture
* Single page applications
* Platform agnostic
* High performance – angular-cli, dependency injection, end-to-end tooling, declarative templates and   integrated best practices
* Cleanly separate the UI and business logic
* Creating modern-looking UIs using the Angular Material library
* Scalable, reusable and maintainable JS code
* Test driven development 

##### What are the new features of angular ?
###### Angular 2(2016) :
* Five times Faster than angularjs
* It widely support for TypeScript and ES6
* Component based architecture
* Data Binding
* Server side rendering
* SPA

###### Angular 4(end of 2016) :
* HttpClient - used for Rest web services, it uses browser’s XMLHttpRequest object
* Improved ngIf and ngFor
* Backward compatible
* AOT
* Animation module is separated from Angular/core
* New router life cycle events for Guards and Resolvers.
* Conditionally disable animations via a new attribute, [@.disabled]

###### Angular 5 :
* Angular Material & CDK Stable Release
* Service Worker support in the CLI
* Improved Universal & AppShell Support in the CLI
* Improved decorator error messages
* Improved Type Checking for templates
* Improved router param and data inheritance
* TypeScript 2.6 support

###### Angular 6 :
* Router Scroll Position Restoration
* Shadow DOM v1 View Encapsulation
* Schematics Chaining
* TypeScript 2.9
* HttpModule -> HttpClientModule
* ng update <package> is a new CLI command that analyzes your package.json and recommends updates to your application.
* Angular 6 uses angular.json instead of angular-cli.json.
* Minor changes in imports such as import {Observable} from 'rxjs/Observable' to import {Observable} from 'rxjs' .

###### Angular 7 :
* CLI Prompts
* Application performance
* Angular material & CDK
* Angular Elements
* Dependency updates

###### Angular 8:
* Differential loading-  Angular CLI to create two different production bundles of your app.
* New lazy loading syntax
* Create web workers with cli
* New guide for old features

##### What is Typescript ?
* Superset of JavaScript, compiles to JavaScript, uses types, classes, async/await
* TypeScript follows the latest ECMAScript specifications
* TypeScript interfaces allow you to declare custom types. Interfaces help prevent compile-time errors caused by using objects of the wrong type in your application.

##### What are web workers ?
* Web Workers are a simple means for web content to run scripts in background threads.
* Web Workers allow you to run CPU intensive computations in a background thread, freeing the main thread to update the user interface.

##### What are basic building blocks of angular (or) angular architecture ?
* NgModules - provides compilation context for components and collect related code into functional sets
* An angular app is defined by a set of NgModules
* An app always has at least a root module that enables bootstrapping, and typically has many more feature modules.
* An Angular module is a container for a group of related components, services, directives, and pipes.

##### What are the Key Components of angular ?
* *Component*: These are the basic building blocks of angular application to control HTML views.
* *Modules*: An angular module is set of angular basic building blocks like component, directives, services etc. An application is divided into logical pieces and each piece of code is called as "module" which perform a single task.
* *Templates*: This represent the views of an Angular application.
* *Services*: It is used to create components which can be shared across the entire application.
* *Metadata*: This can be used to add more data to an Angular class.

##### What are decorators ?
Decorators are functions that mark the classes and provides metadata that tells angular how to use them.

##### What is Angular CLI ?
* Command Line Interface helps to speed up development process and perform following tasks
  * Bootstrapping your application
  * Serving your application
  * Running tests(Both unit & end-to-end)
  * Creating a build for distribution
  * Generating components, services, routes and more for your application

##### Name some angular-cli commands 
* ng new
* ng generate
* ng serve
* ng test
* ng update
* ng build
* ng version
* ng g c— Generates a new component.
* ng g s— Generates a new service.
* ng g d— Generates a new directive.
* ng g m— Generates a new module.
* ng g application— Generates a new app within the same project. This command was introduced in Angular 6.
* ng g library— Starting with Angular 6, you can generate a library project.

##### Describe structure of angular application ?
* *Root Component* : app.component.ts
* *Main module* : app.module.ts The application module file can be thought of as the core configuration of your application, from loading all the relevant and necessary dependencies, declaring which components will be used within your application, to marking which is the main entry point component of your application
* *Root HTML* : index.html is responsible for deciding which files are to be loaded
* *Entry point* : main.ts is responsible for identifying which angular module to be loaded when application starts
* *Angular-cli config* : angular.json
 
##### What are the libraries that can be used in angular app ?
* SystemJS is a javascript library that allows us to import other libraries.
* RxJS is a set of libraries for composing asynchronous and event-based programs using observable collections. It allows applications to work with asynchronous data streams, such as a server-side stream of stock price quotes or mouse move events.

##### What is Angular Directive ?
* A directive is how we add dynamic behavior to HTML.There are three kinds of directives.They are
 * Component Directives
 * Structural  Directives- NgIf, NgFor, and NgSwitch.

Eg: 
```js
// structural directive example
import { Directive, TemplateRef, ViewContainerRef, Input } from '@angular/core';
@Directive({ selector: '[appNot]' })
export class AppNotDirective {
    constructor(private templateRef: TemplateRef<any>, 
                private ViewContainerRef: ViewContainerRef<any>) {}
@Input() set appNot(condition: boolean) {
	if (!condition) {
		this.viewContainer.createEmbeddedView(this.templateRef);
} else {
this.viewContainer.clear();  
}
}
```
* Attribute Directives -  NgStyle, NgClass

Eg:
```js
import { Directive, ElementRef, Input } from '@angular/core';

@Directive({ selector: '[myHighlight]' })
export class HighlightDirective {
    constructor(el: ElementRef) {
       el.nativeElement.style.backgroundColor = 'yellow';
    }
}

<p myHighlight>Highlight me!</p>
```
##### What is Structural directive ?
* Alters layout by adding, removing or replacing HTML elements
E.g: *ngFor - loops through an array
      *ngIf - shows content conditionally

##### What is Angular component ?
* A component is a type of directive.It is a decorator function that comprises of a template, class and metadata.

##### What are Angular modules ?
Modules are how we organize our application in angular.Every angular app must have one root module that you bootstrap to launch application.By convention, it is usually called AppModule.our main.ts is where we import our first component and bootstrap it.

##### What is Template ?
A template combines HTML with Angular markup that can modify HTML elements before they are displayed.

##### What is Angular pipe ?
A pipe that takes in data as input  and transforms it to a desired output.
E.g: lowercase,uppercase,date, number,replace,json

##### What is data binding ?
Allows you to keep a component’s properties in sync with the view. Angular updates the binding during its change detection cycle

##### What is property binding ?
Allows us to glue component properties to DOM element properties.
Eg: hidden,src,disabled,alt

##### What are Angular services ?
Services are used to organize and share code across your app, and they are usually where we create our data access methods.

##### what is dependency injection ?
* The injector is the main mechanism. Angular creates an application-wide injector for you during the bootstrap process, and additional injectors as needed. You don't have to create injectors.
* An injector creates dependencies, and maintains a container of dependency instances that it reuses if possible.
* A provider is an object that tells an injector how to obtain or create a dependency.

##### What is JIT Compilation ?
* compilation happens when the bundles arrive at browser
* Using JIT compilation in production is discouraged

##### what is AOT Compilation ?
Templates are to be precompiled into JavaScript before the bundles are created.
no need to wait for code compilation.

##### What are Life Cycle hooks available ?
After creating a component/directive by calling its constructor, Angular calls the lifecycle hook methods in the following sequence at specific moments:
* *ngOnChanges*: When the value of a data bound property changes, then this method is called.
* *ngOnInit*: This is called whenever the initialization of the directive/component after Angular first displays the data-bound properties happens.
* *ngDoCheck*: This is for the detection and to act on changes that Angular can't or won't detect on its own.
* *ngAfterContentInit*: This is called in response after Angular projects external content into the component's view.
* *ngAfterContentChecked*: This is called in response after Angular checks the content projected into the component.
* *ngAfterViewInit*: This is called in response after Angular initializes the component's views and child views.
* *ngAfterViewChecked*: This is called in response after Angular checks the component's views and child views.
* *ngOnDestroy*: This is the cleanup phase just before Angular destroys the directive/component.

