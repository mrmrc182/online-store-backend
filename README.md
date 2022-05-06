## online-store-backend

# Description
This application is backend data for an ecommerce store's server.  There are routes where categories, products, and tags in the store are able to be created, retrieved, updated, and deleted.

# Contributors
I wrote the code but received help from my classmate Sam, TA Michael, instructor John, and several BCS tutors.

# Usage
In order to use this app, you will need Node, NPM, Sequelize, MySQL, and Insomnia.  

# Testing
To test the app, first open a terminal and copy the ```.env.EXAMPLE``` file as a ```.env```, then place your MySQL information in it.  Then run the ```npm-i``` command if you haven't already.  Then, in the terminal type ```mysql -u root -p <db/schema.sql``` and then ```npm run seed``` to set up and seed the database.

Then you will type ```npm start```.  This will start the server, and you can then view the various requests via Insomnia.

[Refer to this video if you are having challenges]()

I have also attached a screenshot below for what the requests in Insomnia should look like.

# License
Matt Carlson Code 2022