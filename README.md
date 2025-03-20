## This workspace is designed for managing and testing APIs related to Courses and Users. It includes structured API requests for CRUD operations (Create, Read, Update, Delete) using HTTP methods:

### Courses API
#### POST /course – Add a new course
#### GET /course – Retrieve existing courses
#### PUT /course – Update course details
#### DELETE /course – Remove a course
#### GET /courses -Retrieve all courses

### Users API
#### POST /user – Register a new user
#### GET /user – Retrieve user details
#### PUT /user – Update user information
#### DELETE /user – Remove a user


## Setup and Run Guide

### 1.Clone the Repository
### git clone https://github.com/eslamwaled150/Testing_Run_Newman.git
### cd Testing_Run_Newman
### 2.Install Dependencies
#### npm install
### 3.Start JSON Server with Authentication
#### json-server-auth db.json --watch
### 4.Start the Development Server
#### npm run dev
### 5.Run the Newman Report
#### "./NEWMAN_FOLDER/name of collection.json" -r htmlextra --reporter-htmlextra-export "./NEWMAN_FOLDER/Newman_Reporter.html"

