# Flow Test Plan

## 1. Project Analysis

### 1.1 Project Overview
Flow is a free and open-source mobile expense tracker designed for offline personal finance management. Based on the public product description provided by the developer, the application supports multiple accounts and currencies, categories, tags, file attachments, optional geo tagging, spending statistics, backups, data export, localization, and URI-based automation.

This portfolio project is based on real manual testing of the Flow mobile application across selected Android and iOS environments.

The initial testing scope and module breakdown were derived from the feature description provided by the developer in the official project README and were further refined through actual application behavior observed during manual testing.

### 1.2 Target Audience
The target audience of Flow includes users who want to track personal finances in a simple, privacy-focused, and offline-first way. The product appears suitable for users who:

- want to record expenses and income manually
- use multiple financial accounts
- need support for different currencies
- prefer full control over personal finance data
- want backup and export options
- value a lightweight and privacy-friendly mobile solution

### 1.3 User Needs and Product Solution
The main user need addressed by Flow is the ability to track and review personal financial activity without relying on complex systems or constant internet access.

The product aims to solve this need by providing:

- offline expense tracking
- account-based finance organization
- transaction categorization with tags
- financial overview through statistics
- backup and export options for data control
- optional supporting features such as attachments and geo tagging

---

## 2. Test Strategy

### 2.1 Scope of Testing
The testing scope is based on publicly available product information provided by the developer, primarily the official GitHub README, and was refined through real manual testing.

#### In Scope
- Manual functional testing of the mobile application
- Validation of core expense-tracking workflows
- Testing on Android real device, iPhone real device, and Android emulator
- Cross-platform comparison of key flows and behavior
- Validation of offline functionality
- Validation of account, transaction, category, and tag flows
- Validation of statistics, backup, and export behavior
- Basic validation of supporting features where applicable
- Defect reporting and result documentation

#### Core Modules
The following core modules were prioritized for testing:

- Application installation and launch
- First run / initial app access
- Account management
- Transaction management
- Categories and tags
- Statistics and spending overview
- Backup and restore
- Export functionality
- Offline behavior

#### Supporting Modules
The following supporting modules were planned for focused or selective testing:

- Attachments and receipt-related input
- Geo tagging / location-related behavior
- Permission handling
- Currency handling
- Localization / language support
- URI-based automation

#### Out of Scope
- Source code review
- Unit and integration testing at code level
- Automated testing
- Separate backend/API testing stream
- Deep performance profiling with specialized tools
- Deep security testing
- Full accessibility audit
- Exhaustive device compatibility testing
- Desktop platform testing
- Validation of external services beyond observable in-app behavior

### 2.2 Testing Types
The following testing types were planned for this project:

- Functional testing
- Exploratory testing
- UI testing
- Usability-focused testing
- Compatibility testing across selected environments
- Localization and regional format checks
- Installation testing
- Smoke testing
- Regression testing of affected areas after defect fixes or retesting

### 2.3 Risk Analysis
The following risks were considered relevant to this testing project:

- Incorrect transaction creation, editing, or saving may affect core product value
- Incorrect calculations or statistics may reduce user trust in the application
- Backup, restore, or export issues may lead to data loss or data inconsistency
- Offline behavior may not fully match the product promise described by the developer
- Platform-specific differences may cause inconsistent user experience between Android and iOS

### 2.4 Test Logistics
- **Jira** — defect tracking and feature stories
- **TestRail** — test case management
- **Real Android device** — Xiaomi Redmi Note 9 Pro
- **Real iOS device** — iPhone 11 Pro
- **Android Emulator** — Android Studio

---

## 3. Testing Objectives

The main objectives of this testing project were:

- To validate the core functionality of the Flow mobile application through real manual testing
- To verify whether the main finance-tracking flows work correctly across selected Android and iOS environments
- To assess whether the application supports its main product promises, especially offline use, transaction management, backup, and export
- To identify functional, usability, and platform-specific defects
- To prepare a realistic and professional set of QA artifacts based on actual testing activity
- To provide an overall quality assessment of the tested product version

---

## 4. Test Criteria

### 4.1 Entry Criteria
- The application build is available and installable
- Selected test environments are prepared
- The initial scope foundation is documented
- Main modules for testing are identified
- Basic requirement sources are available
- The tester has access to the necessary devices and environments

### 4.2 Exit Criteria
- Planned core module coverage is executed
- Major supporting module checks are completed as planned
- Identified defects are documented
- Test results are summarized
- Final QA artifacts for the project are prepared
- Major blockers, limitations, and assumptions are clearly recorded

### 4.3 Suspension Criteria
- The application cannot be installed or launched
- A blocker prevents execution of core user flows
- Test data becomes unusable due to critical corruption or data loss
- The build becomes unstable enough to prevent meaningful testing

---

## 5. Resource Planning

### 5.1 Main Resource
**Tester / Author:** one QA tester responsible for test analysis, test design, execution, defect reporting, traceability, and final reporting.

### 5.2 Main Responsibilities
- Analyze public product information
- Define testing scope
- Prepare QA artifacts
- Execute manual tests
- Document defects
- Summarize results and quality findings

---

## 6. Environment Planning

### Environment 1
- **Platform:** Android
- **Device:** Xiaomi Redmi Note 9 Pro
- **OS:** Android 10
- **UI Version:** MIUI 12.0.3
- **Type:** Real device

### Environment 2
- **Platform:** iOS
- **Device:** iPhone 11 Pro
- **OS:** iOS 26.2.1
- **Type:** Real device

### Environment 3
- **Platform:** Android
- **Device:** Pixel 7
- **OS:** Android 16, API 36
- **Type:** Emulator

---

## 7. Schedule and Estimation

- **Planning and Analysis:** 7 m/h
- **Requirements Analysis:** 5 m/h
- **Test Design:** 12 m/h
- **Test Execution:** 16 m/h
- **Defect Reporting:** 6 m/h
- **Reporting:** 4 m/h

---

## 8. Test Deliverables

### 8.1 Before Testing / Inputs
- Product Requirements Draft (PRD)
- Test Plan
- Module decomposition / test structure in TestRail
- Requirements list
- Test scenarios
- Test cases in TestRail
- Initial RTM draft

### 8.2 During Testing / Test Deliverables
- Test execution results in TestRail
- Bug reports created in Jira
- Updated RTM

### 8.3 After Testing / Outputs
- Test report
- Bug reports
