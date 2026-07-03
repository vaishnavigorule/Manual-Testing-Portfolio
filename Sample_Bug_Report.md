# 🐞 Bug Report 1

| Field | Details |
|--------|---------|
| Bug ID | BUG-001 |
| Title | Password is displayed in plain text instead of being masked |
| Module | Login |
| Reported By | Vaishnavi Gorule |
| Reported Date | DD/MM/YYYY |
| Severity | High |
| Priority | High |
| Status | Open |
| Environment | Windows 11, Google Chrome 138 |

## Description
The password field displays the entered password in plain text instead of masking it with dots or asterisks.

## Preconditions
- User is on the Login page.

## Steps to Reproduce
1. Open the Login page.
2. Click on the Password field.
3. Enter any password.

## Expected Result
The password should be masked (e.g., ●●●●●●).

## Actual Result
The password is visible as plain text.

## Impact
This exposes sensitive user information and poses a security risk.



# 🐞 Bug Report 2

| Field | Details |
|--------|---------|
| Bug ID | BUG-002 |
| Title | Remember Me functionality does not retain user session |
| Module | Login |
| Reported By | Vaishnavi Gorule |
| Reported Date | DD/MM/YYYY |
| Severity | Medium |
| Priority | Medium |
| Status | Open |
| Environment | Windows 11, Google Chrome 138 |

## Description
The "Remember Me" checkbox does not keep the user logged in after closing and reopening the browser.

## Preconditions
- User has valid login credentials.

## Steps to Reproduce
1. Open the Login page.
2. Enter valid username and password.
3. Select the **Remember Me** checkbox.
4. Click **Login**.
5. Close the browser.
6. Reopen the browser and navigate to the application.

## Expected Result
The user should remain logged in without entering credentials again.

## Actual Result
The user is redirected to the Login page and must log in again.

## Impact
The feature does not work as expected, reducing user convenience.

## Attachment
Screenshot (if available)
