# Foodie

[Foodie](shirley-wang.github.io) is a web application that allows customers to put a price on their food orders. Customers create orders by specifying a price, maximum wait time, and further options such as gluten free and vegan. After the order is created, restaurants will then respond back with  best offers for orders they want to fulfill. Once return offers are finalized by the restaurants, the customer receives notifications with all the different restaurant offers, including any other options the restaurants want to offer the customer. The customer may choose  which offer they would like to take, and then may proceed with the transaction.  The restaurant receives a final order, and after that the food will be delivered.


## Functionality

__Customers:__
* Customers may register a new account
* Customers may reset their password 
* Customers may change profile data after login
* Customers have two choices for getting food, either ordering customized item, or browsing menus by restaurant advertisements
* Customers may specify food type, price, wait time, gluten free, vegan information for customized order
* Customers will receive notification when an order was accepted by the restaurant
* Customers will be able to track the status of each confirmed order
* Any setting of the application can be edited under settings (address, payment information, etc.)
* Customers may add multiple payment types

__Restaurants:__
* Restaurants may register a new account
* Restaurants may submit an advertisement to Foodie
* Restaurants will receive notification when customer finalized order
* Restaurans may be able to access customer's information when an order is proceed
* Restaurants may add bank account information, tracking taxes, and receive payments twice a week

## Process of solving problems
This is the first version of this application. As of now, only the front-end customer side is implemented. 
There are five pages implemented for customers to sign up, log in, browse menu, make an order, and change profile.

## What I learned
I made this web application during HackISU hackathon, I learned Bootstrap grid system, AngularJS, and basic JavaScript syntax from my first web application.

* Bootstrap grid system
<br>
.container / .container-fluid
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
.row
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
.col-xs / .col-sm / .col-md / .col-lg
        
* AngularJS
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Angular data binding <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Angular directives <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
The Model View Controller Framework <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Angular Filters

## Future Revisions
__Customers:__
* Notification page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
customers may receive text message or email
* Setting page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
customers may be able to add payments method, change notification type, remember orders that will be placed often
* Finalized page<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
customers may track the orders that are on the way, and when it will be delivered
* Rating page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
customers could rate completed orders

__Restaurants:__
* Welcome page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
restaurants may see all the orders made by customers around a certain distance
* Setting page<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
restaurants may set price range of the orders, change banking account or any advertisement need to be turned in
* Revenue page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
restaurants may check the information of how much money they made, how much they spent, and how much taxes need to be paid
* Transaction page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
restaurants may monitor orders need to be delivered, instruction of where to deliver can be found in each order
* Profile page <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
restaurants would be able to change password, or restaurant type

__Backend:__
* Database of customers and business
* Database of orders made by customers<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
For this version, no database is implemented. The existing orders showing on the order page are the dummy data from Angular controller, 
which will be improved after further learning of Angular.

If you have any questions, please email Shirley at xuanli512@gmail.com
