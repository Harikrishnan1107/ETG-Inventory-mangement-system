# ETG-Inventory-mangement-system
This repository is having all the codes with json file for making an Inventory management system during ETG AI/ML Internship

## I have made an Inventory management system which will work on NOSQL database. 
1.I have use JSON file system of it
2.New item can be added to record file by first option
3.A Item can be removed in record file by second option 
4.The items inside record file can be removed using third option --->it will show the item name , price and quantity.
5.You can purchase a product.

## Files used: 
1.record.json --->This file contain all the items in the store with the id number , product name , quantity , price , expiry date ,manufacturing date.
2.record before changes.json ---> This file is same as the record file but this file is not used in the program so no changes are made in it.
3.customer.json --->In this file the customers details are saved with phone number as key and name and point as values.
4.sale.json --->this file is used to save the number of purchases done with the product name,product id,quantity customer purchased and total billing amount 
5.Elite_assignment1.ipynb --->it is the entier code file.

## Working Of Project: 
1.When the choice is given as 1 ---> A new product can be added to recoed file by giving id number,product name , quantity , price , expiry date ,manufacturing date.
2.When the choice is given as 2 ---> A product inside record file can be removed by giving only the product id.
3.When the choice is given as 3 ---> The entire products inside the record file can be shown with the product id , product name , quantity available and the product price
4.when the choice is given as 4 ---> In this it will ask you to enter the name,phone number,product id and product quantity. it will check for your enterd phone in customer file and if the phone number is there, the points for you will be increasd by the way of if you bought products for 10rs it will increase your points by 1 point. if the number is not there the new customer id will be created with your phone number as key then name and points as values , then the quantity you purchased will be reduced from the record file.The sale is saved with id as nth sale with values as product id ,product name,product quantity and billing amount.At the final the bill is printed by showing the details such as company name,welcome note,product id ,product name,product price,product quantity you puchased ,manufacturing date,Expiry date,billing amount as total amount to be paid,wallet point as your total points earned after all purchases,billing time and happy shoping note with customer name.

