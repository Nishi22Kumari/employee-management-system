# QA-301: Overtime Entry Feature

## User Story

As a payroll administrator,
I want to record overtime hours for employees,
so that employees receive correct salary payments.

---

## Acceptance Criteria

### Functional Criteria

1. Payroll admin can enter overtime hours for an employee.
2. Overtime hours must be greater than 0.
3. Overtime hours cannot exceed 12 hours per day.
4. Employee must exist in the system before overtime can be recorded.
5. Date of overtime cannot be in the future.
6. Overtime entry should be saved successfully.
7. Saved overtime should appear in payroll calculations.

---

### Construction Payroll Edge Cases

1. Construction workers may work overtime on weekends.
2. Workers assigned to different sites should have overtime tracked separately.
3. Night shift overtime should be recorded correctly.
4. Multiple overtime entries on the same date should not create duplicate payments.
5. Workers who are on approved leave should not receive overtime for that date.
6. Overtime should not be allowed for terminated employees.
7. Overtime calculations should remain accurate for workers with daily wage contracts.

---

## Non-Functional Criteria

1. Overtime entry form should load within 3 seconds.
2. System should save overtime without data loss.
3. Unauthorized users should not access overtime records.
4. Audit logs should capture overtime modifications.

---

## Out of Scope

1. Tax calculations.
2. Bank transfers.
3. Employee attendance hardware integration.