# Negative Testing Report

## Objective
The objective of this testing was to identify validation, security, and error-handling issues in the HRMS application.

---

## Test Case 1: Empty Required Fields

### Feature
Login Form

### Test Input
Leave username and password fields empty.

### Expected Result
System should display validation messages.

### Actual Result
Validation message displayed.

### Status
Pass

---

## Test Case 2: Invalid Credentials

### Feature
Login Form

### Test Input
Enter invalid username and password.

### Expected Result
System should display "Invalid Credentials" message.

### Actual Result
Proper error message displayed.

### Status
Pass

---

## Test Case 3: SQL Injection Attempt

### Feature
Login Form

### Test Input
' OR 1=1 --

### Expected Result
System should reject the input.

### Actual Result
Login failed and access was denied.

### Status
Pass

---

## Test Case 4: XSS Attack Attempt

### Feature
Employee Name Field

### Test Input
<script>alert('XSS')</script>

### Expected Result
Script should not execute.

### Actual Result
Input was sanitized and script did not execute.

### Status
Pass

---

## Test Case 5: Extremely Long Input

### Feature
Employee Name Field

### Test Input
Enter a string with more than 500 characters.

### Expected Result
System should limit input length.

### Actual Result
Input validation message displayed.

### Status
Pass

---

## Test Case 6: Negative Numeric Values

### Feature
Salary Field

### Test Input
-1000

### Expected Result
Negative salary should not be accepted.

### Actual Result
Validation error displayed.

### Status
Pass

---

## Summary

The application handled most negative scenarios correctly. Validation and security mechanisms prevented invalid and malicious inputs from being processed.
