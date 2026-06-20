# Regression Suite

## Salary to Payslip Tests

1. Update employee salary and verify next payslip reflects changes.
2. Update salary twice and verify latest value is used.
3. Verify new employees receive correct payslip.
4. Verify employees without salary records cannot generate payslips.

## Related Data Propagation Tests

- Attendance changes should update salary calculations.
- Overtime changes should update payroll.
- Employee deactivation should stop payroll processing.
