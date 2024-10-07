README
CS 20 - Ezey Duru

Tasks
Your assignment is to create a web page to get an order for a new café in Medford called “Joe’s Hotdog Stand”.  Joe’s only sells three items: hotdogs ($4.80 each), French Fries ($3.95 each), and Drinks ($1.99 each).  Joe is swamped due to his delectable hotdogs and is hoping online orders will help to manage the flow better.

The page should do the following:
	Create constants to store the price of each item.
	Using prompt(), ask the user three questions- how many hotdogs do they want, how many fries do they want and how many sodas do they want.  When you get the values, store them in variables called numDogs, numFries, numSoda.
	Create a function called showMoney() that takes a floating point number as a parameter and returns a string that shows the number rounded to exactly 2 places.  You should use an arithmetic calculation to do this – you may not use any built-in Javascript functions that do formatting such as format() or toFixed().
For example, 
      $2.5    	should return 2.50
      $2.588  	should return 2.59
      $2.582  	should return 2.58

	Calculate the subtotal for the order based on the pricing and the quantities requested. Store in a variable.
	Implement Joe’s special offer - 10% discount if the order (before tax) is at least $25.  Store the discount amount in a variable. Update the subtotal.  
	Add 6.25% Massachusetts meals tax to the new subtotal (after any discount is calculated).  This is the final amount the customer will need to pay.
 

Display all order information below on the page:  
•	quantity of each item ordered and the total cost for that item
•	subtotal before discount
•	discount, if applicable
•	subtotal after discount
•	tax amount
•	final total 

	All currency values must be rounded to exactly 2 decimal places.  Use showMoney() to help with this.

For example, 
      $2.5    	should display as $2.50
      $2.588  	should display as $2.59
      $2.582  	should display as $2.58
You may not use the library function, toFixed() for this assignment. 
![image](https://github.com/user-attachments/assets/ba3d1e3f-187d-499a-9196-305f180049fd)
