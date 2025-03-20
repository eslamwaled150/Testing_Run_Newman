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


# Setup and Run Guide

### Clone the Repository  
```sh
git clone https://github.com/eslamwaled150/Testing_Run_Newman.git  
cd Testing_Run_Newman  
```

### Install Dependencies  
```sh
npm install  
```

### Start JSON Server with Authentication  
```sh
json-server-auth db.json --watch  
```

### Start the Development Server  
```sh
npm run dev  
```

### Run Newman with Extra HTML Report  
```sh
newman run "./NEWMAN_FOLDER/collection name.json" -r htmlextra --reporter-htmlextra-export "./NEWMAN_FOLDER/Newman_Reporter/Newman_Reporter.html"  
```


