# Bug Report

**1. Bug: Phone number field accepts alphabets**
- **Severity:** High
- **Steps to Reproduce:** Enter alphabets in phone field and submit.
- **Expected:** Should throw an error for non-numeric characters.

**2. Bug: Form accepts phone numbers with less than 10 digits**
- **Severity:** Medium
- **Expected:** Should strictly validate for 10 digits.

**3. Bug: Duplicate registration possible with the same Email ID**
- **Severity:** High
- **Expected:** System should check DB and prevent duplicate email entries.

**4. Bug: Course field accepts arbitrary strings instead of standard courses**
- **Severity:** Low
- **Expected:** Should be a Dropdown instead of a text field to prevent invalid input.

**5. Bug: Missing success confirmation message after submission**
- **Severity:** Low
- **Expected:** A clear "Registration Successful" popup should appear.
