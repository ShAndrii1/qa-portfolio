# Huntd – Requirements Traceability Matrix (RTM)

This document maps product requirements to test cases created in TestRail.

---

## Authentication

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Sign In | The Sign In page should contain a **Sign up** link redirecting to the Sign Up page                                                         | C807 |
| Sign In | The Sign In page should contain a **Forgot password** link redirecting to the password recovery page                                       | C806 |
| Sign Up | After entering email and password, the user should choose profile type (Recruiter / Candidate)                                 | C814, C817, C819 |
| Sign Up | Registration should support OAuth providers (Google, LinkedIn, GitHub)                                                                     | C813 |

---

## Recruiter Registration Flow

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Recruiter Registration | Recruiter can fill position, company and contact information                                        | C825, C826, C830, C833, C834 |
| Recruiter Registration | Recruiter defines candidate requirements (role, technologies, salary, experience, English level, location) | C837, C839, C841, C842,                                                                                                                   C843, C844, C845, C846, C847, C848, C849, C850 |
| Recruiter Registration | After registration recruiter is redirected to candidate list                                                                | C855 |

---

## Candidate Registration Flow

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Candidate Registration | Role stage includes desired position and tech stack (5–15 skills)                   C860, C862, C863, C864, C865, C866, C867, C868 |
| Candidate Registration | Expectations stage includes experience, salary expectations, English level and location         C872, C873, C880, C888, C889, C891 |
| Candidate Registration | Experience stage allows importing experience from LinkedIn                              | C899, C904, C906, C907, C909, C910, C912 |
| Candidate Registration | Bio stage includes achievements and expectations                                                                      | C924, C929 |
| Candidate Registration | Contact stage includes avatar, name, CV upload and social links                   | C932, C935, C937, C938, C940, C942, C944, C945 |
| Candidate Registration | Candidate profile requires admin activation within 24–48 hours                                                        | C946, C947 |

---

## Engineers Main Page

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| FOR ENGINEERS          | Default landing page for users                                                                                              | C949 |
| FOR ENGINEERS          | Registration form available via email and OAuth                                                                       | C952, C953 |
| FOR ENGINEERS          | Page contains links to Jobs                                                                                                 | C961 |
| FOR ENGINEERS          | Page contains links to Web3 Compan                                                                                          | C965 |
| FOR ENGINEERS          | Authorized users see mobile app banner instead of registration form                                                         | C965 |
| FOR ENGINEERS          | Page contains at least 10 user feedback entries                                                                             | C967 |

---

## Companies Main Page

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| FOR COMPANIES          | Page explains platform value for recruiters                                                                                 | C971 |
| FOR COMPANIES          | Page includes comparison with other services                                                                                | C976 |
| FOR COMPANIES          | Page motivates recruiters to explore candidate list and sign up                                                             | C975 |
| FOR COMPANIES          | CEO quotes displayed                                                                                                        | C973 |
| FOR COMPANIES          | Partner logos displayed                                                                                                     | C978 |

---

## Filters

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Filters                | Filters are visible to all users                                                                                            | C981 |
| Filters                | Only authorized users can apply filters                                                                                     | C984 |
| Filters                | Unauthorized users are prompted to sign in when interacting with filters                                              | C982, C983 |
| Filters                | Filters include role, technologies, salary, English level, location           C986, C988, C989, C990, C991, C993, C994, C995, C997 |

---

## Candidate List

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Candidate List         | Candidates displayed as cards                                                                                              | C1002 |
| Candidate List         | Card includes short description of skills and achievements                                                                 | C1006 |
| Candidate List         | "Show experience" reveals full experience details                                                                          | C1010 |
| Candidate List         | Recruiters can initiate chat from candidate card                                                                           | C1008 |
| Candidate List         | Candidate must create recruiter profile before initiating chat                                                             | C1007 |
| Candidate List         | Clicking card opens candidate profile in a new tab                                                                         | C1012 |

---

## Candidate Profile

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Candidate Profile      | Profile contains full candidate information                                                                         | C1013, C1014 |
| Candidate Profile      | Contacts remain hidden before candidate shares them                                                                        | C1015 |
| Candidate Profile      | Experience sorted chronologically                                                                                          | C1018 |

---

## Chats

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Chats                  | Recruiters can initiate chat from candidate list or profile                                                                | C1020 |
| Chats                  | Recruiter cannot see candidate contacts before interaction                                                          | C1016, C1017 |
| Chats                  | Candidate can accept or reject recruiter request                                                                    | C1030, C1031 |
| Chats                  | Recruiter can send offer or mark chat as rejected                                                                   | C1032, C1033 |
| Chats                  | Chats can be archived or marked as favourite                                                                 | C1023, C1025, C1028 |

---

## Profile

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Profile                | ProfileUsers can have recruiter and candidate roles simultaneously                                                         | C1044 |
| Profile                | Users can edit profile information                                                                                         | C1045 |
| Profile                | Users can switch between recruiter and candidate roles                                                                     | C1046 |
| Profile                | Users can connect social networks                                                                            | C1088, C1089, C1090 |
| Profile                | Users can change password                                                                      | C1091, C1092, C1093, C1094, C1095 |
| Profile                | Users can activate or deactivate candidate profile                                                           | C1051, C1052, C1053 |

---

## Jobs

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Jobs                   | Jobs can be filtered by skills                                                                                             | C1102 |
| Jobs                   | Unauthorized users see limited job details                                                                                 | C1114 |
| Jobs                   | Users can subscribe to vacancies                                                               | C1116, C1117, C1118, C1121, C1122 |
| Jobs                   | Recruiters can post jobs manually or via ATS import                                                          | C1098, C1100, C1101 |
| Jobs                   | Authorized users can apply with one click                                                                    | C1110, C1111, C1112 |

---

## Web3 Companies

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Web3 Companies         | Page displays 100 Web3 companies in groups of 10                                                                    | C1122, C1123 |
| Web3 Companies         | Each company has clickable logo and name                                                                     | C1124, C1125, C1143 |

---

## Footer

|     Feature            |                               Requirement                                    |                   Test Cases                        |
|------------------------|------------------------------------------------------------------------------|-----------------------------------------------------|
| Footer                 | Footer displays top Web3 companies preview                                                                                 | C1127 |
| Footer                 | Footer contains job vacancy sections                                                                                       | C1141 |
| Footer                 | Footer includes social network links                                                    | C1128, C1129, C1130, C1131, C1132, C1133 |
| Footer                 | Footer includes links to documentation and informational pages                                        | C1134, C1138, C1139, C1140 |
