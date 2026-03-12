# Huntd Mobile – Requirements Traceability Matrix (RTM)

This document maps Huntd Mobile requirements to corresponding test cases created in TestRail.

---

## Authentication

| Feature | Requirement | Test Cases |
|--------|-------------|-----------|
| Sign In | Sign In page should contain **Sign Up** link redirecting to registration page | C423 |
| Sign In | Sign In page should contain **Forgot Password** link redirecting to password recovery | C421 |
| Sign Up | After entering email and password user chooses profile type (Recruiter / Candidate) | C432, C433 |
| Sign Up | Registration supports OAuth via Google | C424 |

---

## Recruiter Registration

| Feature | Requirement | Test Cases |
|--------|-------------|-----------|
| Recruiter Registration | Recruiter can fill position, company, and contact information | C1174, C1175 |

---

## Candidate Registration

| Feature | Requirement | Test Cases |
|--------|-------------|-----------|
| Role Stage | Candidate enters desired role and technical skills | C1151, C1233 |
| Expectations Stage | Candidate specifies experience, salary expectations, English level, and location | C1159, C1234, C1160, C1235, C1161, C1162, C1163, C1169 |
| Experience Stage | Candidate provides detailed work experience | C1196, C1200 |
| Profile Activation | Candidate profile requires admin activation within 24–48 hours | C1202 |

---

## Chat & Contact Privacy

| Feature | Requirement | Test Cases |
|--------|-------------|-----------|
| Contact Privacy | Recruiter cannot see candidate contacts before interaction | C1129, C1240 |
| Contact Sharing | Candidate can accept or decline recruiter request to share contacts | C1241 |
| Chat Management | Users can archive chats | C1229 |

---

## Profile Management

| Feature | Requirement | Test Cases |
|--------|-------------|-----------|
| Multi-role Accounts | Users can have both recruiter and candidate profiles | C1179 |
| Profile Editing | Users can edit profile information | C1188 |
| Role Switching | Users can switch between recruiter and candidate roles | C1180, C1181 |
| Profile Settings | Users can manage account settings | C1210, C1212, C1214 |
| Profile Activation | Users can activate or deactivate candidate profile | C1186 |
