# API Test Scenarios – Conduit

## Authentication

1. Register a new user with valid data
2. Register a new user with invalid data
3. Attempt registration with an existing email  
4. Login with valid credentials
5. Login with invalid credentials  
6. Login with incorrect password
7. Login with incorrect email

## Users

1. Get info about user  
2. Update user info: bio, image, username, email, password  
3. Update user info: taken username, taken email
4. Update user info: without Authorization

## Articles

1. Create article with Authorization
2. Create article without Authorization
3. Update article
4. Delete article: with Auth, without Auth, of another user
5. Get article
6. Get articles

## Profile

1. Get info about profile
2. Follow user
3. Unfollow user

## Comments

1. Create comment for an article  
2. Delete own comment  
3. Attempt to delete another user's comment  
