# Regression Test Cases – OrangeHRM

## Module: Login

### TC_01 – Valid Login
Steps:
1. Open OrangeHRM login page
2. Enter valid username and password
3. Click Login

Expected Result:
User should login successfully and dashboard should display.

---

### TC_02 – Invalid Login
Steps:
1. Enter invalid credentials
2. Click Login

Expected Result:
Error message should display.

---

### TC_03 – Empty Login Fields
Steps:
1. Leave username and password blank
2. Click Login

Expected Result:
Required field validation message should display.

---

## Module: Dashboard

### TC_04 – Dashboard Visibility
Steps:
1. Login successfully
2. Navigate to Dashboard

Expected Result:
Dashboard widgets and menu should load properly.

---

## Module: Admin

### TC_05 – Search User
Steps:
1. Open Admin tab
2. Search existing employee

Expected Result:
Employee details should display correctly.

---

## Module: Leave

### TC_06 – Apply Leave
Steps:
1. Open Leave module
2. Apply leave with valid details

Expected Result:
Leave request should submit successfully.

---

## Module: Recruitment

### TC_07 – Add Candidate
Steps:
1. Open Recruitment module
2. Add candidate details
3. Save information

Expected Result:
Candidate should be added successfully.

---

## Module: Logout

### TC_08 – Logout Functionality
Steps:
1. Click profile icon
2. Click Logout

Expected Result:
User should logout and redirect to login page.
