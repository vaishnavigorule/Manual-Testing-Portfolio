# Test Summary Report

## Project Details

| Field | Details |
|--------|---------|
| Project Name | Sample Web Application |
| Module | Login Module |
| Test Cycle | Cycle 1 |
| Tester | Vaishnavi Gorule |
| Test Execution Date | 09/02/2026 |

---

# Test Execution Summary

| Metric | Count |
|--------|------:|
| Total Test Cases | 10 |
| Executed Test Cases | 10 |
| Passed | 8 |
| Failed | 2 |
| Blocked | 0 |
| Not Executed | 0 |
| Pass Percentage | 80% |
| Fail Percentage | 20% |

---

# Failed Test Cases

| TC ID | Reason for Failure | Severity |
|------|--------------------|----------|
| TC007 | Password is visible instead of being masked | High |
| TC008 | Remember Me functionality is not working | Medium |

---

# Defect Summary

| Bug ID | Summary | Severity | Status |
|--------|---------|----------|--------|
| BUG-001 | Password masking functionality is not working | High | Open |
| BUG-002 | Remember Me feature does not retain user session | Medium | Open |

---

# Overall Test Result

**Status:** ⚠️ **Partially Passed**

Out of **10 executed test cases**, **8 test cases passed** and **2 test cases failed**.

The Login Module is **functionally stable**, but the identified defects should be fixed and retested before the application is considered ready for production.

---

## Recommendations

- Fix the password masking issue immediately, as it is a security-related defect.
- Resolve the "Remember Me" functionality issue.
- Perform **retesting** for the failed test cases.
- Execute **regression testing** to ensure the fixes do not introduce new defects.
