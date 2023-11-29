# block18.test-specs

Unit Tests:
A function called "multiplication" that returns the product of the two input numbers.

## Unit Tests
### Multiplication Function
a declared function called Multiplication is expected to:
- have two parameters, x & y
- the parameters should take numbers as arguments
- the output should be a number
- the output should be the product of the two arguments (x * y)

  - If user fails to input two arguments, Multiplication should return NaN
  - if user inputs more than two arguments, Multiplication should return only the product of the first two arguments, and ignore any beyond that
  - if user enters a data type that isn't a number, it should return NaN


### ConcatOdds function
a declared function named concatOdds is expected to:
- have two parameters (arr1, arr2)
- take two arrays of integers (numbers) as arguments
- it should concatenate the arrays
- it should filter for odd numbers
- It should return a single array of integers, all of which are odd
- the integers in the new array should be in ascending numerical order

  - if user inputs a single array, it will return undefined for the missing argument
  - if more than two arguments are given, it will only return for the first two
 
  
## Function Test
A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:
What should happen if the cart is empty?
What needs to be shown to the user at each step of check out?
What behaviors of this feature does the prompt miss or gloss over?

- If the users cart is empty, checkout should not be an available option eg a checkout button should be inactive
- Many sites have a quick link icon to the cart, if the cart is empty it should just show the icon which brings you to an empty cart
- if the cart has items, it should show the number of items superimposed on the cart
- when the cart is accessed, it should show each item as a link to the full page of that item, with it's individual price, the total units of that item in the cart, and the total price for that amount.
- the cart should have the ability to modify the count/delete each item
- the cart should have the ability to clear all items
- The cart should have a subtotal of all items being purchased
- Cart should have a link to checkout
- checkout will give full details on total, shipping cost, and time expectations.
- It will have fields that are either pre-filled out, or need to be completed based on whether the user is checking out as a guest, or if they're logged into their account.
- fields will include name, shipping address, billing address, contact info, payment info.
- after user checks out, a page confirming that the order has been placed, and a confirmation number and reiteration of charges should appear
