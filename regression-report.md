# Regression Testing Report – OrangeHRM

## Objective
To validate newly implemented features and ensure existing functionalities continue working without issues.

---

# New Feature Testing

## Feature: Dashboard Widgets

### Test Scenario
Verify dashboard widgets load correctly after recent updates.

Expected Result:
Widgets should display without delay or UI issues.

Actual Result:
Widgets loaded correctly and displayed accurate information.

Status:
PASS

---

## Feature: Leave Management

### Test Scenario
Verify leave application functionality.

Expected Result:
User should successfully apply leave.

Actual Result:
Leave request submitted successfully.

Status:
PASS

---

## Feature: Admin User Search

### Test Scenario
Search employee records in Admin module.

Expected Result:
Correct employee details should display.

Actual Result:
Search functionality worked correctly.

Status:
PASS

---

# Regression Testing

## Regression Check 1 – Login Functionality

Expected Result:
Users should login successfully using valid credentials.

Actual Result:
Login worked correctly.

Status:
PASS

---

## Regression Check 2 – Logout Functionality

Expected Result:
User should logout and return to login page.

Actual Result:
Logout worked correctly.

Status:
PASS

---

## Regression Check 3 – Navigation Menu

Expected Result:
All sidebar menu links should open properly.

Actual Result:
Navigation menu functioning correctly.

Status:
PASS

---

# Issues Identified

## Issue 1
Minor UI alignment issue observed on smaller screen resolution.

Severity:
Low

Status:
Open

---

# Conclusion

Regression testing confirmed that core functionalities are working properly after feature updates. No critical functional regressions were identified during testing.