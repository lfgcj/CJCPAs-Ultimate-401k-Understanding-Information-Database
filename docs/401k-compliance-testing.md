# 401(k) Compliance Testing

## Overview

401(k) plans must undergo annual nondiscrimination testing to ensure that the plan benefits all employees fairly, not just highly compensated employees. This comprehensive guide covers all required compliance tests.

## Table of Contents

1. [Testing Overview](#testing-overview)
2. [ADP Test](#adp-test)
3. [ACP Test](#acp-test)
4. [Top-Heavy Test](#top-heavy-test)
5. [Coverage Test](#coverage-test)
6. [General Nondiscrimination Test](#general-nondiscrimination-test)
7. [415 Limits Test](#415-limits-test)
8. [Correction Methods](#correction-methods)
9. [Safe Harbor Exemptions](#safe-harbor-exemptions)

---

## Testing Overview

### Purpose of Nondiscrimination Testing

Testing ensures that:
- Plan benefits are fairly distributed
- HCEs don't disproportionately benefit
- Tax advantages are broadly shared
- Plan maintains qualified status

### Key Terms

| Term | Definition |
|------|------------|
| HCE | Highly Compensated Employee |
| NHCE | Non-Highly Compensated Employee |
| Key Employee | For top-heavy testing |
| Excludable Employee | Can be excluded from testing |

### HCE Definition

An employee is an HCE if:
- **5% owner** at any time during current or prior year, OR
- **Compensation** exceeds $155,000 (2024) in prior year

**Top-Paid Group Election:**
- Can limit HCEs to top 20% by compensation
- Must be consistent year-to-year

### Key Employee Definition

For top-heavy testing only:
- Officers with compensation > $220,000 (2024)
- 5% owners
- 1% owners with compensation > $150,000

---

## ADP Test

### What is Tested

The Actual Deferral Percentage test compares average deferral rates:
- Employee pre-tax contributions
- Employee Roth contributions
- Combined deferrals

### Calculating ADP

For each participant:
```
ADP = Employee Deferrals / Plan Compensation
```

Then calculate average ADP for HCEs and NHCEs.

### ADP Test Limits

| NHCE ADP | Maximum HCE ADP |
|----------|-----------------|
| 0% - 2% | NHCE × 2 |
| 2% - 8% | NHCE + 2% |
| Over 8% | NHCE × 1.25 |

### Example ADP Test

```
NHCE Group (90 employees):
Total compensation: $4,500,000
Total deferrals: $180,000
NHCE ADP: $180,000 / $4,500,000 = 4.00%

HCE Group (10 employees):
Total compensation: $2,000,000
Total deferrals: $140,000
HCE ADP: $140,000 / $2,000,000 = 7.00%

Test:
NHCE ADP = 4.00%
Maximum HCE ADP = 4.00% + 2.00% = 6.00%
Actual HCE ADP = 7.00%

RESULT: FAIL (7.00% > 6.00%)
Excess: 1.00%
```

### Prior Year vs Current Year Testing

| Method | Description |
|--------|-------------|
| Prior Year | Use last year's NHCE ADP |
| Current Year | Use this year's NHCE ADP |

Plans must elect method and apply consistently.

---

## ACP Test

### What is Tested

The Actual Contribution Percentage test covers:
- Employer matching contributions
- Employee after-tax contributions
- Allocated forfeitures (if applicable)

### Calculating ACP

For each participant:
```
ACP = (Matching + After-Tax) / Plan Compensation
```

### ACP Test Limits

Same structure as ADP:
| NHCE ACP | Maximum HCE ACP |
|----------|-----------------|
| 0% - 2% | NHCE × 2 |
| 2% - 8% | NHCE + 2% |
| Over 8% | NHCE × 1.25 |

### ADP/ACP Aggregate Limit Test

If plan satisfies both individually, must also satisfy:
```
(HCE ADP + HCE ACP) ≤ (NHCE ADP + NHCE ACP) × 2 + 2

AND either ADP or ACP must be within 2× NHCE
```

---

## Top-Heavy Test

### Purpose

Ensures key employees don't hold disproportionate share of plan assets.

### Top-Heavy Determination

Plan is top-heavy if:
```
Key Employee Account Balances > 60% of Total Account Balances
```

As of determination date (last day of prior plan year).

### Key Employee Accounts

Include:
- Current key employees
- Former key employees (within 5 years)
- Beneficiaries of key employees

### Top-Heavy Consequences

If plan is top-heavy:

| Requirement | Description |
|-------------|-------------|
| Minimum contribution | 3% of compensation for NHCEs |
| Accelerated vesting | 3-year cliff or 6-year graded |
| Limit on includible compensation | $345,000 (2024) |

### Top-Heavy Minimum Contribution

```
Minimum = 3% × Compensation (or HCE rate if lower)
```

**Example:**
```
Highest HCE contribution rate: 4%
Required NHCE minimum: 3%

If highest HCE contribution rate: 2%
Required NHCE minimum: 2%
```

### Safe Harbor Exemption

Plans using safe harbor contributions:
- Generally exempt from top-heavy minimum
- Safe harbor contribution satisfies requirement
- ADP/ACP safe harbor provides exemption

---

## Coverage Test

### Purpose

Ensures plan benefits sufficient percentage of employees.

### Ratio Percentage Test

Most common test:
```
Benefiting NHCEs / Eligible NHCEs
÷
Benefiting HCEs / Eligible HCEs
```

Must equal at least 70%.

### Example Coverage Test

```
Total NHCEs: 100
NHCEs benefiting: 80
NHCE percentage: 80%

Total HCEs: 20
HCEs benefiting: 20
HCE percentage: 100%

Ratio: 80% / 100% = 80%

RESULT: PASS (80% > 70%)
```

### Average Benefit Test

Alternative test if ratio percentage fails:
1. Plan must be nondiscriminatory as to contributions
2. Average benefit percentage for NHCEs must be at least 70% of HCEs

### Excludable Employees

Can exclude from testing:
- Employees not meeting age/service
- Union employees (with certain exceptions)
- Nonresident aliens with no US income
- Employees in separate line of business

---

## General Nondiscrimination Test

### IRC Section 401(a)(4)

Plans must not discriminate in favor of HCEs regarding:
- Contributions
- Benefits
- Rights and features
- Amendment and termination

### Design-Based Safe Harbors

Plans that meet safe harbor designs automatically satisfy:
- Uniform allocation formula
- Uniform points allocation
- Pro-rata contribution formula

### Testing Methods

| Test | Application |
|------|-------------|
| Design-based | Meets safe harbor design |
| General test | Mathematical testing of contributions |
| Cross-testing | Converts contributions to benefits |

### Benefits, Rights, and Features

Must be available to NHCEs on nondiscriminatory basis:
- Loans
- Hardship withdrawals
- In-service distributions
- Investment options
- Vesting schedules

---

## 415 Limits Test

### Annual Additions Limit

Maximum additions per participant:
```
Lesser of:
- $69,000 (2024), or
- 100% of compensation
```

### What Counts as Annual Additions

| Included | Not Included |
|----------|--------------|
| Employee deferrals | Catch-up contributions |
| Employer contributions | Rollovers |
| Forfeitures allocated | Loan repayments |
| After-tax contributions | Restorative payments |

### Combined Plan Limits

If employee participates in multiple plans of same employer:
- Aggregate annual additions
- Cannot exceed 415(c) limit

### Correction of 415 Excess

If exceeded:
- Return employee contributions first
- Then reduce employer contributions
- Cannot roll over excess

---

## Correction Methods

### ADP/ACP Failure Corrections

#### Corrective Distributions

Distribute excess contributions to HCEs:

| Deadline | Consequence |
|----------|-------------|
| 2.5 months | No excise tax |
| 12 months | 10% excise tax |
| After 12 months | Plan disqualification risk |

**Calculation:**
- Level excess among HCEs starting with highest ADP
- Include gap period earnings

#### QNEC Contributions

Make additional contributions to NHCEs:
- Must be fully vested
- Subject to distribution restrictions
- Increases NHCE ADP

#### QMAC Contributions

Make additional matching to NHCEs:
- Must be fully vested
- Subject to distribution restrictions
- Increases NHCE ACP

#### Recharacterization

Recharacterize HCE deferrals as after-tax:
- Rare option
- Complex rules
- Must be permitted by plan

### Top-Heavy Failure Corrections

If minimum contribution not made:
- Calculate required minimum
- Make contribution by employer deadline
- Correct under EPCRS if late

### Coverage Failure Corrections

Options:
- Expand coverage
- Make QNEC to excluded NHCEs
- Amend plan retroactively (limited)
- Correct under EPCRS

---

## Safe Harbor Exemptions

### Safe Harbor 401(k) Plans

Exempt from ADP/ACP testing:

| Type | Required Contribution |
|------|----------------------|
| Basic match | 100% on 3%, 50% on next 2% (4% max) |
| Enhanced match | Equal to or better than basic |
| Non-elective | 3% to all eligible |
| QACA match | 100% on 1%, 50% on next 5% (3.5% max) |

### Safe Harbor Requirements

1. **100% immediate vesting** (2-year cliff for QACA)
2. **Annual notice** to participants
3. **Cannot be reduced mid-year** (generally)
4. **No last-day requirement**

### Top-Heavy Exemption

Safe harbor plans are generally exempt from:
- Top-heavy minimum contribution
- If safe harbor meets or exceeds 3%

---

## Testing Timeline

### Calendar Year Plan

| Activity | Deadline |
|----------|----------|
| Plan year end | December 31 |
| ADP/ACP correction deadline (no tax) | March 15 |
| ADP/ACP correction deadline (10% tax) | December 31 next year |
| Top-heavy determination | Prior year end |
| Top-heavy minimum | Following year end |

### Testing Best Practices

1. **Project results early** - Run mid-year estimates
2. **Monitor HCE deferrals** - Adjust if necessary
3. **Track employee status** - Know who is HCE
4. **Document everything** - Keep testing records
5. **Consider safe harbor** - If testing problematic

---

## Common Testing Issues

### Data Issues

| Issue | Solution |
|-------|----------|
| Incorrect compensation | Use plan definition consistently |
| Wrong HCE status | Apply prior year lookback |
| Missing participants | Include all eligible |
| Incorrect hours | Verify service tracking |

### Calculation Issues

| Issue | Solution |
|-------|----------|
| Wrong testing method | Elect and document |
| Incorrect aggregation | Know controlled group rules |
| Wrong year | Use correct plan year |
| Missing contributions | Include all sources |

---

## Related Resources

- [401(k) Plan Types](401k-plan-types.md)
- [Contribution Rules](401k-contribution-rules.md)
- [Correction Programs](401k-correction-programs.md)
- [Safe Harbor Plans](401k-plan-types.md#safe-harbor-401k-plan)

---

*Last Updated: 2024*
