## Shopping Cart Challenge
Design and build a shopping cart that can calculate the results of an order. Use the provided menu.json and location.json to construct an interface that allows a user to select items to order and then submit that order. You will need to display all taxes and surcharges in a summary.

## Requirements
1. Selecting from a list of items based on the menu should include an image for the item, the name of the item and the price.
2. A user should be able to specify the quantity of an item before it is added to the cart.
3. The Summary of the order should include: the name of the item, the quantity chosen for that item, a subtotal, each additional charge (tax, surcharge) should be listed out seperately and the sum should be calculated at the very bottom.

## Example Summary
```
2 x Nachos @ $price
1 x Water @ $price
--------------------
$subtotal Subtotal
$sales_tax Sales Tax
$local_tax Local Tax
$surcharge Surcharge
--------------------
$total Total
```
## Submitting the Order
Assume that you are going to POST the results to an endpoint. Log out via the console what you would POST to a fake `/orders` endpoint

## Technical Requirements
* You can use any framework or build process that you desire

## Questions
Contact the proctor of your test if you have any questions or feedback about this challenge.


