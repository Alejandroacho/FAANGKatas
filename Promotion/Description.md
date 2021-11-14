# Promotion List Kata

### Description

A FAANG company that owns a shopping service wants to apply random discounts accodring to the shopping list of the customer. To do that, a list of rewarded products will be generated every day. 

* The customers list of product will have to match the rewarded list of products.
* If "anything" is in the rewarded product list, a match will be any kind of product but it can't be empty.

You must write a function that receives 2 parameters (a list of lists with promotional products, and the customer shopping list) and returns 1 if the shopping list is eligible to apply a discount or 0 if not.

### Example

Parameter 1 : [ [ "banana", "orange" ], [ "strawberry", "apple", "banana" ], [ "anything", "apple" ] ]

Parameter 2 : [ "banana", "orange", "apple", "strawberry", "mango", "apple", "banana", "melon", "apple", "apple" ]

Expected return : 1

Explanation : The customers shopping list follows the order of the rewarded items in the list of lists. Between 2 rewarded items, there can be any other product/s and when "anything" appears, there's actually an item.
