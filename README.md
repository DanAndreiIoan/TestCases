# Test Cases

------------------------------------
**Description :**
Check if the login works when a person uses a corect user/password.

**Steps to reproduce :**
1. Go to www.website.com/login
2. Add a correct user/password
3. Press Login button

**Expected rezult :**

User should be able to login and is taken to his page.

**Test data :**

User : radu
Pass : 123456


------------------------------------
**Description :**

Check if the login does not works when a person uses a  incorrect user/password.

**Steps to reproduce :**
1. Go to www.website.com/login
2. Add a incorrect user/password
3. Press Login button

**Expected rezult :**

The user cannot login and a warning message is displayed, “The username or password is incorrect”.

**Test data :**

User : eerr
Pass : @3455t5t


------------------------------------
**Description :**

Check if the login works when a person uses a corect user/password and the data remains saved for a certain period of time.

**Steps to reproduce :**
1. Go to www.website.com/login
2. Add a correct user/password
3 .Check Remember Me field
4. Press Login button
5. Close curent page
6. Go to www.website.com

**Expected rezult :**

After closing the page and re-entering the desired site, he did not have to log in.

**Test data :**

User : andrei
Password : 123456


------------------------------------
**Description :**

Check if the login works when a person uses a SQL insection on user and password

**Steps to reproduce :**

1. Go to www.website.com/login
2. Add a SQL on user/password
3. Press Login button

**Expected rezult :**

The user cannot log in and a warning message is displayed, “The username or password is incorrect”.


**Test data :**

User : " or ""=" 
Password : " or ""=" 


------------------------------------
**Description :**

Check if the latest product searches are displayed

**Steps to reproduce :**
1. Go to www.emag.ro
2. Click on search field
    
**Expected rezult:**

After clicking Search field - search history should be displayed latest search
