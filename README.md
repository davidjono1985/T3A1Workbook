
# T3A1 - WORKBOOK
#### By David Johnson

## Question 1 
```
Provide an overview and description of a standard source control process for a large project
```
![Source Control](./docs/version_control.jpg)
*image stolen from https://www.smartsheet.com/*

Source control = version control
Online repository eg github
Branching
Merging (staging environment)
Git Flow

Source control (or version control) is the practice of tracking and managing changes to code. 

A source code management (SCM) system is utilized to streamline the development process and to provide a centralized source for all of the code.

SCM systems allow the tracking of code changes, revision history for the code, and the ability to revert to previous versions of a project when needed. 

By using a SCM system, you can collaborate on code with your team, isolate your work until it is ready, and quickly trouble-shoot issues by identifying who made changes and what the changes were. 

A standard process for managing source control is as follows:
1.	Use a source control system.
2.	Keep your source code in source control 
3.	Ensure the working file is from the latest version of the source file.
4.	Only check-out the file being worked upon.
5.	Check in immediately after alterations are completed.
6.	Review every change before committing. 
7.	Commit often 
8.	Make extensive, detailed notes in the check-in comments about why the changes were made.

## Question 2
```
What are the most important aspects of quality software?
```
![Source Control](./docs/quality.png)
*image stolen from http://www.davidchappell.com*

•	Functional Quality
•	Structural Quality
•	Functional Quality

•	Reliable
•	Understandable
•	Modifiable
•	Usabille
•	Scalable
•	Testable
•	Portable
•	Efficient

## Question 3
```
Outline a standard high level structure for a MERN stack application and explain the components
```
![Source Control](./docs/mern1.png)
*image stolen from https://www.mongodb.com/*

![Source Control](./docs/mern2.png)
*image stolen from https://levelup.gitconnected.com/*

4 components: provide an end-to-end framework for developers to work in
Mongo DB:
Express.js
React
Node.js
 

## Question 4
```
A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?
```
Project management methodologies
Programming and updates/changes to languages – technical knowledge – html/css/backend
Testing
Basic design – Responsive design
Photoshop etc
SEO
marketing
Security – Understanding common security attacks and how to prevent them
Image Resizing and Effects
Patience
Time Management and Detailed Planning
Documentation
Deployment/hosting
Conversational and negotiation
Understanding of the business and what they want to achieve


## Question 5
```
With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges
```
Rad Kelly's

![Source Control](./docs/rad_kellys.png)
*I own this image and you cannot have it*

## Question 6
```
With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature
```

Read it 'n' Wipe

![Source Control](./docs/read_wipe.jpg)
*I own this image and you cannot have it*

## Question 7
```
Explain control flow, using an example from the JavaScript programming language
```
The control flow is the order in which the computer executes statements in a script. ... A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.

## Question 8
```
Explain type coercion, using examples from the JavaScript programming language
```

Type coercion is the process of converting value from one type to another (such as string to number, object to boolean, and so on). Any type, be it primitive or an object, is a valid subject for type coercion. To recall, primitives are: number, string, boolean, null, undefined

## Question 9
```
Explain data types, using examples from the JavaScript programming language
```
In JavaScript, there are 6 primitive data types: string, number, boolean, null, undefined, symbol (new in ECMAScript 2015)

## Question 10
```
Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language
```
As you can see, JavaScript gives you some powerful ways to manipulate arrays — you can alter the elements at the start of an array with unshift() and shift() , modify the end of an array with push() and pop() , and add or remove elements at any point in an array with splice()


## Question 11
```
Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language
```
In JavaScript objects are simply a data structure made up of key-value pairs. A blueprint for an object can be made by using a function that acts as a constructor function for the objects. You can also create an object literal that will result in a single object that you can't duplicate

## Question 12
```
Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language
```

Stringify, parse and DOM manipulation

## Question 13
```
For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes
```

**Code Snippet:**

```javascript

class Car {
  constructor(brand) {
    this.carname = brand;
  }
  present() {
    return 'I have a ' + this.carname;
  }
}

class Model extends Car {
  constructor(brand, mod) {
    super(brand);
    this.model = mod;
  }
  show() {
    return this.present() + ', it was made in ' + this.model;
  }
}

let makes = ["Ford", "Holden", "Toyota"]
let models = Array.from(new Array(40), (x,i) => i + 1980)

function randomIntFromInterval(min,max) { // min and max included
    return Math.floor(Math.random()*(max-min+1)+min);
}

for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]
  model = models[randomIntFromInterval(0,makes.length-1)]
    
  mycar = new Model(make, model);
  console.log(mycar.show())
}
```