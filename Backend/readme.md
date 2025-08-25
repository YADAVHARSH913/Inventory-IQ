## Stock Management System 

The Stock Management System is a web app that helps track and manage inventory. Its backend provides a RESTful API to handle stock operations like managing brands, purchases, and items. Users can add, update, delete, and search stock, as well as filter items by category or supplier. The system also has user authentication with role-based permissions.

## Tech/framework used
**Express.js**
**MongoDB**
**Token-based Authentication**
**Dotenv**
**CRUD Operations**


## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/esmaaksoy/Stock-Management-System-Backend
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Create .env file in home directory.
   ```sh
   HOST=localhost
   PORT=8000
   MONGODB=ENTER YOUR Database adres or local: mongodb://127.0.0.1:27017/stockApi
   SECRET_KEY=ENTER YOUR random letters and number, for example: jsl78dd9ff6f6s9jkd89Kkfnfd
   ACCESS_KEY=ENTER YOUR random letters and number, for example: jsl78dd9ff6f6s9jkd89Kkfnfd
   REFRESH_KEY=ENTER YOUR random letters and number, for example: jsl78dd9ff6f6s9jkd89Kkfnfd
   PAGE_SIZE=25

   ```
4. Logs File
   ```sh
   You can write:
   mkdir logs
   ```
5. The project is ready, you can start using it now.
   ```sh
   You can run:
   nodemon
   ```

### IMPORTANT NOTES ! 

To use the application, you can log in with the following email and password <br>
email: admin@site.com <br>
password: aA?123456 <br>


