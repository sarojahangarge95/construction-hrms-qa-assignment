# Test Strategy

## Top 5 Critical Flows

### 1. Payroll Generation
- Highest business impact because workers depend on accurate salaries.
- Worst case: Worker receives incorrect or delayed salary.

### 2. Employee Onboarding
- New workers must be added correctly.
- Worst case: Worker is not paid or tracked.

### 3. Attendance and Overtime Tracking
- Attendance directly affects payroll.
- Worst case: Worker is underpaid or overpaid.

### 4. Salary Updates
- Salary changes should reflect in future payslips.
- Worst case: Employee receives incorrect salary.

### 5. Employee Exit Process
- Ex-employees should not continue receiving salary.
- Worst case: Organization pays inactive employees.

## What Will Be Automated

- Login functionality
- Employee onboarding
- Salary update flow
- Payroll calculation
- Regression scenarios

## What Will Be Tested Manually

- Exploratory testing
- UI usability
- Mobile responsiveness

## What Will Not Be Tested

- Cosmetic UI issues with low business impact
- Unsupported browsers
- Non-critical reports

Reason: Priority will be given to payroll-related and business-critical functionality.
