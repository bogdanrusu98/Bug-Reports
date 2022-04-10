# Bug Report Samples

Below are some Bug Report samples I wrote while working on previous projects.

---------------

**Priority & Severity:**
P4 - Medium

**Description:**
When trying to access https://www.demoblaze.com/index.html the navbar has a huge height on every smartphone.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/index.html
2. Press F12 (on desktop) to open Inspect Element3. Press toggle device toolbar and select any smartphone (or open page on a smartphone)

**Expected result:**
User should be able to see a normal height on nav-bar.

**Actual result:**
User has a huge height on nav-bar.


---------------

**Priority & Severity:**
P2 - Medium

**Description:**
When trying to access https://www.demoblaze.com/index.html with a width between 801px and 991px the navbar is hidden by products images.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/index.html
2. Press F12 (on desktop) to open Inspect Element
3. Use a width between 801px and 991px

**Expected result:**
User should be able to see the nav-bar.

**Actual result:**
User can’t see or use the nav-bar.


---------------

**Priority & Severity:**
P3 - Medium

**Description:**
When trying to access https://www.demoblaze.com/cart.html, the navbar is overlaying with the product list.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/cart.html
2. Press F12 (on desktop) to open Inspect Element
3. Press toggle device toolbar and select any smartphone (or open page on a smartphone)

**Expected result:**
User should be able to use the navbar buttons.

**Actual result:**
User can’t use and can’t see properly the navbar buttons.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
On the cart page https://www.demoblaze.com/cart.html, the footer should be on the bottom of the page, not of the div.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/cart.html 

**Expected result:**
User should see the footer on the bottom of the page.

**Actual result:**
User can see the footer on the bottom of the div.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
When I access the cart page, the items are on the same row with the “Total” text and “Place Order” button.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/index.html 

**Expected result:**
User should have a break line between the list and the total part.

**Actual result:**
User has not a break line between the list and the total part.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
When you access cart page, there’s no space on the left side and top side of product list.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/cart.html 

**Expected result:**
User should have a padding left and top on the product list.

**Actual result:**
User has not a padding left and top on the product list.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
When I access the cart page, the navbar buttons are centered.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/cart.html 

**Expected result:**
User should have the navbar buttons like in index page.

**Actual result:**
User has a different navbar buttons position.


---------------

**Priority & Severity:**
P4 - Medium

**Description:**
When I try to access a file that doesn’t exist I am not redirecting to a custom 404 page.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com
2. Enter the symbol “/” after the URL and write something random 
3. Press enter
4. See the 404 page 

**Expected result:**
User should have a custom 404 page.

**Actual result:**
User has not a custom 404 page.


---------------

**Priority & Severity:**
P3 - High

**Description:**
Once logged in, when I trying to access my profile account by pressing on my username nothing happens.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com/# 
2. Log in
3. Press click on your username

**Expected result:**
User should have a profile account when he can change his password, his username, etc.

**Actual result:**
User has not a profile account.


---------------

**Priority & Severity:**
P3 - High

**Description:**
You can add any credentials you want, letters, special symbols or numbers and any length on inputs and they still place the order.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com
2. Add any product to cart
3. Press “Place Order” button
4. Add at least one letter as credentials

**Expected result:**
User should add valid credentials in order to process the order.

**Actual result:**
User can add any credentials he want and yet can process the order.


---------------

**Priority & Severity:**
P2 - Medium

**Description:**
When trying to place an order, I have to add the credentials only on the “Name” and “Credit card” text-box to be able to process the order.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com
2. Add a product to cart
3. Go to cart page
4. Press “Process Order” button
5. Add credentials only on “Name” and “Credit card” text-box
6. Press “Purchase” button

**Expected result:**
User should get an error when he is trying to purchase the product without credentials.

**Actual result:**
User get no error when he is trying to purchase the product without credentials.


---------------

**Priority & Severity:**
P3 - Medium

**Description:**
If a add to cart a product and then I log in, the product from cart disappears.

**Steps to Reproduce:**
1. Go to https://www.demoblaze.com 
2. Add a product to cart without being logged in
3. Log in
4. Go to cart page
5. See how the product goes

**Expected result:**
User should have the products on the list after they are logged in.

**Actual result:**
The cart is empty after the user is logging in.


---------------

**Priority & Severity:**
P6 - Low

**Description:**
When you login as a customer, the “Withdraw” button is named “Withdrawl”

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Log in
3. See the button

**Expected result:**
User should see the third button named “Withdraw”.

**Actual result:**
User see the third button named “Withdrawl”.


---------------

**Priority & Severity:**
P4 - Medium

**Description:**
The “Amount” and “Transaction Type” sorting are not working.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Log in as a customer
3. Press click on the “Transactions” button
4. Press click on the “Amount” button or “Transaction Type”

**Expected result:**
User should be able to sort ascending or descending his transactions.

**Actual result:**
The buttons do nothing.


---------------

**Priority & Severity:**
P3 - High

**Description:**
If value of balance exceeds 21 characters then the balance is not showing correctly the amount.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Log in as a customer
3. Deposit a value with 21 characters or more
4. See the result on balance and in the “Transactions” page

**Expected result:**
User should be able to see his balance correctly.

**Actual result:**
User is able to see a part of his balance.


---------------

**Priority & Severity:**
P4 - Medium

**Description:**
The “Home” button is logging you out and redirecting to the login page.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Log in as a customer
3. Press click on the “Home” button

**Expected result:**
User should be redirect to his customer account.

**Actual result:**
User is redirecting to the login page.


---------------

**Priority & Severity:**
P1 - Critical

