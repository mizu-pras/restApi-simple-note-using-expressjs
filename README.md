# restApi-simple-note-using-expressjs


## To get the Node server running locally:

 * Clone this repo
 * ```cd restApi-simple-note-using-expressjs```
 * ```npm install```
 * set up file .env and database
 * start your mysql server
 * ```npm start``` 
 
## To setup .env and database

 * make file ```.env``` 
 * you can imitate ```.env-semple```
 * create database  
 
 #### set variables for database connection at ```.env```
 
 ```
 DB_HOST=your-host-mysql
 DB_USER=your-user-mysql
 DB_PASS=your-password-mysql
 DB_NAME=your-databse-name
 DB_DIALECT='mysql'

 ```

 * ```sequelize db:migrate```
 
 import dump data from ```./dumping-data.sql``` to your database

## To test request API

 * open postman
 * import from ```./test``` to your postman
 * test request
