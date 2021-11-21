# :zap: Angular Engineering Calculator

* App to do simple arithmetic calculations.
* Tutorial code from [Ahmed Bouchefra, TechieDiaries: Angular 9 Tutorial and Example: Build your First Angular App](https://www.techiediaries.com/angular/angular-9-tutorial-and-example/) to be expanded into a more complex calculator with Engineering functions.
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/angular-engineering-calculator?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/angular-engineering-calculator?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/angular-engineering-calculator?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/angular-engineering-calculator?style=plastic)

## :page_facing_up: Table of contents

* [:zap: Angular Engineering Calculator](#zap-angular-engineering-calculator)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Calculator created in HTML and CSS, using html from a [jsfiddle by Ayo Isaiah](http://jsfiddle.net/ayoisaiah/c8b9zsaq/)

## :camera: Screenshots

![Example screenshot](./img/calc.png)

## :signal_strength: Technologies

* [Angular v13](https://angular.io/)

## :floppy_disk: Setup

* Install dependencies using `npm i`
* Run `npm start` to get a server at `http://localhost:4200/`
* Run `npm run build` to build the project. The build artifacts will be stored in the `docs` directory.

## :computer: Code Examples

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

## :cool: Features

* Angular event binding used to bind the `getNumber()` method to the button `(click)` DOM event

## :clipboard: Status & To-Do List

* Status: Working.
* To-Do: Add engineering functions

## :clap: Inspiration

* [Ahmed Bouchefra, TechieDiaries: Angular 9 Tutorial and Example: Build your First Angular App](https://www.techiediaries.com/angular/angular-9-tutorial-and-example/),

## :file_folder: License

* This project is licensed under the terms of the MIT license.

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com
