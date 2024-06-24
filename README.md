# Project-3-QA-REPORT


 ## Notes ##
 
 TESTING (saucedemo.com)
 
FEATURES:-
 - Login page	 	{No SQL Injection Found}
   - username (Field) 	{Various Roles}
   - password (field) 	{Testing standard_user}

 - Inventory Page (https://www.saucedemo.com/inventory.html)
   - (Hamburger, Cart, Filter {Name (A to Z) })


 - Products Catalog
   - Add to cart (Button)
   - Back to products (Link)

 - Socal Links           {All links are working}
   - Twitter (Outdated LOGO)
   - facebook
   - linkedin

 - Item not Found Page (https://www.saucedemo.com/inventory-item.html?id=6)

 - Cart Page (https://www.saucedemo.com/cart.html)
   - Continue Shopping (Button)
   - Checkout (Button)


 - Checkout Step 1 Page (https://www.saucedemo.com/checkout-step-one.html)
   - First Name (Text Field)
   - Last Name  (Text Field)
   - Zip/Postal (Text Field)


 - Checkout Step 2 Page (https://www.saucedemo.com/checkout-step-two.html)
   - Cancel (Button)
   - Finish (Button)


 - Checkout Complete Page (https://www.saucedemo.com/checkout-complete.html)
   - Green Tick (ICON)
   - Back Home (Button)



PARAMETERS :- 
 
   - ?id=0-5 ONLY (seen on https://www.saucedemo.com/inventory-item.html?id=4)
                        {No SQL injection Found}



BUGS:-
 [-] Cart Button Arrow Not changing on Hover (STATIC)
 [-] Can't specify quantity in product
 [-] Filter Drop Down icon not working
 [-] Session Expiring Too Soon
 [-] Add to cart button is there on ITEM NOT FOUND page by clicking this button cart is updating and while opening the cart Page get's CRASHED (White page)
 [-] User Can Perfor Checkout Without Adding Anything in Cart
 [-] User can add any number in Zip/Postal Code Site doesn't verify correct Zip code
 [-] Remove Button not resetting after Clicking on Reset App State
 [-] There's no link in Terms of Serivce And Privacy Policy (STATIC)

