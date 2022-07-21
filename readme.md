# Bug Reports

Here are some of the bugs I found on the sites I use.

---

### BUG REPORT 1 
**Title:**
The responsive test doesn’t work for the mobile version

**Description:**
When “Alege marimea” button was selected, the site isn’t responsive for the mobile device.

![Bug Report 1 - Image 1](/images/bug_report_1_ss1.png)

![Bug Report 1 - Image 2](/images/bug_report_1_ss2.png)

**Steps to reproduce**
1. Go to https://www.epantofi.ro/
2. Open Developer Tools
3. Select one or two devices for testing (Android, iOS)
4. Click on a random item
5. On the product page click “Alege marimea”

**Expected result:**
The result should appear in a mobile format.

**Actual result:**
The site isn’t responsive for a mobile device when “Alege marimea” option was clicked.
The content of the page isn’t aligned correctly. The page has horizontal scroll.


## BUG REPORT 2 
**Title:**
“Remove button” should exist from sold-out products

**Description:**
If exist in the shopping cart a sold out product, it doesn’t have the possibility to be removed.

![Bug Report 1 - Image 1](/images/bug_report_2_ss1.png)

**Steps to reproduce:**
1. Go to https://www.cropp.com/ro/ro/
2. Add a product to the shopping cart
3. Go to the shopping cart

**Expected result:**
The “sold out” product should be able to remove from the shopping cart.

**Actual result:**
There is no “remove button” from sold-out products (it’s not a blocker)


### BUG REPORT 3
**Title:**
Character limit

**Description:**
The character limit for address validation is too small.

![Bug Report 3 - Image 1](/images/bug_report_3_ss1.png)

**Steps to reproduce:**
1. Go to https://www.cropp.com/ro/ro/
2. Go to the shopping cart
3. Click to “Finalizeaza comanda” button
4. Go to “Date de facturare” section and click to “Modifica” button
5. Try to add a long billing address

**Expected results:**
1. The limit should be increased.
2. Actual results
3. A long billing address can’t be added (character limit: 40).