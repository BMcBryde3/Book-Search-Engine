# Book-Search-Engine

## Description

This application allows users to create an account, look up books using Google Books, add those books to their own personalized reading list and also removing them.

## Table Of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [License](#license)
4. [Contribution Guidelines](#contribution)
5. [Tests](#tests)
6. [Questions](#questions)

## Installation

1. Install the files, make sure you also have MongoDB installed.
2. Open the base file in a terminal and run "npm i", followed by "npm run build".
3. Add an .env file with the following values and appropriate links to your db:
   MONGODB_URI='mongodb://000.0.0.1:27017/googlebooks'
   JWT_SECRET_KEY='shhhhhmysecret'
4. Then start the program run "npm run start:dev".

## Usage

1. Create a new account.
2. Enter a username, email and password.
3. Once logged in, search for a book typing a book title or author in the search bar and clicking search.
4. Browse the list of results and click the "Add" button to add the book to the reading list. <br>
   ![Search for books](./Assets/18-mern-homework-demo-01.gif)<br>
   ![Save books to list](./Assets/18-mern-homework-demo-02.gif)<br>
5. Once you have added some favoritesm you can browse the saved books in the Saved Books page.
6. You can also remove books from here by clicking the "Delete" button on the book.<br>
   ![Browse saved books and delete them](./Assets/18-mern-homework-demo-03.gif)

Note: You can see a live example at this link :<br>
[Book Search Engine Deployed Site](https://book-search-engine-ext3.onrender.com/)

## License

None.

## Contribution Guidelines

None

## Tests

Render and Visual Studio Code

## Questions

Feel free to reach out to me if you have any questions, or if you'd like to find out what else I've worked on. My details are as follows:  
 Github: https://github.com/BMcBryde3
Email: Brett.McBryde@yahoo.com
