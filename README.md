# Block18Workshop-WritingTestSpecifications

Key: 
Q: Question/Prompt; 
A: Answer; 
T: Test Specs;

1) Unit Tests:
Q. Prompt: 
- A function called "multiplication" that returns the product of the two input numbers.
- Expect [action] to be [some result]
A. 
Expect multiplication(num1,num2) to be a number;
Expect multiplication(num1,num2) to return/output the total/product of the 2 input numbers;
Expect multiplication(num1, num2) to accept two numerical arguments; an error will occur if NaN;

T. 
1. when a user inputs a non-numerical value, they should be prompted to enter a valid number
2. when a user inputs more than two arguments of a number, they should be shown an error and prompted to enter only 2 numbers to pass
3. when  a user enters numerical values correctly, they should be given the product of the function 



Q. Prompt:
- a function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]
A. 
Expect concatOdds(arr1,arr2) to accept 2 arrays[] of integers as arguments
Expect concatOdds(arr1,arr2) to filter out non-odd numbers
Expect concatOdds(arr1,arr2) to remove duplicates
Expect concatOdds(arr1,arr2) to sort a single array that contains odd numbers in ascending orders

T.
1. when a user inputs arguments that aren't arrays, they should be prompted to enter two arrays to pass
2. when a user is missing syntax like a [], they should be shown an error for a valid array
3. when a user enters more than 2 arguments of arrays, they should be shown an error and prompted to enter only two
4. when a user enters decimals, they should be shown an error and prompted to enter an integer/whole number.


2) Functional Tests
Q. Prompt: 
- Write in a more natural langauge
A. 
-the user will be able to click the checkout section where a list of their items will show in their shopping cart
-the feature will allow the user to checkout and be prompted to checkout as a guest or a logged in user
-if user clicks as a guest, they should be prompted with the option to create an account or continue without
-if user continues as a guest, they should be taken to the payment page to fill out their shipping and payment info
-if user clicks to log in as a user, they will be prompted to fill out their username and prompted before they are directed to the shipping and payment page
- after filling out their shipping and payement info, the user will be able to submit to complete purchase!
- the user should to be taken to their confirmation page and/or receive an email of confirmation

T.
1. if the user's cart is empty, they should be taken to the shopping site's home page
2. if the user's cart could qualify for free shipping, they should be prompted to buy a certain amount remaining to qualify for free shipping
3. if the user clicks to sign in as a user without filling info, they should be shown as error and prompted to create an account
4. if the user fills out info with invalid information, they should be shown an an error of either the username or password being invalid; ex: if the email does not have @ symbol to complete
5. if the user is directed to the shipping and payment page, they should be prompted with options to fill our manually or link other payment methods 


