# Bugs Identified – JPetStore

## JWT-4 – The "Password" field is not empty by default when open the website

### Preconditions:

 - user is logged-out

### Steps to reproduce

1. Open the JPetStore Sign in page
2. Observe the “Password“ field

### Expected result

The "Password" field is empty by default

### Actual result

The "Password" field is not empty by default

### Priority

High

---

## JWT-2 – Error message is not shown to user by trying to login with empty "Username" field on the Sign in page

### Preconditions:

 - user is logged-out

### Steps to reproduce

1. Open the JPetStore Sign in page
2. Fill in the “Password“ field with test data
3. Leave “Username“ field empty
4. Click on the [Login] button
5. Observe result

### Expected result

Error message is shown to user by trying to login with empty "Username" field

### Actual result

Error message is not shown to user by trying to login with empty "Username" field

### Priority

Medium
