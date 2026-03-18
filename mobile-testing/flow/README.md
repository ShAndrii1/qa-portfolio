# Flow Mobile Testing Project

## Overview
This repository section contains a manual mobile testing portfolio project for **Flow**, a free and open-source expense tracker focused on offline personal finance management.

The project was built as a realistic QA case study and includes the full testing workflow: requirement analysis, test planning, test design, execution, defect reporting, traceability, and final reporting.

Testing was performed based on the public product description and actual application behavior observed during execution.

---

## Project Goal
The goal of this project was to validate the core user flows, data integrity, localization, and overall usability of the Flow mobile app across key finance-tracking features, ensuring the product behaves reliably and consistently from an end-user perspective.

---

## Scope
The main testing scope included:

- Initial access and first-time setup
- Main navigation and core screens
- Transaction management
- Accounts and currencies
- Statistics and spending overview
- Profile and settings
- Optional and advanced features

Special attention was given to:

- Core transaction flows
- Offline behavior
- Backup and export functionality
- Localization-related behavior
- Selected URI-based automation scenarios

---

## Test Environments
Testing was executed in the following environments:

- **Android real device** — Xiaomi Redmi Note 9 Pro, Android 10, MIUI 12.0.3
- **iPhone real device** — iPhone 11 Pro, iOS 26.2.1
- **Android emulator** — Pixel 7, Android 16, API 36

The primary defect discovery environment was **Android real device**.

The iPhone device was mainly used for cross-platform validation of key flows.

The Android emulator was used for retesting, reproduction support, log collection, and URI-based automation checks.

---

## Testing Types Used
- Functional testing
- Exploratory testing
- UI testing
- Usability-focused validation
- Localization checks
- Installation testing
- Smoke testing
- Regression-oriented coverage

---

## Key Results
### Test Execution
- **Total test cases:** 332
- **Passed:** 318
- **Failed:** 12
- **Execution rate:** 100%
- **Pass rate:** 96%
- **Fail rate:** 4%

### Defects
- **Total defects:** 17
- **High:** 4
- **Medium:** 13

### RTM Coverage
- **Total covered test cases linked through RTM:** 216

---

## Repository Structure

- **bug-reports/** — sample bug report and Jira backlog evidence
- **requirements-analysis/** — requirements traceability matrix (RTM)
- **test-cases-runs/** — screenshots of test cases and executed test runs from TestRail
- **test-plan/** — test plan for the project
- **test-summary/** — final test summary report and visual diagrams

---

## Included Artifacts
This project includes the following QA deliverables:

- Product Requirements Draft (PRD)
- Test Plan
- Requirements Traceability Matrix (RTM)
- Test cases in TestRail
- Test runs by feature
- Smoke test run
- Regression test run
- Full execution run
- Bug reports in Jira
- Test Summary Report

---

## Notes
- Testing was performed from a manual QA perspective without source code access.
- Advanced features were validated only to the extent possible through observable behavior and public documentation.
- URI-based transaction import was validated on Android using **PowerShell and ADB commands** to invoke documented `flow-mn` deep links.

---

## Final Summary
This project demonstrates a practical manual QA workflow for a real mobile application, including planning, analysis, execution, defect reporting, and final documentation.

The tested build showed solid baseline behavior in core finance-tracking flows, while the reported defects highlighted meaningful improvement areas in product consistency, UI behavior, localization, filtering logic, and selected supporting features.