**Description:**
When you go to “Transactions” page and press click on the “Reset” button, the balance is reset too.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Log in as a customer
3. Press click on the “Transactions” button
4. Press click to the “Reset” button

**Expected result:**
User should be able to reset only his transactions.

**Actual result:**
User will get balance 0 after pressing the reset button. 


---------------

**Priority & Severity:**
P4 - High

**Description:**
On the bank manager account when trying to delete a customer account should get an alert for confirmation to avoid deleting accounts by accidentaly.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login 
2. Log in as a customer
3. Press click on the “Transactions” button
4. Press click to the “Reset” button

**Expected result:**
User should get an alert for confirmation when trying to delete an account.

**Actual result:**
User can delete accounts by pressing one click.


---------------

**Priority & Severity:**
P1 - Critical

**Description:**
You don’t need a password to login so anyone can access your account.

**Expected result:**
User should be able to login with credentials (including a password) to have access to his account (customer or bank manager).

**Actual result:**
Anyone can login to anyone’s account.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
Image icon appears when you add a value in the coffee input.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Add a value to coffee input
3. See the result

**Expected result:**
User should be able to see the image.

**Actual result:**
User can’t see the image.


---------------

**Priority & Severity:**
P4 - Medium

**Description:**
When you access a page that doesn’t exist you don’t have a 404 page so the user doesn’t know what happened.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Add in URL at the end “/” and then something random
3. Press enter

**Expected result:**
User should have an error 404 page with navbar to be announced that the page is trying to access is not valid.

**Actual result:**
User is redirecting to home page.


---------------

**Priority & Severity:**
P4 - Low

**Description:**
Footer should be at the bottom of the page and not next to the content.

**Expected result:**
Footer should be at the bottom of the page and not next to the content.

**Actual result:**
Footer is next to the content. 


---------------

**Priority & Severity:**
P5 - Low

**Description:**
When you add a value bigger than 2 on cigarettes input you will get an image who overlays on the coffee side.

**Steps to Reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/ 
2. Select cigarettes input
3. Add a value equal or bigger than 2
4. See the image

**Expected result:**
User should be able to see an image which is not overlaying.

**Actual result:**
The image should be under the line.


---------------

**Priority & Severity:**
P3 - High

**Description:**
P3 - High

**Expected result:**
User should be able to read the text on the page.

**Actual result:**
The text is too small and can’t be read.


---------------

**Priority & Severity:**
P3 - High

**Description:**
There is an extremely high loading page time.

**Steps to Reproduce:**
1. Go to https://www.primariatechirghiol.ro 
2. Press click right on the page
3. Press click on Inspect Element
4. Go to “Network”
5. Check the “Disable cache” and “Preserve log” inputs
6. Press CTRL + F5

**Expected result:**
Webpage should be loaded in maximum 3 seconds.

**Actual result:**
Very high loading page time.


---------------

**Priority & Severity:**
P3 - High

**Description:**
The text is not readable on mobile because is too small.

**Expected result:**
User should be able to read the text on the page.

**Actual result:**
The text is too small and can’t be read.


---------------

**Priority & Severity:**
P2 - High

**Description:**
Currently Bootstrap version does not support jQuery 4.x and showing an error in console “Uncaught Error: Bootstrap's JavaScript requires at least jQuery v1.9.1 but less than v4.0.0”

---------------

**Priority & Severity:**
P2 - Medium

**Description:**
Many broken links were found.
1.	https://www.primariatechirghiol.ro/formulare/arhitect-ef
2.	http://www.pensiunea-mareaneagra.ro/
3.	https://www.primariatechirghiol.ro/home/primaria/informatii-publice/formulare/alte-formulare/
4.	http://www.vilabellatechirghiol.ro/
5.	https://www.wetransfer.com/downloads/cbacdc1fcd0a56d5dc17ba76f0a0dacb20161010084658/38a9cec55d79988080ba3d1f0bb2018620161010084658/0b3930
6.	https://www.primariatechirghiol.ro/achizitii/achizitii-publice/publicatie-achizitie-combustibil-auto-pe-loturi-2/
7.	https://www.primariatechirghiol.ro/home/primaria/informatii-publice/anunturi-somatii/-Anunt colectiv privind comunicarea prin publicitate
8.	https://www.primariatechirghiol.ro/home/primaria/informatii-publice/hotarari-ale-consiliului-local/HCL 115 din 15 mai 2018 privind atribuire loc de veci
9.	https://www.primariatechirghiol.ro/achizitii/documentatii/caiet-de-sarcini-achizitie-combustibil-auto-pe-loturi-2/
10.	https://www.primariatechirghiol.ro/politia-locala/ ‎
11.	https://www.primariatechirghiol.ro/consiliul-local/sedintele-consiliului-local-al-orasului-techirghiol/
12.	https://www.primariatechirghiol.ro/primaria/directiile-primariei/compartiment-situatii-de-urgenta/

**Expected result:**
User should be able to access the links.

---------------

**Priority & Severity:**
P3 - Medium

**Description:**
When you try to change the language in english is redirecting to a page with broken links.

**Steps to Reproduce:**
1. Go to https://www.primariatechirghiol.ro 
2. On “Informatii Publice” side press on the Great Britain flag

**Expected result:**
User should be able to translate the text in english.

**Actual result:**
The button is redirecting you to a page with broken links.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
On the “Evenimente” side of the Home page there is no padding between the text and borders.

**Expected result:**
User should be able to see a space between text and borders.

**Actual result:**
There is no space between them.


---------------

**Priority & Severity:**
P5 - Low

**Description:**
There is no margins between buttons and the first row width is not equal with the second row.

**Expected result:**
User should be able to see a navbar with equal rows and margins between buttons.

**Actual result:**
There is no such thing.


---------------

