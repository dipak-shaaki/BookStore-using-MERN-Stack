# BookStore-using-MERN-Stack

A simple web application built using the MERN stack to manage books by performing CRUD operations (Create, Read, Update, Delete).

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [Contributing Guidelines](#contributing-guidelines)

## Project Overview
This project allows users to interactively manage a collection of books through basic CRUD operations.

## Features

*   Create New Books: Add title, author(s), publication date.
*   Read All Books: Display list of all available books with their details.
*   Update Existing Books: Modify any field of an existing book entry.
*   Delete Unwanted Books: Remove any book from the database.

## Technologies Used

| Technology | Role |
|------------|------|
| MongoDB    | Database |
| Express    | Backend Framework |
| React      | Frontend Library |
| Node       | Runtime Environment |

### Additional Tools:

None required beyond standard development tools like npm for package management.

## Setup Instructions:

1.. Clone this repository:
    ```
    [git clone https://github.com/dipak-shanki/BookStore-using-MERN-Stack.git](https://github.com/dipak-shanki/BookStore-using-MERN-Stack.git)
    ```

2.. Configure `config.js` files if needed:

     - In `server` directory:
       ```
       mongo_URL=mongodb://localhost/bookstore  
       ```

4.. Run Development Servers:

     - Start backend server from `server` directory:
        ```
        npm run dev   
        ```
        
     - Start frontend development server from `client` directory:
        ```
        npm start   
        ```

5.. Access your app at http://localhost:3000/

6.. Use Postman or similar tools to test API endpoints if needed.


## Contributing Guidelines 

Contributions are welcome! Here’s how you can contribute:

1.. Fork this repository on GitHub.
2.. Make changes locally on your forked version following standard commit guidelines.
3.. Open a pull request against this repository’s main branch.


Thank you!
