## Test Execution Details

| TC ID | Test Case | Expected Result | Actual Result | Status | Remarks |
|------|-----------|-----------------|---------------|:------:|---------|
| TC001 | Verify login with valid credentials | User logs in successfully | User logged in successfully and redirected to dashboard | ✅ Pass | Working as expected |
| TC002 | Verify login with invalid password | Error message displayed | Error message displayed | ✅ Pass | Validation working correctly |
| TC003 | Verify login with invalid email | Error message displayed | Error message displayed | ✅ Pass | Working correctly |
| TC004 | Verify login with blank email | Validation message displayed | Validation message displayed | ✅ Pass | Working correctly |
| TC005 | Verify login with blank password | Validation message displayed | Validation message displayed | ✅ Pass | Working correctly |
| TC006 | Verify login with both fields blank | Required field messages displayed | Validation messages displayed | ✅ Pass | Working correctly |
| TC007 | Verify password is masked | Password should not be visible | Password field displayed entered characters instead of masking them | ❌ Fail | Security issue observed |
| TC008 | Verify Remember Me checkbox | User session is remembered | User session was not retained after browser restart | ❌ Fail | Functionality not working |
| TC009 | Verify Forgot Password link | Password recovery page opens | Password recovery page opened successfully | ✅ Pass | Working correctly |
| TC010 | Verify Logout functionality | User is logged out successfully | User logged out successfully | ✅ Pass | Working correctly |
