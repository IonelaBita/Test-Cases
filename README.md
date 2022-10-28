# Test-Cases
Below are some sample Test Cases that I wrote while doing the course at Wantsome School


--------------------

**Title**

Validate sorting filters are shown alphabetically

**Precondition:** 

Access www.wantsomeshop.ro

**Test Steps**

1. Select a category
2. Click on sorting button

**Expected Result**
Drop-down menu sorted alphabetically should appear.


--------------------


**Title**

Check if quantity updates when adding to cart

**Description**

Check when adding to cart a product multiple times Cart section updates with the corresponding quantity.

**Test Steps**

1. Add to cart multiple times from Add to cart button of the product grid.

**Expected Result**

Quantity from Cart section is updating instantly with every click.

--------------------

**Title**

Test if the "IULIE2021" voucher can be applied to the cart

**Preconditions:**

- a user is logged in
- at least a product is added to the cart
- a "IULIE2021" voucher is still available

**Test Steps**

1. Enter the cart page
2. Click on the Coupon Code section, enter the coupon code and press the button "Apply coupon"

**Expected Result:**

Discount should be applied to the total price of the cart.

**Test Data**

Cupon Code: Iulie2021


--------------------


**Title**

Check the quantity selection button without introducing a specific quantity

**Precondition**

Access www.wantsomeshop.ro

**Test Steps**

1. Click on product name selected from collection dispayed
2. Click on add to cart without clicking on quantity selection button

**Expected Result**

A message should be displayed and invite user/customer to select quantity.


--------------------


**Title**

Check the functionality of the quantity selection button

**Precondition**

Access www.wantsomeshop.ro

**Test Steps**
1. Click on product name selected from collection dispayed
2. Introduce special characters and letters in the box where appears the number of products selected

**Expected Result**
The box from quantity selection button should not list any changes in number of products and neither the price should be updated.

**Test Data:**

;&?





