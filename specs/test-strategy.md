# Test Strategy - Employee Management System

## Purpose

The purpose of this HRMS is to help administrators manage employees, leave requests, profiles, and payroll-related activities accurately.

---

## Critical User Flows

### 1. User Login
- User enters valid credentials
- User reaches dashboard
- Invalid credentials show error

### 2. Employee Profile Management
- View profile
- Edit profile
- Upload profile image

### 3. Leave Request Flow
- Employee submits leave
- Admin reviews request
- Admin approves/rejects

### 4. Employee Management
- Admin views employee list
- Admin edits employee details

### 5. Payroll / Overtime Entry
- Overtime hours entered correctly
- Salary calculations remain accurate

---

## Risk Areas

### High Risk
- Authentication failures
- Incorrect payroll calculations
- Leave approval errors

### Medium Risk
- Employee profile updates
- File uploads

### Low Risk
- UI styling issues
- Dashboard visual charts

---

## Test Types

### Functional Testing
Verify all business flows work correctly.

### Negative Testing
Verify invalid inputs are rejected.

### Regression Testing
Ensure fixes do not break existing functionality.

### API Testing
Verify backend endpoints return correct responses.

### Security Testing
Verify unauthorized users cannot access restricted data.

---

## What I Will Not Test

- Third-party email systems
- Browser compatibility older than Chrome
- Infrastructure scaling

---

## Success Criteria

1. Critical flows pass.
2. No high severity defects remain.
3. Regression suite passes before release.
4. Login, leave, and employee management remain stable.