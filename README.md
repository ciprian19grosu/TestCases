# TestCases
--------

**Test design for Cart Page**
---------
## Visual
---------
- verify that the correct products ( photo, price, quantity, total) are displayed on the page 
- verify that all the buttons are displayed in the right place
---------
## Valid
--------
- verify the QUANTITY field(s) are working by changing the value ( typing or using +,-)
- verify the UPDATE SHOPPING CART button
- verify the TOTAL, CART TOTALS, Cart Icon values 
- verify the "Remove this item" button
- verify the CONTINUE SHOPPING button
- verify the APPLY COUPON button
- verify the PROCEED TO CHECKOUT button
- verify the CLEAR SHOPPING CART button

## Invalid

- verify with a big quantity
- verify with an invalid coupon code


## **Test cases**
 
1. TITLE: CART PAGE visual verification&validation
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
   STEPS: the user sees all the products, buttons, fields
EXPECTED RESULTS: all the products, buttons, fields are right

2.
           TITLE: product's picture on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on the product's picture
EXPECTED RESULTS: product's page is displayed

3.
           TITLE: product's name on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on the product's name
EXPECTED RESULTS: product's page is displayed

4.
           TITLE: modify the QUANTITY field by typing in CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on the product's quantity and types the new quantity
                  the user clicks on UPDATE SHOPPING CART
EXPECTED RESULTS: product's QUANTITY, TOTAL, CART TOTALS fields are updated with the right values 

5.
           TITLE: modify the QUANTITY field by clicking + & - in CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on the product's quantity and clicks on +
                  the user clicks on UPDATE SHOPPING CART
                  the user clicks on the product's quantity and clicks on -
                  the user clicks on UPDATE SHOPPING CART
EXPECTED RESULTS: product's QUANTITY, TOTAL, CART TOTALS fields are updated with the right values

6.
           TITLE: Remove this item button on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on "Remove this item" button of one product
EXPECTED RESULTS: the CART PAGE is reloaded, the product is removed, CART TOTALS, Cart Icon is updated and a message(undo) is displayed

7.
           TITLE: CONTINUE SHOPPING button on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on CONTINUE SHOPPING button
EXPECTED RESULTS: products page is displayed

8.
           TITLE: APPLY COUPON button on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user types a valid cupon code in the field
                  the user clicks on APPLY COUPON button
EXPECTED RESULTS: a discount is made and CART TOTALS is updated

9.
           TITLE: PROCEED TO CHECKOUT button on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on PROCEED TO CHECKOUT button
EXPECTED RESULTS: the checkout page is displayed


10.
           TITLE: CLEAR SHOPPING CART button on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on CLEAR SHOPPING CART button
EXPECTED RESULTS: all the products are removed 

11.
           TITLE: QUANTITY field by typing a large number in CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user clicks on the product's quantity and types a 20 digits number
                  the user clicks on UPDATE SHOPPING CART
EXPECTED RESULTS: an error message is displayed

12.
           TITLE: APPLY COUPON button with an invalid coupon code on CART PAGE 
   PRECONDITIONS: random products are added to the CART
                  CART PAGE is open  
           STEPS: the user types a invalid cupon code in the field
                  the user clicks on APPLY COUPON button
EXPECTED RESULTS: an error message is displayed
