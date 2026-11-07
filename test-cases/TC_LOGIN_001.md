# Test Case: TC_LOGIN_001

**Module:** Login

**Test Scenario:** Verify login using valid credentials

**Preconditions:**
- The SauceDemo login page is accessible.
- A valid test account is available.

**Test Data:**
- Username: standard_user
- Password: secret_sauce

**Test Steps:**
1. Open https://www.saucedemo.com/.
2. Enter `standard_user` in the username field.
3. Enter `secret_sauce` in the password field.
4. Click the Login button.

**Expected Result:**
The user should successfully log in and be redirected to the products page.

**Actual Result:** User successfully logged in with valid credentials and was redirected to the Products page (`/inventory.html`).

**Status:** Pass
