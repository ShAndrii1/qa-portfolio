# Flow Test Summary Report

## 1. Project Overview
This project covers manual mobile testing of **Flow**, a free and open-source expense tracker focused on offline personal finance management.

The testing scope was based on the public product description provided in the official project documentation and refined through real application behavior observed during execution.

The goal of this project was to validate core finance-tracking flows, assess overall product stability and usability, and prepare a realistic set of QA artifacts based on actual testing activity.

---

## 2. Test Scope
The executed scope included validation of the following product areas:

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
- Data persistence
- Backup and export-related functionality
- Localization-related checks
- Selected URI-based automation scenarios

---

## 3. Test Environments
Testing was executed in the following environments:

- **Android real device** — Xiaomi Redmi Note 9 Pro, Android 10, MIUI 12.0.3
- **iPhone real device** — iPhone 11 Pro, iOS 26.2.1
- **Android emulator** — Pixel 7, Android 16, API 36

The primary defect discovery environment was **Android real device**.

The iPhone device was mainly used for cross-platform behavior validation and comparison of key user flows.

The Android emulator was additionally used for retesting, reproduction support, log collection, and URI-based automation checks.

---

## 4. Test Approach
The project combined:

- Functional testing
- Exploratory testing
- UI and usability-focused validation
- Localization-related checks
- Smoke testing
- Regression-oriented coverage preparation
- Feature-based execution in TestRail

Testing was performed from an end-user perspective, with focus on realistic user flows rather than isolated UI inventory validation.

In addition to predefined test cases, exploratory testing helped identify several defects related to UI behavior, localization, filtering logic, settings behavior, and data consistency.

URI-based automation scenarios were validated on Android using **PowerShell and ADB commands** to invoke documented `flow-mn` deep links.

---

## 5. Execution Results

### Overall Execution
- **Executed test cases:** 332
- **Passed:** 318
- **Failed:** 12
- **Execution rate:** 100%
- **Pass rate:** 96%
- **Fail rate:** 4%

### Defect Summary
- **Critical:** 0
- **High:** 4
- **Medium:** 13
- **Low:** 0
- **Total defects:** 17

### Feature Execution Summary
- **Initial access and first-time setup:** 45 tests, 43 passed, 1 failed
- **Main navigation and core screens:** 35 tests, 32 passed, 3 failed
- **Transaction management:** 59 tests, 58 passed, 1 failed
- **Accounts and currencies:** 39 tests, 37 passed, 1 failed
- **Statistics and spending overview:** 25 tests, 24 passed, 1 failed
- **Profile and settings:** 77 tests, 73 passed, 3 failed
- **Optional / advanced features:** 52 tests, 49 passed, 2 failed

---

## 6. Key Findings
The application demonstrated solid baseline behavior across the main finance-tracking flows, especially in transaction creation, account-based usage, and general navigation.

At the same time, testing revealed a number of defects affecting product consistency and user experience, including issues related to:

- Filtering behavior
- Settings and preference logic
- Localization consistency
- UI rendering and layout
- File attachment persistence
- Data/state consistency in selected flows

Several findings were identified not only through predefined test cases, but also during exploratory testing, which proved useful for uncovering behavior gaps beyond the planned coverage.

URI-based transaction import was successfully triggered using documented deep links, confirming support for both single-transaction and multiple-transaction import scenarios at the feature-entry level.

---

## 7. Quality Assessment
Based on the executed scope, the tested build can be considered **functionally usable for core flows**, but not fully stable in all supporting and edge-case scenarios.

The main product value is present, and the application generally supports its primary purpose as an offline expense tracker. However, the identified defects indicate that certain areas still require improvement to ensure stronger consistency, predictability, and polish.

The most attention should be given to:

- Defect-prone settings behavior
- Filtering consistency
- Selected localization gaps
- Visual/UI issues in data presentation
- Supporting features such as attachments and advanced options

---

## 8. Limitations
This project was performed as a manual portfolio testing effort and has the following limitations:

- No source code access
- No internal analytics or backend visibility
- No automated test coverage
- No deep security or performance profiling with specialized tools
- No exhaustive device compatibility matrix
- iOS testing was limited to focused validation rather than full defect discovery depth

Some advanced features were validated only to the extent possible through observable user-facing behavior and publicly documented examples.

---

## 9. Deliverables Produced
The following QA artifacts were prepared as part of this project:

- Product Requirements Draft (PRD)
- Test Plan
- Test cases in TestRail
- Test execution runs by feature
- Smoke test run
- Regression test run
- Bug reports in Jira
- Requirements Traceability Matrix (RTM)
- Test Summary Report

---

## 10. Final Conclusion
This project resulted in a realistic and well-structured set of QA artifacts supported by actual manual execution across selected Android and iOS environments.

The Flow application showed good functional coverage in its core areas, while the identified defects highlighted meaningful improvement opportunities in product quality and consistency.

Overall, the project demonstrates a practical manual QA workflow including planning, requirements analysis, test design, execution, defect reporting, traceability, and final reporting.
