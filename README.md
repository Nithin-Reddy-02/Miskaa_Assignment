# Miskaa_Assignment
RESTful api for shopping where you can add/delete your product and order any product after authorization.
## DESCRIPTION
- Built a REST Api in Node.js using Node.js + MongoDB.
- JWT for Authetication and Authorization.
- Experss Sessions for cart
## INSTALLATION INSTRUCTIONS
 - Clone or download the repo. into your local system.

 - Cd into that root folder you just cloned locally.

 - install all dependencies which are written in the packet.json file, type
```
npm install
```
 - Now typing
```
npm start
```
will start a server !

App should now be running on localhost:3000

## Dependencies
For dependencies refer Package.json
## For Testing (Postman)
Postman extension can be used for testing !

# Available API Routes

## User Routes

| Routes | Description |
| ------ | ----------- |
| `POST/user/signup` | Sign up a new user |
| `POST/user/login` | Login the user with Email and Password |

## Products Routes

| Routes | Description |
| ------ | ----------- |
| `GET/products/` | Get list of all products |

## Cart Routes

| Routes | Description |
| ------ | ----------- |
| `POST/add/:product` | Add Products to the cart |
| `POST/update/:product` | Update the products in the cart such as increase quantity, decrease quntity etc. |
| `POST/clear` | Clear the items in the cart |

