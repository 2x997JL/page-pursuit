## Description
This is a book search engine that allows users to search for books, create an account, save books to their account, and manage their saved books. The search engine integrates with the Google Books API to retrieve book information.

## Installation
To install and run the book search engine locally, follow these steps:
    npm install
    Create a .env file in the root directory and provide the following environment variables:
MONGO_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>

    Start the application:
    npm start
    The book search engine will be accessible at http://localhost:3001 in your web browser.

## Usage
1. When you load the search engine, you will be presented with a menu that includes options to search for books and login/signup. You can enter a search term in the input field and click the submit button to search for books.

2. If you click on the "Search for Books" menu option, you will be directed to a page with an input field and a submit button to search for books.

3. If you are not logged in and enter a search term in the input field and click the submit button, you will see several search results with book details such as the title, author, description, image, and a link to that book on the Google Books site.

4. By clicking on the "Login/Signup" menu option, a modal will appear on the screen with a toggle between the options to log in or sign up.

5. If you select the "Signup" option in the modal, you will be presented with three input fields for a username, an email address, and a password, along with a signup button. Fill in the required information and click the signup button to create your account.

6. If you select the "Login" option in the modal, you will be presented with two input fields for an email address and a password, along with a login button. Enter your credentials and click the login button to access your account.

7. After logging in, the menu options will change to "Search for Books," "Saved Books," and "Logout." You can use the input field and submit button to search for books while being logged in.

8. When you search for books and receive the search results, each result will display the book's title, author, description, image, and a link to the book on the Google Books site. You can click the "Save" button on a book to add it to your saved books list.

9. Clicking on the "Saved Books" option in the menu will present you with all the books you have saved to your account. Each saved book will include the title, author, description, image, and a link to the book on the Google Books site. You can also remove a book from your saved books list by clicking the "Remove" button.

10. To log out, click on the "Logout" option in the menu. You will be logged out of the site and redirected to the initial page with the search engine menu.

## License
This project is licensed under the MIT License.