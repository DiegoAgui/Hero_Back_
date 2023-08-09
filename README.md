# Introduction to Express.js

<img src="img/programate-academy.png" alt="Logo Programate">

## Objective

We are going to develop an API connected to mongoDB, to complement the [Angular](https://angular.io/tutorial/tour-of-heroes) tutorial and to be able to have a fullstack project using the MEAN stack

## First Steps

Remember you must have [Node.js](https://nodejs.org/en/download) installed, then create and enter the folder where you are going to save the project. Once you clone the repository remember to enter the folder with
```
cd node-basic-c9
```
and install the packages using the command:
```
npm install
```

## Run the server

To start the server we are going to run the following command in a console at the index.js level
```
node index.js
```
## Documentation de MongoDB

They're going to create the account, this is the recommended documentation for MongoDB, although you can find more online.

* [Quick Start](https://www.mongodb.com/docs/drivers/node/current/quick-start/#quick-start) 
* [Download and Install](https://www.mongodb.com/docs/drivers/node/current/quick-start/download-and-install/)

* [Create a MongoDB Deployment](https://www.mongodb.com/docs/drivers/node/current/quick-start/create-a-deployment/)

* [Create a Connection String](https://www.mongodb.com/docs/drivers/node/current/quick-start/create-a-connection-string/#create-a-connection-string)
* [Connect to MongoDB](https://www.mongodb.com/docs/drivers/node/current/quick-start/connect-to-mongodb/)

* [Express Tutorial Part 3: Using a Database (with Mongoose)]c

## Enviroments Variables

Environment variables are values ​​that are set in the operating system and can be accessed by applications at run time. In Node.js, you can access these variables through the 'dotenv' object..


1. Create an .env file in the root directory of your project.

2. Inside the .env, define your environment variables for example:

```
MONGO_DB_URI = `12lkjefoaih1209`
```
## Endpoints available

Finally we test the enpoints:

#### Postman Get Authors
```
localhost:3005/api/hero/
```
#### Get Hero For Id
```
localhost:3005/api/hero/:id
```

#### Get Hero For Id
```
localhost:3005/api/hero/:id
```
#### Update Hero
Verbo patch
```
localhost:3005/api/hero/update/:id
```
with the following scheme of json
```
{
    "first_name:"Capitan Python",
    "faction":"Python",
    "hp":50,
}
```

#### Create Hero
```
loclahost:3005/api/hero/create/:id
```
with the following scheme of json
```
{
    "first_name:"Capitan Python",
    "faction":"Python",
    "hp":50,
}
```
#### Delete Hero
```
loclahost:3005/api/hero/delete/:id
```



## Contact

If you have any questions, suggestions or want to obtain the workbook to develop this project, do not hesitate to contact me through: [diego.aguirre.9805@gmail.com](diego.aguirre.9805@gmail.com).

# node-basic-c9
# node-super-hero
