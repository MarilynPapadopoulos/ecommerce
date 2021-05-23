# E-commerce Back End

## Description 
This app allows the user, an e-commerce store, to control their product inventory.  They have the ability to see the existing products as well as add new product inventory including details such as price, category and quantity.  The user has the ability to delete products.  They can also add/delete and update the different categories.  The tagging system is integrated whereby the tags are in sync with the aforementioned operations.  
This app can run in Insomnia.  One of the challenges is that the sequelize.sync needs to be set to false and the server restarted after various changes to maintain up-to-date operation.  Then, the database needs to be reseeded and run in Insomnia.  

## Installation
This app uses:
* Express.js
* MySql2
* Sequelize

## Usage 
To run this app: 
1. npm run seed
2. npm start

Here is a demo in Insomnia: 

[GET all](https://drive.google.com/file/d/1K4enWk4TmrIQoNTEvQNFC6kXPzghBseR/view)

[GET by id](https://drive.google.com/file/d/15eCTyAYZpr5Kq_-4L8RYGCE-rhN1vjBa/view)

[Categories PUT, POST, DELETE](https://drive.google.com/file/d/1NPRBNbyOZLN-XiHWNClXMlwauVDNY4Hx/view)


