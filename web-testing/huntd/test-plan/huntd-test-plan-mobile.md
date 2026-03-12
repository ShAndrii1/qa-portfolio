# Huntd Mobile Application (Android) – Test Plan

## 1. Product Analysis

### 1.1 Product Overview

Huntd Mobile is an MVP application designed to provide recruiter–candidate communication on mobile devices.

The mobile app includes a limited subset of the web platform functionality, focusing primarily on:

- Identity and access management (IAM)
- Chat communication
- Profile and account management

The goal of the mobile application is to enable faster communication and allow users to manage their hiring interactions on the go.

---

### 1.2 Users’ Needs and Product Solutions

| User Need | Product Solution |
|-----------|------------------|
| Communication through web is slow | Mobile chat enables faster responses |
| Hard to track hiring conversations | Chats are grouped and easily accessible on mobile |
| Need quick account management | Profile and account settings available within the app |

---

# 2. Test Strategy

## 2.1 Scope of Testing

### In-Scope Features

The following features were tested if implemented in the mobile MVP:

- IAM (Sign in / Sign up / Logout / Session handling)
- Chats (chat list, opening chats, sending messages, chat actions)
- Profile and Account Settings (view/edit profile fields, password change, social connections if available)

### Out-of-Scope Features

- Admin functionality
- Question / feedback forms

---

## 2.2 Testing Types

The following testing types were applied:

- Functional testing
- Smoke testing
- Test case-based testing
- Ad-hoc testing
- Permission testing (Logged-out / Recruiter / Candidate)
- Usability checks
- Compatibility testing (emulator and real Android device)
- Negative testing
- Feature testing

---

## 2.3 Risks

Potential risks identified during analysis:

- Login or session management issues
- Chat functionality issues
- Privacy and permission problems (contacts visible when they should not be)
- Application stability issues (crashes, ANR, infinite loading)
- Data inconsistency between web and mobile versions

---

## 2.4 Test Logistics

Tools used during testing:

- Jira — bug tracking
- TestRail — test case management and execution tracking
- Android Studio emulator
- Physical Android device
- Log analysis for crash investigation

---

# 3. Testing Objectives

The main objectives of mobile testing were:

- Confirm that core mobile flows function correctly  
  (Sign in → Open chats → Send message)

- Ensure privacy rules are respected

- Verify application stability

- Validate role-based access restrictions

---

# 4. Test Criteria

## 4.1 Entry Criteria

Testing begins when:

- Mobile build is available and installable (APK)
- Test accounts exist (Candidate and Recruiter)
- At least one chat exists (can be created on the web if necessary)

---

## 4.2 Suspension Criteria

Testing may be suspended if:

- Application cannot launch
- Application crashes on startup
- Sign in / Sign up functionality is blocked
- Chat screen fails to load

---

## 4.3 Exit Criteria

Testing is considered complete when:

- 100% of planned test cases are executed
- No Critical defects remain open
- All critical business flows are tested

---

# 5. Resource Planning

## 5.1 Human Resources

### QA Engineer

Responsibilities:

- Test planning
- Test design
- Test execution
- Bug reporting
- Test summary preparation

---

## 5.2 Tools

- Jira
- TestRail
- Android Studio
- Android Emulator
- Physical Android device

---

# 6. Test Environment

### Emulator

- Device: Pixel 7
- OS: Android 16 (API 36)

### Physical Device

- Device: Xiaomi Redmi 9
- OS: Android 10
- MIUI: 12.0.3

---

# 7. Schedule and Estimation

| Phase | Estimated Time |
|------|------|
| Planning and Analysis | 1 hour |
| Test Design | 3 hours |
| Mobile Application Testing | 5 hours |
| Reporting and Closure | 3 hours |

---

# 8. Test Deliverables

## Before Testing

- Mobile Test Plan
- Mobile Decomposition
- Test cases

---

## During Testing

- Smoke test execution results
- Bug reports in Jira (logs/screenshots attached)
- Mobile RTM

---

## After Testing

- Test case execution results
- Bug reports
- Test report (Test Summary)
