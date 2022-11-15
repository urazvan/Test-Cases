# Test Case Samples

###### In this repository I have some Test Case samples that I wrote while working on my previous projects.

________________________________________________________________________________________________________

**Description:**
Test the login by using wrong credentials.

**Steps to reproduce**
1.	Go to site.com/login 
2.	Add wrong user/pass
3.	Observe if the page will give you a wrong user/pass error

**Expected result:**
User should get an error message saying that the user/pass is wrong.

**Test data:**
User: wronguser & Pass: 123456

___________________________________________________________________________________________________________

**Description:**
Test the login with no credentials.

**Steps to reproduce**
1.	Go to site.com/login 
2.	Don't add any credentials
3.	Observe if the page will give you a wrong user/pass error

**Expected result:**
User should get an error message saying that you need to enter a username and a password.

**Test data:**
No user and password

___________________________________________________________________________________________________________

**Description:**
Test the Remember me checkbox by closing the page and opening it again.

**Steps to reproduce**
1.	Go to site.com/login
2.	Add correct user/pass
3.	Check the "Remember me" option
4.	Observe if user can login
5.	Close the page
6.	Open the page again
7.	Observe if the user credentials are pre-filled

**Expected result:**
User login details should be saved and filled in automatically.

**Test data:**
User: test & pass: 123456

___________________________________________________________________________________________________________

**Description:**
Test the Stay Signed in checkbox by closing the page and opening it again.

**Steps to reproduce**
1.	Go to site.com/login
2.	Add correct user/pass
3.	Check the "Stay signed in" option
4.	Observe if user can login
5.	Close the page
6.	Open the page again
7.	Observe if the user is logged in

**Expected result:**
User should be logged in when opening the page again.

**Test data:**
User: test & pass: 123456

___________________________________________________________________________________________________________

**Description:**
Check if forgot password functionality works as expected and an email with reset password link is sent.

**Steps to reproduce**
1.	Go to site.com/login
2.	Press “Forgot password” button
3.	Add an email address
4.	Press “Recover my password” button

**Expected result:**
User should receive an email with a reset password link. The link should allow the user to create a new password.

**Test data:**
User: test@yahoo.com

___________________________________________________________________________________________________________

**Description:**
Test the Search bar by searching a product.

**Steps to reproduce**
1. Go to site.com
2. Type "HP Laptop" in the search bar
3. Observe if the search will give you the right products

**Expected result:**
User should be able to search a product and get the correct results for correct keywords.

**Test data:**
Product: HP Laptop
