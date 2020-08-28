# 14.Sequelize-Reverse-Engineering-Code

## PASSWORD AUTHENTICATION

This app allows users to create an account, log into the account and sign back out securely.  All user data is stored in a MySQL
database.

## USER STORY

As someone who wants to safely log in to a site, I want to know my personal details are safely stored so that I dont have to worry about using that site.

## ACCESSING THE APPLICATION

To access this app, clone this repo into your local storage.  Once cloned, complete the following items:

1) Open the config.js file and replace "null" with your personal password.  (Username may also need to be updated.)

2) Create a database in MySQLWorkbench called "passport_demo" under a local connection.

3) Open integrated terminal in current repo and run 'nmp install' to install the node packages designated by the package.json file.

4) While still in the integrated terminal, run 'node server.js' to open a connection to the server.

5) Open Chrome and type 'http://localhost:8080' in the search bar (Or, other port if changed.)

6) You can now use the application.