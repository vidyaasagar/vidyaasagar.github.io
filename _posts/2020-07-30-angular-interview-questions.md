---
layout: post
title:  "Angular Interview Questions"
categories: [ Angular, JavaScript, TypeScript ]
image: assets/images/14.jpg
---
You will find this post to be resourceful for the interview preparation.


<details>
<summary class="query-text">What is Angular ?</summary> 

Angular is a platform and Typescript based open  source framework for building client side web applications that are cross platform. Dependency injection, declarative templates, and e2e tooling are some of the key characteristics which facilitate application development.

</details>
<details class="mt-1">
<summary class="query-text">What is the primary purpose of angular ?</summary> 
To create Single page applications, angular has a collection of built-in modules to make SPA's efficient and easier.
</details>
<details class="mt-1">
<summary class="query-text">What exactly do SPA do ?</summary> 
SPA's have single entry point index.html, in which new page content is dynamically generated instead of reloading the entire web page it only updates certain parts of the page.
</details>

<details class="mt-1">
<summary class="query-text">Why Angular ?</summary> 
<ul>
<li> Component based architecture</li>
<li> Single page applications</li>
<li> Platform agnostic </li>
<li> High performance – angular-cli, dependency injection, end-to-end tooling, declarative templates and   integrated best practices </li>
<li> Cleanly separate the UI and business logic </li>
<li> Creating modern-looking UIs using the Angular Material library </li>
<li> Scalable, reusable and maintainable JS code </li>
<li> Test driven development </li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">What are the new features of angular ?</summary> 

<h6>Angular 2(2016) </h6>
<ul>
<li> Five times Faster than angularjs </li>
<li> It widely support for TypeScript and ES6</li>
<li> Component based architecture</li>
<li> Data Binding</li>
<li> Server side rendering</li>
<li> SPA</li>
</ul>

<h6> Angular 4(end of 2016):</h6>
<ul>
<li> HttpClient - used for Rest web services, it uses browser’s XMLHttpRequest object</li>
<li> Improved ngIf and ngFor</li>
<li> Backward compatible</li>
<li> AOT</li>
<li> Animation module is separated from Angular/core</li>
<li> New router life cycle events for Guards and Resolvers.</li>
<li> Conditionally disable animations via a new attribute, [@.disabled]</li>
</ul>
<h6>Angular 5 : </h6>
<ul>
<li> Angular Material & CDK Stable Release</li>
<li> Service Worker support in the CLI</li>
<li> Improved Universal & AppShell Support in the CLI</li>
<li> Improved decorator error messages</li>
<li> Improved Type Checking for templates</li>
<li> Improved router param and data inheritance</li>
<li> TypeScript 2.6 support</li>
</ul>
<h6>Angular 6 :</h6>
<ul>
<li> Router Scroll Position Restoration</li>
<li> Shadow DOM v1 View Encapsulation</li>
<li> Schematics Chaining</li>
<li> TypeScript 2.9</li>
<li> HttpModule -> HttpClientModule</li>
<li> ng update package is a new CLI command that analyzes your package.json and recommends updates to your application.</li>
<li> Angular 6 uses angular.json instead of angular-cli.json.</li>
<li> Minor changes in imports such as import {Observable} from 'rxjs/Observable' to import {Observable} from 'rxjs' .</li>
</ul>

<h6>Angular 7 :</h6>
<ul>
<li> CLI Prompts</li>
<li> Application performance</li>
<li> Angular material & CDK</li>
<li> Angular Elements</li>
<li> Dependency updates</li>
</ul>

