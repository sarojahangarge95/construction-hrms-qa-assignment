# API Test Suite

## Happy Path
- Create employee with valid data.
- Update salary with valid values.

## Validation Tests
- Missing required fields.
- Negative salary.
- Zero salary.
- Extremely large salary.

## Business Rules
- Duplicate employee detection.
- Salary cannot be negative.

## Error Handling
- Verify meaningful error messages are returned.
- Verify no stack traces are exposed.
