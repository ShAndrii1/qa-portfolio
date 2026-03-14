# Huntd Web Application – Test Plan

## 1. Product Analysis

### 1.1 Product Overview

Huntd is a job search and recruitment platform that connects engineers and recruiters through a structured candidate discovery and communication system.

The platform aims to simplify and organize the hiring process for both candidates and recruiters.

Key platform components include:

- Candidate marketplace
- Job listing system
- Application tracking
- Direct recruiter–candidate communication
- Profile management system
- Web3 companies directory

---

### 1.2 Target Audience

#### Engineers (Candidates)

- Find job opportunities
- Present skills and experience in a structured profile
- Receive offers from recruiters
- Track communication with recruiters
- Manage expectations (salary, role, location)

#### Recruiters

- Search for qualified candidates
- Filter candidates by skills and salary expectations
- Initiate communication
- Post job listings
- Manage hiring through chat

#### Web3 Companies

Companies seeking engineering talent.

---

### 1.3 Users’ Needs and Product Solutions

#### Recruiters

| Problem | Solution |
|-------|-------|
| Difficult to filter relevant candidates | Advanced filtering system |
| Lack of structured candidate comparison | Clear candidate profile structure |
| Limited communication before contact sharing | Messaging available before sharing contacts |
| Low response rate from candidates | Smart candidate matching |
| Limited chat management | Ability to archive, reject, and accept candidates |

#### Candidates

| Problem | Solution |
|-------|-------|
| Job search is chaotic | Structured job tracking and recommendations |
| Hard to stand out | Detailed skill-focused profiles |

---

# 2. Test Strategy

## 2.1 Scope of Testing

### In-Scope Features

- Main Page (Recruiter & Engineer views)
- Candidates List
- Candidate Profile
- Sign Up (Recruiter & Candidate flows)
- Sign In
- Chats
- Profile
- Footer
- Web3 Companies Page
- Jobs Page
- Filters

### Out-of-Scope Features

- Admin functionality
- Question / feedback form

---

## 2.2 Testing Types

The following testing types were applied:

- Functional testing
- Test case-based testing
- Ad-hoc testing
- Permission testing (role-based access validation)
- Usability testing
- Compatibility testing (Chrome, Edge)
- Smoke testing
- Feature testing
- Negative testing (invalid inputs, boundary values)

---

## 2.3 Risks

Potential risks identified during analysis:

- Incorrect contact visibility logic
- Broken role switching
- Chat state inconsistencies (archive / favorite / reject)
- Incorrect filtering results
- Profile activation logic failure
- OAuth (Google, LinkedIn, GitHub) failures
- LinkedIn experience import issues
- Browser compatibility issues
- Mobile layout inconsistencies
- Session expiration issues
- Token handling problems
- Data not synchronized between Web and Mobile
- Unauthorized access to candidate contacts
- Incorrect permission separation

---

## 2.4 Test Logistics

Tools used during testing:

- Jira — defect tracking and feature stories
- TestRail — test case management
- Chrome DevTools
- USB Debugger (for mobile device testing)

---

# 3. Testing Objectives

## 3.1 Protect Business Value

- Candidate contacts must not be visible before sharing
- Unauthorized users cannot access restricted features
- Inactive candidate profiles are not publicly visible
- Prevent issues that may reduce user trust

---

## 3.2 Ensure Revenue Protection

- Only recruiters can post jobs
- Unauthorized users cannot access restricted job functionality
- Recruiter permissions are properly enforced

---

## 3.3 Ensure Reliable User Acquisition

- Registration flows operate correctly
- OAuth integrations are stable
- Profile completion process works correctly

---

## 3.4 Maintain Data Integrity

- User data is stored and displayed correctly
- Profile edits are saved successfully
- Role switching does not corrupt user data

---

## 3.5 Ensure Stability of Core Flows

Critical business flows must not be blocked by high severity defects:

- Registration
- Login
- Chat communication
- Job application
- Profile editing

---

# 4. Test Criteria

## 4.1 Entry Criteria

Testing begins when:

- Web build is deployed and accessible
- Test accounts are created:

  - Unauthorized user
  - Candidate
  - Recruiter
  - Dual role account

---

## 4.2 Suspension Criteria

Testing may be suspended if:

### Critical Environment Issues

- Application is not accessible
- Application crashes on launch
- OAuth providers are unavailable
- Database instability prevents normal usage

### Blocking Defects

Critical defects blocking core flows:

- Registration
- Login
- Chat initiation
- Candidate listing
- Job application

---

## 4.3 Exit Criteria

Testing is considered complete when:

- 100% of planned test cases are executed
- No Critical defects remain open
- All critical business flows are tested

---

# 5. Resource Planning

## 5.1 Human Resources

### QA Engineer (Author)

Responsibilities:

- Test planning and strategy definition
- Risk analysis
- Test case design
- Permission table creation
- RTM preparation
- Test execution
- Bug reporting in Jira
- Smoke testing
- Test summary reporting
  
---

## 5.2 System Resources

- Jira — defect tracking
- TestRail — test case management
- Chrome DevTools
- Physical Android device
- Web browsers (Chrome, Firefox, Edge)
- Spreadsheet for Test Summary metrics

---

# 6. Test Environment

Operating System:

- Windows 10 x64 (Version 22H2)

Supported Browsers:

- Google Chrome
- Microsoft Edge

Mobile Device:

- Xiaomi Redmi 9
- Android 10
- MIUI Global 12.0.3

---

# 7. Schedule and Estimation

| Phase | Estimated Time |
|------|------|
| Planning and Analysis | 5 hours |
| Test Design | 5 hours |
| Web Application Testing | 8 hours |
| Reporting and Closure | 5 hours |

---

# 8. Test Deliverables

### Before Testing

- Test Plan
- Decomposition
- Test cases
- Test data

### During Testing

- Permission testing table
- RTM

### After Testing

- Test case execution results
- Bug reports
- Test report (Test Summary)
