<p align="center">
  <a href="https://angularclass.com" target="_blank">
    <img src="/media/awesome-angular2.png" alt="Awesome Angular 2" />
  </a>
</p>

# Awesome Angular 2 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Awesome list of [Angular 2](https://angular.io/) seed repos, starters, boilerplates, examples, tutorials, components, modules, videos, and anything else in the Angular 2 ecosystem

##### Current Angular 2 version:
[![npm version](https://badge.fury.io/js/angular2.svg)](http://badge.fury.io/js/angular2)

Table of contents:
* [Angular 2](#angular-2)
  * [Angular 2 General Resources](#angular-2-general-resources)
  * [Angular 2 Community](#angular-2-community)
  * [Angular 2 Server-Side Rendering](#angular-2-server-side-rendering)
  * [Angular 2 Material Design](#angular-2-material-design)
  * [Angular 2 Cheatsheet](#angular-2-cheatsheet)
  * [Angular 2 Features](#angular-2-features)
    * [Annotations](#annotations)
      * [Directives](#directives)
      * [Components](#components)
    * [View](#view)
      * [Overview](#overview)
      * [Simple View](#simple-view)
      * [Composed View](#composed-view)
      * [Component Views](#component-view)
      * [Evaluation Context](#evaluation-context)
      * [Lifecycle (Hydration and Dehydration)](#lifecycle-hydration-and-dehydration)
    * [Templates](#templates)
      * [Property bindings](#property-bindings)
      * [Binding events](#binding-events)
      * [String Interpolation](#string-interpolation)
      * [Inline Templates](#inline-templates)
      * [Template Microsyntax](#template-microsyntax)
    * [Change detection](#change-detection)
      * [Immutable Objects](#immutable-objects)
      * [Observable Objects](#observable-objects)
    * [DI](#di)
      * [Core Abstractions](#core-abstractions)
      * [Example](#example)
      * [Child Injectors and Dependencies](#child-injectors-and-dependencies)
        * [Constraints](#constraints)
        * [DI Does Not Walk Down](#di-does-not-walk-down)
      * [Bindings](#bindings)
        * [Resolved Bindings](#resolved-bindings)
      * [Transient Dependencies](#transient-dependencies)
    * [HTTP](#http)
    * [Pipes](#pipes)
    * [Router](#router)
    * [Test](#test)
    * [Web Workers](#web-workers)
    * [Server-Rendering](#web-workers)
  * [Angular 2 Tutorials](#angular-2-tutorials)
  * [Angular 2 Series](#angular-2-series)
  * [Angular 2 Video Tutorials](#angular-2-video-tutorials)
  * [Angular 2 Books](#angular-2-books)
  * [Angular 2 On-Site Training](#angular-2-on-site-training)
  * [Angular 2 Approach and Explanation](#angular-2-approach-and-explanation)
  * [Angular 2 Integrations](#angular-2-integrations)
  * [Angular 2 Components](#angular-2-components)
  * [Angular 2 Generators](#angular-2-generators)
  * [Angular 2 TodoMVC](#angular-2-todomvc)
* [Universal](#universal-angular-2)
  * [Universal General Resources](#universal-general-resources)
  * [Seed Projects](#universal-seed-projects)
* [TypeScript](#angular-2-in-typescript)
  * [TypeScript General Resources](#typescript-general-resources)
  * [Seed Projects](#typescript-seed-projects)
* [Dart](#angular-2-in-dart)
  * [Seed Projects](#dart-seed-projects)
* [Traceur](#angular-2-in-traceur)
  * [Traceur General Resources](#traceur-general-resources)
  * [Seed Projects](#traceur-seed-projects)
* [Babel](#angular-2-in-babel)
  * [Babel General Resources](#babel-general-resources)
  * [Seed Projects](#babel-seed-projects)
* [ES5](#angular-2-in-es5)
  * [Seed Projects](#es5-seed-projects)
* [Ionic 2](#ionic-2-in-angular-2)
  * [Ionic 2 General Resources](#ionic-2-general-resources)
* [Meteor](#meteor-in-angular-2)
  * [Meteor General Resources](#meteor-general-resources)
  * [Seed Projects](#meteor-seed-projects)
* [NativeScript](#angular-2-in-nativescript)
  * [NativeScript General Resources](#nativescript-general-resources)
  * [Seed Projects](#nativescript-seed-projects)
* [React Native](#angular-2-in-react-native)
  * [React Native General Resources](#react-native-general-resources)
  * [React Native Projects](#react-native-projects)
* [Haxe](#angular-2-in-haxe)
  * [Seed Projects](#haxe-seed-projects)
* [Scala](#angular-2-in-scala)
  * [Seed Projects](#scala-seed-projects)

### Angular 2
> Angular is a development platform for building mobile and desktop web applications.

#### Angular 2 General Resources
* [Official Site](https://angular.io/)
* [Official Blog](http://angularjs.blogspot.com/)
* [Official Documentation](https://angular.io/docs/js/latest/)
* [Official Getting Started Guide](https://angular.io/docs/js/latest/quickstart.html)
* [Official GitHub Repo](https://github.com/angular/angular)

#### Angular 2 Community
* `#angular2` channel on Freenode IRC Server
* [`#angular2`](https://twitter.com/hashtag/angular2) hashtag on Twitter
* [Gitter Channel](https://gitter.im/angular/angular)
* [Angular 2 StackOverflow](http://stackoverflow.com/questions/tagged/angular2)
* [@AngularJS on Twitter](https://twitter.com/angularjs)
* [/r/Angular2 Subreddit](http://www.reddit.com/r/angular2/)
* [Angular Group on Facebook](https://www.facebook.com/groups/angular2/)
* [AngularJS on Google+](https://plus.google.com/u/0/+AngularJS/posts)
* [AngularAir](http://angular-air.com/)
* [ng-newsletter](http://www.ng-newsletter.com)
* [tryangular2](http://www.tryangular2.com/)
* [Built With Angular 2](http://builtwithangular2.com/)
* [`#ng-2 Slack Channel`](https://angularbuddies.slack.com/messages/ng-2/) on AngularBuddies ([Sign up](http://www.angularbuddies.com/))
* [`#angular2 Slack Channel`](https://dartlang.slack.com/messages/angular2) on dartlang.slack.com ([Sign up](https://dartlang-slack.herokuapp.com/))

#### Angular 2 Server-Side Rendering
* [Angular 2 Universal Repository (GitHub)](https://github.com/angular/universal)

#### Angular 2 Material Design
* [Official Angular 2 Material Design (GitHub)](https://github.com/angular/angular/tree/master/modules/angular2_material)

#### Angular 2 Cheatsheet
* [TypeScript/Babel API Cheatsheet](https://docs.google.com/document/d/19jHbsXeYj2QiZ-cGS_mA3nyaU86gLeonjU2Tfzm1J5Y/mobilebasic)
* [Dart API Cheatsheet](https://docs.google.com/document/d/1FYyA-b9rc2UtlYyQXjW7lx4Y08MSpuWcbbuqVCxHga0/edit#heading=h.34sus6g4zss3)
* [Angular2 Dart cheatsheet](https://github.com/andresaraujo/angular2_cheatsheet_dart)

#### Angular 2 Features

* Annotations
* Directives
* Components
* View
* Overview
* Simple View
* Composed View
* Component Views
* Evaluation Context
* Lifecycle (Hydration and Dehydration)
* Templates
* Property bindings
* Binding events
* String Interpolation
* Inline Templates
* Template Microsyntax
* Change detection
* Immutable Objects
* Observable Objects
* DI
* Core Abstractions
* Example
* Child Injectors and Dependencies
* Constraints
* DI Does Not Walk Down
* Bindings
* Resolved Bindings
* Transient Dependencies
* HTTP
* Pipes
* Router
* Test
* Web Workers
* Server-Rendering


#### Angular 2 Tutorials

#### Angular 2 Series
* Ionic
  * Angular 2
    * [Introduction](http://blog.ionic.io/angular-2-series-introduction/)
    * [Components](http://blog.ionic.io/angular-2-series-components/)
* Auth0
  * Angular 2
    * [Working with Pipes](https://auth0.com/blog/2015/09/03/angular2-series-working-with-pipes/)
    * [Domain Models and Dependency Injection](https://auth0.com/blog/2015/09/17/angular-2-series-part-2-domain-models-and-dependency-injection/)
* thoughtram
  * Angular 2 Template Syntax Demystified
    * [Part 1](http://blog.thoughtram.io/angular/2015/08/11/angular-2-template-syntax-demystified-part-1.html)

#### Angular 2 Video Tutorials
* [Egghead.io - Angular 2](https://egghead.io/technologies/angular2)
* [udemy - Introduction to Angular 2](https://www.udemy.com/introduction-to-angular2/)

#### Angular 2 Books
* [ng-book 2](https://ng-book.com/2) `fullstack.io`
* [Become a ninja with Angular 2](https://books.ninja-squad.com/angular2) `Ninja Squad`

#### Angular 2 On-Site Training
* [AngularClass](https://angularclass.com)
* [thoughtram](http://thoughtram.io/training.html)
* [Egghead.io](https://egghead.io/angularjs-enterprise-training-workshop)
* [ng-book](https://www.ng-book.com/2/)

#### Angular 2 Approach and Explanation

* Victor Savkin
  * [Dependency Injection in Angular 1 and Angular 2](http://victorsavkin.com/post/126514197956/dependency-injection-in-angular-1-and-angular-2)
  * [Writing Angular 2 in Typescript](http://victorsavkin.com/post/123555572351/writing-angular-2-in-typescript)
  * [Angular 2 Template Syntax](http://victorsavkin.com/post/119943127151/angular-2-template-syntax)
  * [The Core Concepts of Angular 2](http://victorsavkin.com/post/118372404541/the-core-concepts-of-angular-2)
  * [Two Phases of Angular 2 Applications](http://victorsavkin.com/post/114168430846/two-phases-of-angular-2-applications)
  * [Change Detection in Angular 2](http://victorsavkin.com/post/110170125256/change-detection-in-angular-2)
  * [Better Support For Functional Programming In](http://victorsavkin.com/post/108837493941/better-support-for-functional-programming-in)
  * [Angular 2 Bits Unified Dependency Injection](http://victorsavkin.com/post/102965317996/angular-2-bits-unified-dependency-injection)

* thoughtram
  * [Developing a tabs component in Angular 2](http://blog.thoughtram.io/angular/2015/04/09/developing-a-tabs-component-in-angular-2.html)
  * [Developing a zippy component in Angular 2](http://blog.thoughtram.io/angular/2015/03/27/building-a-zippy-component-in-angular-2.html)
  * [Resolving Service Dependencies in Angular 2](http://blog.thoughtram.io/angular/2015/09/17/resolve-service-dependencies-in-angular-2.html)
  * [Forward references in Angular 2](http://blog.thoughtram.io/angular/2015/09/03/forward-references-in-angular-2.html)
  * [Host and Visibility in Angular 2's Dependency Injection](http://blog.thoughtram.io/angular/2015/08/20/host-and-visibility-in-angular-2-dependency-injection.html)
  * [Dependency Injection in Angular 2](http://blog.thoughtram.io/angular/2015/05/18/dependency-injection-in-angular-2.html)
  * [Routing in Angular 2](http://blog.thoughtram.io/angular/2015/06/16/routing-in-angular-2.html)
  * [Angular 2 Template Syntax Demystified - Part 1](http://blog.thoughtram.io/angular/2015/08/11/angular-2-template-syntax-demystified-part-1.html)
  * [View Encapsulation in Angular 2](http://blog.thoughtram.io/angular/2015/06/29/shadow-dom-strategies-in-angular2.html)
  * [Styling Angular 2 components](http://blog.thoughtram.io/angular/2015/06/25/styling-angular-2-components.html)
  * [Even better ES5 code for Angular 2](http://blog.thoughtram.io/angular/2015/07/06/even-better-es5-code-for-angular-2.html)
  * [Writing Angular 2 code in ES5](http://blog.thoughtram.io/angular/2015/05/09/writing-angular-2-code-in-es5.html)
  * [The difference between Annotations and Decorators](http://blog.thoughtram.io/angular/2015/05/03/the-difference-between-annotations-and-decorators.html)

#### Angular 2 Integrations
* [FalcorJS + Angular2 (Video)](https://youtu.be/z8UgDZ4rXBU)
* [Angular2-Meteor](http://angular-meteor.com/angular2)
* [nativescript-angular](https://github.com/NativeScript/nativescript-angular)
* [react-native-renderer](https://github.com/angular/react-native-renderer)

### Angular 2 Components
* [Axponents: of Accessible Web Components (Dylan Barrell)](https://github.com/dylanb/Axponents/tree/master/angular2)
* [ng2-bootstrap: Native Angular2 bootstrap components](https://github.com/valor-software/ng2-bootstrap)
* [ng2-bs](https://github.com/pkozlowski-opensource/ng2-bs) Experiments with Angular 2 directives for Bootstrap.
* [ng2-handsontable](https://github.com/valor-software/ng2-handsontable) Excel-like data grid / spreadsheet

### Angular 2 Generators
* Node.js
  * Slush
    * [TheVelourFog/slush-angular2](https://github.com/TheVelourFog/slush-angular2)
  * Yeoman
    * [swirlycheetah/generator-angular2](https://github.com/swirlycheetah/generator-angular2)
* Dart
  * Stagehand
    * [kasperpeulen/stagehand](https://github.com/kasperpeulen/stagehand)

#### Angular 2 TodoMVC
* [Official Angular 2.0](http://todomvc.com/examples/angular2/)
* [Angular 2 Dart](https://github.com/ng2-dart-samples/todomvc)

---

### Universal Angular 2
> Universal (isomorphic) javascript support for Angular 2

#### Universal General Resources
* [Universal Angular 2 Repository (GitHub)](https://github.com/angular/universal)

#### Universal Seed Projects
* [fullstack-angular2-starter](https://github.com/angular-class/fullstack-angular2-starter) - Fullstack Angular 2 starter kit by @Angular-Class

---

### Angular 2 in TypeScript
> TypeScript lets you write JavaScript the way you really want to.
TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.

#### TypeScript General Resources
* [TypeScript](http://www.typescriptlang.org/) Official Website for TypeScript
* [REPL](http://www.typescriptlang.org/Playground) Official TypeScript REPL that runs entirely in your browser
* [TypeScript Repository (GitHub)](https://github.com/Microsoft/TypeScript) Official GitHub Repo for TypeScript
* [TSD](http://definitelytyped.org/tsd) TypeScript Definition manager for DefinitelyTyped
* [DefinitelyTyped Repository (GitHub)](https://github.com/borisyankov/DefinitelyTyped) The repository for high quality TypeScript type definitions.


#### TypeScript Seed Projects
* [Angular 2 Webpack Starter](https://angularclass.com/angular2-webpack-starter#awesome-angular2) - An Angular 2 Webpack Starter kit featuring Angular 2 (Router, Http, Forms, Services, Tests, E2E), Karma, Protractor, Jasmine, TypeScript, and Webpack by @Angular-Class
* [Angular 2 Seed](http://mgechev.github.io/angular2-seed#awesome-angular2) Seed project for Angular 2 apps
* [ng2-play.ts](https://github.com/pkozlowski-opensource/ng2-play.ts#awesome-angular2) A minimal Angular2 playground using TypeScript
* [NG2 Lab](https://github.com/rolandjitsu/ng2-lab#awesome-angular2) A simple Angular 2 setup using TypeScript, SystemJS and Firebase that also includes a few examples of unit testing and CI with Travis and Saucelabs.
* [Angular2Go](https://github.com/johnpapa/angular2-go#awesome-angular2) Angular 2 Go !
* [Angular 2 Samples](https://github.com/thelgevold/angular-2-samples) Angular 2.0 sample components
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

### Angular 2 in Dart
> Dart is an open-source, scalable programming language, with robust libraries and runtimes, for building web, server, and mobile apps.

#### Dart General Resources
* [Dart](https://www.dartlang.org/) Official Website for Dart
* [Dartpad](https://dartpad.dartlang.org/) Dartpad lets play with Dart on-line, in a zero-install, zero configuration environment.
* [Dart Organization (GitHub)](https://github.com/dart-lang) Official GitHub Organization for Dart
* [Pub](https://pub.dartlang.org/) Repository of packages of software for the Dart programming language.
* [Dartisans](https://plus.google.com/communities/114566943291919232850) The Official Dart Google+ community
* [Dart Slack Channel](https://dartlang-slack.herokuapp.com/) The Official Dart Slack channel.


#### Dart Seed Projects
* [Angular 2 Dart Quickstart](https://github.com/andresaraujo/ng2_dart_quickstart) A minimal quick start project.

#### Dart Demo, Samples, and Examples
* [Angular 2 Samples](https://github.com/ng2-dart-samples) Angular 2 for Dart demos and samples from the community.
* [Pipes](https://github.com/ng2-dart-samples/pipes) Examples of Pipes in Angular 2 for Dart.
* [Hackernews App](https://github.com/andresaraujo/ng2_hackernews) A HackerNews application made with Angular 2 for Dart
* [Router Demo](https://github.com/andresaraujo/ng2_dart_router_demo) A basic example of Angular 2 router.
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

### Angular 2 in Traceur

> Traceur is a JavaScript.next-to-JavaScript-of-today compiler

#### Traceur General Resources

* [Traceur Repository (GitHub)](https://github.com/google/traceur-compiler) Official GitHub Repo for Traceur

#### Traceur Seed Projects

* [GitHub: Angular2 ES6 Starter Kit (Dan Wahlin)](https://github.com/DanWahlin/Angular2-ES6-Starter/)
* [GitHub: ng2-play (Pawel Kozlowski)](https://github.com/pkozlowski-opensource/ng2-play#awesome-angular2) A minimal ES6 project using Angular 2.0.
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

### Angular 2 in Babel
> The compiler for writing next generation JavaScript.

#### Babel General Resources
* [Babel](https://babeljs.io/) Official Website for Babel
* [REPL](https://babeljs.io/repl/) Official Babel REPL that runs entirely in your browser
* [Babel Repository (GitHub)](https://github.com/babel/babel) Official GitHub Repo for Babel

#### Babel Angular 2 Online Playground
* [Plunker: Angular 2 + Babel](http://plnkr.co/edit/PxCzCu?p=preview)

#### Babel Seed Projects
* [babel-angular2-app](https://github.com/shuhei/babel-angular2-app) A skeleton Angular 2 app built with [Babel](https://babeljs.io/) and [Browserify](http://browserify.org/).
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

### Angular 2 in ES5
> An ECMAScript language that includes structured, dynamic, functional, and prototype-based features.

##### ES5 General Resources
* [**{{** help_add_resources **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

#### ES5 Seed Projects
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

#### Ionic 2 in Angular 2
> Ionic is the beautiful, open source front-end SDK for developing hybrid mobile apps with web technologies.

* [Ionic Framework](http://ionicframework.com) Official Website for Ionic Framework
* [Ionic Documentation](http://ionicframework.com/docs/v2/) Official for Ionic Framework

##### Ionic 2 General Resources
* [Ionic 2 Repository (GitHub)](https://github.com/driftyco/ionic2)

---

#### Meteor in Angular 2
> Build Realtime Web and Mobile Apps With Angular and Meteor

##### Meteor General Resources
* [Angular Meteor](http://angular-meteor.com) Official Website for Angular Meteor
* [Angular 2 Meteor](http://angular-meteor.com/angular2)

#### Meteor Seed Projects
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)


---

#### Angular 2 in NativeScript
> Build truly native iOS, Android and Windows Phone apps with Javascript and CSS. Try NativeScript open-source framework for cross-platform development.

##### NativeScript General Resources
* [NativeScript](https://www.nativescript.org/) Official Website for NativeScript

#### NativeScript Seed Projects
* [sample-Angular2](https://github.com/NativeScript/sample-Angular2)
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

#### Angular 2 in React Native
> React Native enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript

##### React Native General Resources
* [React Native](https://facebook.github.io/react-native/) Official Website for React Native

#### React Native Projects
* [Angular 2 React Native Renderer (GitHub)](https://github.com/angular/react-native-renderer)

#### React Native Seed Projects
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

### Angular 2 in Haxe
> Haxe is an open source toolkit based on a modern, high level, strictly typed programming language.

##### Haxe General Resources
* [**{{** help_add_resources **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

#### Haxe Seed Projects
* [angular2haxe](https://github.com/nweedon/angular2haxe) Haxe Language Bindings for Angular 2
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---

### Angular 2 in Scala
> General purpose language; multiparadigm (object-oriented, functional, concurrent elements); statically typed, type-safe; focus: Web services.

##### Scala General Resources
* [**{{** help_add_resources **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

#### Scala Seed Projects
* [play-angular2](https://github.com/gdi2290/play-angular2)
* [**{{** add_your_repo **}}**](https://github.com/angular-class/awesome-angular2/edit/gh-pages/README.md)

---


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
