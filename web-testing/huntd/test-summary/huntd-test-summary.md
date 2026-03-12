# Huntd – Test Summary Report

This document summarizes the results of manual testing performed for the Huntd platform (Web and Mobile).

Testing included functional verification, permission testing, exploratory testing, and execution of prepared test cases.

---

# 1. Test Execution Overview

## Web Application

| Metric | Value |
|------|------|
| Executed test cases | 347 |
| Passed | 324 |
| Failed | 21 |
| Pass rate | 93% |

---

## Mobile Application (Web Mobile Version)

| Metric | Value |
|------|------|
| Executed test cases | 114 |
| Passed | 93 |
| Failed | 8 |
| Pass rate | 82% |

---

# 2. Defect Distribution (Web)

| Priority | Count |
|------|------|
| Critical | 0 |
| High | 15 |
| Medium | 23 |
| Low | 3 |

Observations:

- No **Critical defects** were identified.
- The majority of issues belong to **Medium severity**.
- Several **High priority defects** affect user experience and platform trust.

---

# 3. Feature Coverage – Web Application

| Feature | Tests | Passed | Failed |
|------|------|------|------|
| Sign in | 14 | 14 | 0 |
| Sign up | 11 | 10 | 1 |
| Recruiter registration | 35 | 31 | 4 |
| Candidate registration | 91 | 78 | 11 |
| Engineers page | 21 | 20 | 1 |
| Companies page | 11 | 11 | 0 |
| Candidates list | 41 | 39 | 2 |
| Chats | 23 | 22 | 1 |
| Profile | 53 | 52 | 1 |
| Jobs | 25 | 25 | 0 |
| Web3 companies | 6 | 6 | 0 |
| Footer | 16 | 15 | 1 |

Coverage result:

- Total test coverage: **95%**

---

# 4. Feature Coverage – Mobile Application

| Feature | Tests | Passed | Failed |
|------|------|------|------|
| Sign in | 9 | 9 | 0 |
| Sign up | 10 | 9 | 1 |
| Recruiter registration | 6 | 4 | 2 |
| Candidate registration | 39 | 25 | 1 |
| Profile | 34 | 30 | 4 |
| Chats | 16 | 16 | 0 |

Coverage result:

- Total mobile coverage: **82%**

---

# 5. Key Observations

Testing identified several issues with potential business impact.

Examples include:

- Missing validation on multiple input fields
- Lack of mandatory email verification during registration
- Outdated company links displayed on the homepage

These issues could negatively impact platform credibility and user trust.

---

# 6. Overall Quality Assessment

Based on executed tests:

- Core platform functionality works correctly
- No critical defects block core user flows
- Several usability and validation issues require improvement

Overall system stability is acceptable, but improvements in validation and data accuracy are recommended.

---

# 7. Test Artifacts

The following artifacts were created during testing:

- Test Plan
- Requirements Traceability Matrix (RTM)
- Permission Table
- Test Cases
- Bug Reports
- Test Summary Report
