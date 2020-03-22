# Angular Engineering Calculator

* App to do simple arithmetic calculations.
* Tutorial code from [Ahmed Bouchefra, TechieDiaries: Angular 9 Tutorial and Example: Build your First Angular App](https://www.techiediaries.com/angular/angular-9-tutorial-and-example/) to be expanded into a more complex calculator with Engineering functions.

*** Note: to open web links in a new window use: _ctrl+click on link_**

## Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

* Calculator created in HTML and CSS, using html from a [jsfiddle by Ayo Isaiah](http://jsfiddle.net/ayoisaiah/c8b9zsaq/)

## Screenshots

![Example screenshot](./img/calc.png)

## Technologies

* [Angular v9.0.5](https://angular.io/)

## Setup

* Install dependencies using `npm i`
* Run `ng serve` to get a server at `http://localhost:4200/`
* If required, run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Code Examples

* Switch statement used to return the result of different operations depending on the operand used

```typescript
  private doCalculation(op: any, secondOp: any) {
    switch (op) {
      case '+':
        return this.firstOperand += secondOp;
      case '-':
        return this.firstOperand -= secondOp;
      case '*':
        return this.firstOperand *= secondOp;
      case '/':
        return this.firstOperand /= secondOp;
      case '=':
        return secondOp;
    }
  }
```

## Features

* Angular event binding used to bind the `getNumber()` method to the button `(click)` DOM event

## Status & To-Do List

* Status: Working
* To-Do: Add engineering functions

## Inspiration

[Ahmed Bouchefra, TechieDiaries: Angular 9 Tutorial and Example: Build your First Angular App](https://www.techiediaries.com/angular/angular-9-tutorial-and-example/),

## Contact

Repo created by [ABateman](https://www.andrewbateman.org) - feel free to contact me!
