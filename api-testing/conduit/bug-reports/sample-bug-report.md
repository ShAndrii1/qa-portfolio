# CAT-2 – Unexpected 200 OK insted of 422 by registering with "username" field length of 41 symbols

## Steps to reproduce

1. Go to the Postman
2. Send the request “Sign Up Username 41 symbols“
3. Observe status code

## Expected result

Status code is 422 - Validation error message "Username must start with a letter, have no spaces, and be 2 - 40 chatacters.“ is shown.

## Actual result

Status code is 200 ok - User is able to register by filling in the “username” field with value of 41 symbols.

## Priority

High
