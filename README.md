# API Testing – ReqRes (Postman)

## Overview
This repository contains API testing performed on the ReqRes public API using Postman. The goal was to validate core HTTP operations and understand how the API behaves under both valid and invalid conditions.

## Scope of Testing
The following API operations were covered:

- GET – Retrieve list of users
- POST – Create a new user
- PUT – Update user details
- DELETE – Delete user

## Testing Approach
Testing was performed manually using Postman by executing API requests and verifying responses against expected outcomes.

The validation focused on:
- Status codes (200, 201, 204, 401, 404)
- Response body structure and data correctness
- Handling of negative and invalid inputs
- Basic response time checks

Each test case was executed step-by-step and supported with screenshots as evidence.

## Test Results
- Total Test Cases: 15  
- Passed: 13  
- Failed: 2  

## Key Observations
- All GET and DELETE operations worked as expected.
- POST and PUT requests were successful for valid inputs.
- The API does not enforce strict input validation:
  - Accepts missing required fields during user creation
  - Accepts incorrect data types during update

## Issues Identified
- Missing field validation is not enforced (POST)
- Data type validation is not enforced (PUT)

These behaviors are acceptable for a mock API but would be considered defects in a production system.

## Repository Contents
- Test case document  
- Test case execution with screenshots  
- Bug report  
- Test summary report  

## Tools Used
- Postman
- GitHub

## Author
Kaleemuddin Mohammed
