# Bamazon

Bamazon is a node application that simulates purchasing items from a website such as Amazon (duh). The main purpose of developing this application was to gain increased understanding of node.js and MySQL.

Bamazon posseses the following features:

  1. Displays items-for-sale for the customer
  2. Allows the user to select with item they would like to purchase by entering the product ID
  3. Allows the user to enter how many units they would like to purchase
  4. If the desired item has sufficient quantity, a total price is displayed. If there is insufficient quantity, the user is notified and they get another chance to enter a lower quantity

# Usage Example

The features outlined above are captured in the following screenshots, displayed sequentially.

![Displaying items to user](images/bamazon1.png)
![User selects item](images/bamazon2.png)
![User enters desired quantity](images/bamazon3.png)
![Total price is displayed](images/bamazon4.png)
![Insufficient quantity message is displayed. User gets to select a new quantity](images/bamazon5.png)

# Development Setup

```
npm i inquirer
npm i mysql

```