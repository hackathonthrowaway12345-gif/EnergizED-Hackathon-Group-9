Requirements:
 - MySQL installed.
 - VS code or other code editing software installed
 - javascript enabled
 - node js installed together with 'npm'
 - open in browser html extension


You may need to run the following code if there is no package.json or no dependencies inside package.json
 - npm install mysql2
 - npm install dotenv
 - npm install cors
 - npm install express


Create a file named ".env"
File contents:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD="<replace_this_with_your_MySQL_password>"
DB_DATABASE="eg_hackaton"

 - 


Steps to run the server:
 1) Inside MySQL app, manually create a schema called "eg_hackaton"
 2) Inside VS code terminal, type "npm run init_tables" to create tables and put data into the MySQL database
 3) Inside VS code terminal, type "npm start" to start the server.
 4) Open the HTML page.
 5) To stop the server, press "control C" inside the terminal.