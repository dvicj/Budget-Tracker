# Budget Tracker

Hello, and welcome to my README! This is for my Week 19 Challenge, which was to refractor existing code for a Budget Tracket into a PWA. 

![main page](https://drive.google.com/file/d/1m8YndScz7C3kKyT_6BjR3ye86ut5J7tP/view?usp=sharing)


It was my job to ensure my Budget Tracker had the following features:

- Include a service worker 
- Include a web manifest
- Must use IndexedDB for offline functionality
- Must be deployed to Heroku


I was to turn this Budget Tracker into a PWA, and meet all of the requirements listed above, by using:

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Heroku](https://heroku.com)
- JavaScript - ES6

I completed this project as a way to work on my skills using MongoDB and turning existing code into PWAs. 

Features:

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [Learning](#learning)
* [License](#license)

## Installation

The user must clone all files from this repo. It is important that the location of the files is not changed. 

The user must have [Node.js](https://nodejs.org/en/download/) and [MongoDB](https://www.mongodb.com/try/download/community) installed on their computer. 

The user must open the terminal, both command line and powershell will work, then enter "npm install" to download all the required dependencies (express, mongoose, and moment).This will allow the user to run the application as intended. 

To run the application, user must enter "npm start" in the command line. This will start the MongoDB server. 

The localhost must then be opened on a web browser. This will allow the user to GET, POST, PUT and DELETE data as they see fit. This backend will only be available to the user on their own computer. 

Alternatively, the application can be viewed anywhere from [Heroku](https://stark-garden-15853.herokuapp.com/)

## Usage
Here are some user experience highlights from my page:

When the user adds or subtracts from their budget while they are offline, the data will be saved to IndexedDB in the web browser. Once internet connection is re-established, the informtion will be added to the database. 

The user has the option to download the application to their desktop/ mobile device. 

Service worker:

![service worker](https://github.com/dvicj/Budget-Tracker/blob/main/public/images/serviceworker.PNG)


Web manifest: 

![web manifest](https://github.com/dvicj/Budget-Tracker/blob/main/public/images/mainfest.PNG)


IDB: 

![idb file](https://github.com/dvicj/Budget-Tracker/blob/main/public/images/idb.PNG)

## Credits
These are some sources I used to help me along:

- [Node.js](https://nodejs.org/en/download/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [mongoose](https://mongoosejs.com/)
- [compression](https://www.npmjs.com/package/compression)
- [morgan](https://www.npmjs.com/package/morgan)
- [lite-server](https://www.npmjs.com/package/lite-server)
- [Heroku](https://heroku.com)
- [Web app manifests: display](https://developer.mozilla.org/en-US/docs/Web/Manifest/display)

  
## Learning
Here are the highlights of what I learned and issues I had while writing this code.

- I think I like working with MongoDB/mongoose more than MySQL or sqlite. The virtuals and schemas were cool and easy to use and offer a lot more options for easy customization.
- I was having a problem setting up my database for a while, then I realized that the MongoDB server was not just running in the background, I had to manually start it by running "mongod" in the command line. Once I did that I didn't have anymore issues. 

## License
MIT License

![license](https://img.shields.io/static/v1?label=license&message=MIT&color=blueviolet)

Copyright (c) 2021 Devin Jones

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
