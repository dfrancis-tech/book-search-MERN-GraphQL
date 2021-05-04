#  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Google Books Search

[Summary](#Summary) &nbsp; &nbsp; [Introduction](#Introduction) &nbsp; &nbsp; [Mock-Up](#Mock-up) &nbsp; &nbsp; [Built With](#Built-With) &nbsp; &nbsp; [User Story](#User-Story) &nbsp; &nbsp; [Acceptance Criteria](#Acceptance-Criteria)  &nbsp; &nbsp; [Code Review](#Code-Review)   

 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [***Live Project***](#Live-Project)

## Summary

 Google Books Search website is a web application where users can search for books, create an account, save their favourite books and delete saved books.

## Introduction
 
 This website is Google Books API search engine built with a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.    

## Live Project

Visit [website](https://intense-shore-78978.herokuapp.com/) and enjoy reading!

## Mock-Up
The following image shows the web application's appearance and functionality.  

![Mock-up image](client/public/mock-up.gif "Mock-up image")

## Built With
* [MongoDB](https://www.mongodb.com/)
* [Express.js](https://expressjs.com/)
* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en/)
* [JavaScript](https://www.javascript.com/) ES5 ES6  
* [React Router](https://reactrouter.com/)
    * [React Router DOM](https://www.npmjs.com/package/react-router-dom)
* [GraphQL](https://graphql.org/)
    * [graphql](https://www.npmjs.com/package/graphql)
    * [graphql-tag](https://www.npmjs.com/package/graphql-tag)
* [JWT:JSON web Token](https://www.npmjs.com/package/jsonwebtoken)
    * [JWT Decode](https://www.npmjs.com/package/jwt-decode)
* [Appolo Server](https://www.apollographql.com/docs/apollo-server/)
    * [Appolo Client](https://www.apollographql.com/docs/react/)
    * [Appolo Server Express](https://www.npmjs.com/package/apollo-server-express)
    * [Appolo Boost](https://www.npmjs.com/package/apollo-boost)
    * [Appolo React Hooks](https://www.npmjs.com/package/@apollo/react-hooks)
* [if-env](https://www.npmjs.com/package/if-env)
* [concurrently](https://www.npmjs.com/package/concurrently)
* [Faker.js](https://www.npmjs.com/package/faker)
* [nodemon](https://www.npmjs.com/package/nodemon)
* [bcrypt](https://www.npmjs.com/package/bcrypt)
* [Mongoose](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/mongoose)
* [Heroku](https://www.heroku.com/)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas2)

## User Story
<details>
<summary>Expand</summary>  

    AS AN avid reader
    I WANT to search for new books to read
    SO THAT I can keep a list of books to purchase
</details>

## Acceptance Criteria
<details>
<summary>Expand</summary>

    GIVEN a book search engine
    WHEN I load the search engine
    THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
    WHEN I click on the Search for Books menu option
    THEN I am presented with an input field to search for books and a submit button
    WHEN I am not logged in and enter a search term in the input field and click the submit button
    THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
    WHEN I click on the Login/Signup menu option
    THEN a modal appears on the screen with a toggle between the option to log in or sign up
    WHEN the toggle is set to Signup
    THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
    WHEN the toggle is set to Login
    THEN I am presented with two inputs for an email address and a password and login button
    WHEN I enter a valid email address and create a password and click on the signup button
    THEN my user account is created and I am logged in to the site
    WHEN I enter my account’s email address and password and click on the login button
    THEN I the modal closes and I am logged in to the site
    WHEN I am logged in to the site
    THEN the menu options change to Search for Books, an option to see my saved books, and Logout
    WHEN I am logged in and enter a search term in the input field and click the submit button
    THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
    WHEN I click on the Save button on a book
    THEN that book’s information is saved to my account
    WHEN I click on the option to see my saved books
    THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
    WHEN I click on the Remove button on a book
    THEN that book is deleted from my saved books list
    WHEN I click on the Logout button
    THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button   
</details>

## Code Review

The completed project is uploaded in Github.  
Repository link:  [GitHub](https://github.com/rosefrancis-tech/book-search-MERN-GraphQL)  
