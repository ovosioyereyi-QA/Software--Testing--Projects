# Login Test Cases

## TC001 - Verify successful login with valid credentials

**Preconditions**
- User account exists.
- User is on the login page.

**Test Data**
- Email: testuser@example.com
- Password: Password123

**Test Steps**
1. Open the login page.
2. Enter a valid email address.
3. Enter a valid password.
4. Click the Login button.

**Expected Result**
- User is successfully logged in.
- User is redirected to the dashboard.
- A welcome message or user profile is displayed.

---

## TC002 - Verify login fails with an invalid password

**Preconditions**
- User account exists.
- User is on the login page.

**Test Data**
- Email: testuser@example.com
- Password: WrongPassword123

**Test Steps**
1. Open the login page.
2. Enter a valid email address.
3. Enter an incorrect password.
4. Click the Login button.

**Expected Result**
- Login is unsuccessful.
- An appropriate error message is displayed.
- User remains on the login page.

---

## TC003 - Verify validation for empty email and password fields

**Preconditions**
- User is on the login page.

**Test Steps**
1. Leave the email field empty.
2. Leave the password field empty.
3. Click the Login button.

**Expected Result**
- Required field validation messages are displayed.
- Login is not attempted.
