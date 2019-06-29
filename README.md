## My Virtual Bookshelf

An app to search for and organize all the books on your reading list, using the Google Books API! Users can create a "virtual bookcase" ordering books by what they want to read, are reading and have read. Created as a group project for Epicodus, demonstrating knowledge of JavaScript, Angular, API calls and more.

#### by Ian Christopher, Kevin Garvey, Svitlana Filanova, Marguerite Kennedy and Tessa Sullivan.


## Setup/Installation Requirements

* _Clone this repository on your Desktop._
* _Open Terminal (for Mac users) or PowerShell (for Windows users), navigate to age_calculator folder(cd .../Desktop/doctor) and run the following command: npm install._
* _Send one of us email to request FirebaseConfig. Once reseived copy api-keys.ts file in the project  src/app folder._
* _You need to generate your own Google Books API key. Go to https://console.developers.google.com/apis/credentials?project=book-reviews-group-project&folder&organizationId > Credentials > Create credentials > API key. Copy your API key and paste in api-keys.ts file._
* _Run the following command to install AngularFire and Firebase npm packages: npm install angularfire2@4.0.0-rc.0 firebase@^3.6.6 --save._
* _Now run ng serve and open a localhost in your browser._

## Description

| User stories                                                                                          |
|-------------------------------------------------------------------------------------------------------|
| I should be able to login my account via Google.                                                      |
| I should be able to search books by author, subject or title.                                         |
| I should be able to add a selected book to one of shelves.                                            |
| I should be able to see my book list.                                                                 |
| In my book list I should be able to see books that I want to read, currently reading or already read. |
| I should be able to move books to any shelf.                                                          |
| I should be able to see book details.                                                                 |

## Known Bugs / Limitations

* _If you click "My list" in dropdown menu you'll see the following error in the console: "ERROR TypeError: Cannot read property 'length' of null at ShelfPipe.webpackJsonp.386.ShelfPipe.transform (shelf.pipe.ts:13)", but it doesn't affect the application's functionality._

## Technologies Used

_Angular, Node.js, Javascript, Typescript, Firebase, Bootstrap, HTML, API_

_This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0._

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

*This software operates under the MIT license.*

Copyright (c) 2019 **_Ian Christopher, Kevin Garvey, Svitlana Filanova, Marguerite Kennedy and Tessa Sullivan_**
