# Book Search Engine

## description
Deployed pgae: https://damp-cove-66674-fdcfa06c6fba.herokuapp.com/
```md
This website is a book search engine that offers various functionalities for both guests and registered users. Upon visiting the site, users are greeted with a simple menu offering options to "Search for Books" and "Login/Signup", along with an input field for searching books and a submit button.

For unregistered or logged-out users, searching for books returns a list of results, each displaying a book's title, author, description, image, and a link to the book on the Google Books site. Users have the option to log in or sign up via a modal window, which toggles between login and signup forms. The signup form requires a username, email address, and password, while the login form requires just an email address and password.

Once registered and logged in, users gain additional features. The menu changes to include "Search for Books", "View Saved Books", and "Logout". Logged-in users can save books to their account for future reference. Each book in the search results includes a "Save" button for this purpose. The "View Saved Books" option displays all saved books, each with the option to "Remove" it from the account.

Logging out returns the user to the default view, with options to search for books or login/signup, ensuring a seamless and functional experience for both guests and registered users, with enhanced features for those who create an account.
```


## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Acceptance Criteria

```md
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
```