<h6>Angular 8:</h6>
<ul>
<li> Differential loading-  Angular CLI to create two different production bundles of your app.</li>
<li> New lazy loading syntax</li>
<li> Create web workers with cli</li>
<li> New guide for old features</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">What is TypeScript ?</summary> 
<ul>
<li> Superset of JavaScript, compiles to JavaScript, uses types, classes, async/await</li>
<li> TypeScript follows the latest ECMAScript specifications</li>
<li> TypeScript interfaces allow you to declare custom types. Interfaces help prevent compile-time errors caused by using objects of the wrong type in your application.</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">What are the benefits of TypeScript ?</summary> 
<ul>
<li> Static typing</li>
<li> ECMAScript Compatibility</li>
<li> Decorators</li>
<li> Modules and Namespaces</li>
<li> Type Inference</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">What is the default module that is used to bootstrap an Angular application ?</summary> 
<ul><li>Every application developed by angular has atleast one module called as bootstrapping module and the most frequently used module is root module called AppModule.</li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What command is used to update to the latest version of Angular ?</summary>
<ul><li>You can update a project using the CLI command - <b>"ng update @angular/cli @angular/core"</b></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What are the core elements of Angular ?</summary>
<ul><li> Components, Modules, Templates, Services, Metadata and decorators</li></ul>
</details>
<details class="mt-1">
<summary class="query-text">Describe the MVVM architecture.</summary>
<ul><li>Model - Represents the data and the business logic of the application. Eg:data structures and services in angular</li>
<li>View - Represents the user interface that the user interacts with Eg: HTML template </li>
<li>ViewModel - Acts as an abstraction of the view, providing data and commands to the view Eg: component's class(Typescript file)</li></ul>
</details>
<details c lass="mt-1">
<summary class="query-text">Difference between AOT and JIT Compilation ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">How does angular gets started when you serve the application ? mention the steps</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What does angular declarable mean ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What are angular components ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What is metadata ? And types of decorator ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What do the declarations metadata of @NgModule include ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What does the import metadata of @NgModule include ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What does the providers metadata of @NgModule include ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What does the bootstrap metadata of @NgModule include ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What is a Module in Angular ?</summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">How to bootstrap a root module called AppModule ? </summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text"></summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text"></summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text"></summary>
<ul><li></li></ul>
</details>
<details class="mt-1">
<summary class="query-text">What are Web workers ?</summary> 
<ul>
<li> Web Workers are a simple means for web content to run scripts in background threads.</li>
<li> Web Workers allow you to run CPU intensive computations in a background thread, freeing the main thread to update the user interface.</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">What are basic building blocks of angular (or) angular architecture ?</summary> 
<ul>
<li> NgModules - provides compilation context for components and collect related code into functional sets</li>
<li> An angular app is defined by a set of NgModules</li>
<li> An app always has at least a root module that enables bootstrapping, and typically has many more feature modules.</li>
<li> An Angular module is a container for a group of related components, services, directives, and pipes.</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">What are the Key Components of angular ?</summary> 
<ul>
<li> <em>Component</em>: These are the basic building blocks of angular application to control HTML views.</li>
<li> <em>Modules</em>: An angular module is set of angular basic building blocks like component, directives, services etc. An application is divided into logical pieces and each piece of code is called as "module" which perform a single task.</li>
<li> <em>Templates</em>: This represent the views of an Angular application.</li>
<li> <em>Services</em>: It is used to create components which can be shared across the entire application.</li>
<li> <em>Metadata</em>: This can be used to add more data to an Angular class.</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">Define angular Decorators ?</summary> 
Decorators are functions that mark the classes and provides metadata that tells angular how to use them.
</details>
<details class="mt-1">
<summary class="query-text"> What is Angular CLI ?</summary>
Command Line Interface helps to speed up development process and perform following tasks
<ul>
  <li> Bootstrapping your application</li>
  <li> Serving your application</li>
  <li> Running tests(Both unit & end-to-end)</li>
  <li> Creating a build for distribution</li>
  <li> Generating components, services, routes and more for your application</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text"> Name some angular-cli commands </summary>
<ul>
<li> ng new</li>
<li> ng generate</li>
<li> ng serve</li>
<li> ng test</li>
<li> ng update</li>
<li> ng build</li>
<li> ng version</li>
<li> ng g c— Generates a new component.</li>
<li> ng g s— Generates a new service.</li>
<li> ng g d— Generates a new directive.</li>
<li> ng g m— Generates a new module.</li>
<li> ng g application— Generates a new app within the same project. This command was introduced in Angular 6.</li>
<li> ng g library— Starting with Angular 6, you can generate a library project.</li>
</ul>
</details>
<details class="mt-1">
<summary class="query-text">Describe structure of angular application ?</summary>
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

