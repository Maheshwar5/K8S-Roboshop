### mongodb:
https://hub.docker.com/_/mongo

importance of "docker-entrypoint-initdb.d"?
MONGO_INITDB_DATABASE
This variable allows you to specify the name of a database to be used for creation scripts in /docker-entrypoint-initdb.d/*.js (see Initializing a fresh instance below). MongoDB is fundamentally designed for "create on first use", so if you do not insert data with your JavaScript files, then no database is created.


- we're copying catalogue.js. We've product catalogue   
  in catalogue.js
- If you search any ecommerce site, you'll find  
  plethora of products and that products and its information comes from database.Generally nosql database.

Also, we've user information in users.js

