# Test Case Samples


## **Test design for a random Cart Page of an ecomerce website**

### Visual

- verify that the correct products ( photo, price, quantity, total) are displayed on the page 
- verify that all the buttons are displayed in the right place

### Valid

- verify the QUANTITY field(s) are working by changing the value ( typing or using +,-)
- verify the UPDATE SHOPPING CART button
- verify the TOTAL, CART TOTALS, Cart Icon values 
- verify the "Remove this item" button
- verify the CONTINUE SHOPPING button
- verify the APPLY COUPON button
- verify the PROCEED TO CHECKOUT button
- verify the CLEAR SHOPPING CART button

### Invalid

- verify with a big quantity
- verify with an invalid coupon code


## **Test cases for CART PAGE**
 
#### TC1. 
**Title:** 
CART PAGE visual verification&validation

**Preconditions:** 
   1. random products are added to the CART
   2. CART PAGE is open  

**Steps:** 
the user sees all the products, buttons, fields

**Expected results:** 
all the products, buttons, fields are right


#### TC2.
**Title:** 
verify product's picture on CART PAGE 

**Preconditions:** 
   1. random products are added to the CART
   2. CART PAGE is open 

**Steps:** 
the user clicks on the product's picture

**Expected results:**
product's page is displayed

#### TC4.
**Title:** 
modify the QUANTITY field by typing on CART PAGE 

**Preconditions:** 
   1. random products are added to the CART
   2. CART PAGE is open  
**Steps:** 
   1. the user clicks on the product's quantity and types the new quantity
   2. the user clicks on UPDATE SHOPPING CART
**Expected results:** product's QUANTITY, TOTAL, CART TOTALS fields are updated with the right values 

#### TC5.
**Title:** modify the QUANTITY field by clicking + & - on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user clicks on the product's quantity and clicks on +
                  the user clicks on UPDATE SHOPPING CART
                  the user clicks on the product's quantity and clicks on -
                  the user clicks on UPDATE SHOPPING CART

**Expected results:** product's QUANTITY, TOTAL, CART TOTALS fields are updated with the right values

#### TC6.
**Title:** Remove this item button on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user clicks on "Remove this item" button of one product
**Expected results:** the CART PAGE is reloaded, the product is removed, CART TOTALS, Cart Icon is updated and a message(undo) is displayed

#### TC7.
**Title:** CONTINUE SHOPPING button on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user clicks on CONTINUE SHOPPING button
**Expected results:** products page is displayed

#### TC8.
**Title:** APPLY COUPON button on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user types a valid cupon code in the field
                  the user clicks on APPLY COUPON button
**Expected results:** a discount is made and CART TOTALS is updated

#### TC9.
**Title:** PROCEED TO CHECKOUT button on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user clicks on PROCEED TO CHECKOUT button
**Expected results:** the checkout page is displayed


#### TC10.
**Title:** CLEAR SHOPPING CART button on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user clicks on CLEAR SHOPPING CART button
**Expected results:** all the products are removed 

#### TC11.
**Title:** modify the QUANTITY field by typing a large number on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user clicks on the product's quantity and types a 20 digits number
                  the user clicks on UPDATE SHOPPING CART
**Expected results:** an error message is displayed

#### TC12.
**Title:** APPLY COUPON button with an invalid coupon code on CART PAGE 
**Preconditions:** random products are added to the CART
                  CART PAGE is open  
**Steps:** the user types a invalid cupon code in the field
                  the user clicks on APPLY COUPON button
**Expected results:** an error message is displayed
