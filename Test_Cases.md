# Test Cases for Student Registration Form

| TC ID | Scenario | Steps to Execute | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-01 | Verify successful registration | Enter valid Name, Email, 10-digit Phone, Course -> Click Submit | Form submits successfully | Form submits | PASS |
| TC-02 | Verify empty form submission | Leave all fields blank -> Click Submit | Validation error shown | Error shown | PASS |
| TC-03 | Verify invalid Email format | Enter "ayush123" in Email field -> Click Submit | Should prompt for valid email | Prompted | PASS |
| TC-04 | Verify Phone Number accepts letters | Enter "ABCDEFGHIJ" in Phone field | Should not accept alphabets | Accepts alphabets | **FAIL** |
| TC-05 | Verify Phone Number length < 10 | Enter "12345" in Phone field -> Click Submit | Should show length error | Submits | **FAIL** |
| TC-06 | Verify duplicate email registration | Enter already registered email -> Submit | Should show "Email exists" | Submits | **FAIL** |
| TC-07 | Verify Course field validation | Enter "XYZ" (invalid course) | Should show "Select valid course" | Accepts "XYZ" | **FAIL** |
