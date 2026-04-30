# LAB_EXTERNAL_FINAL_FULLSTACK_24BCS12132

# LAB_EXTERNAL_FINAL_FULLSTACK_24BCS12132

## Project Overview

This project is developed as part of the Full Stack Development Lab External Examination. It demonstrates both frontend and backend concepts through two tasks:

* QN 2: Display current date and time using JavaScript
* QN 4: Create a REST API to fetch student data using Node.js and Express

## Technologies Used

* Frontend: HTML, JavaScript
* Backend: Node.js, Express.js

## Project Structure

```
project-folder/
│
├── index.html
├── scripts.js
│
├── server.js
├── package.json
└── controllers/
    └── StudentController.js
```

## QN 2: Date and Time Display

### Description

This module demonstrates DOM manipulation and event handling. When the user clicks the button, the current date and time are displayed.

### Working

1. Button click triggers JavaScript function
2. Current date is fetched using Date()
3. Output is formatted using toLocaleString()
4. Result is displayed on the webpage

## QN 4: Student API

### Description

This module implements a REST API using Express.js to return student data in JSON format.

### API Endpoint

GET /students

### Sample Response

```json
[
  { "id": 1, "name": "John Doe", "age": 20, "grade": "A" },
  { "id": 2, "name": "Jane Smith", "age": 21, "grade": "B+" }
]
```

### Working

1. Express server is created
2. Route /students is defined
3. Controller sends student data
4. Response is returned in JSON format

## Installation & Setup

Step 1: Install dependencies

```
npm install
```

Step 2: Run server

```
npm start
```

Step 3: Access project

* Open index.html in browser
* API: http://localhost:3000/students

## Key Concepts

* DOM Manipulation
* Event Handling
* REST API
* JSON Handling
* Basic MVC Structure

## Conclusion

This project demonstrates basic full-stack development by integrating frontend interaction with backend API functionality.
