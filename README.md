# API Testing – ReqRes (Postman)

## Overview
This repository contains API testing performed on the ReqRes public API using Postman. The goal was to validate core HTTP operations and observe API behavior under valid, invalid, and negative scenarios.

## Application Under Test
ReqRes Public API: https://reqres.in

## Scope of Testing
The following API operations were covered:

- GET – Retrieve list of users
- POST – Create a new user
- PUT – Update user details
- DELETE – Delete user

## Testing Approach
Testing was performed manually using Postman by sending requests and validating the returned responses.

The validation covered:
- Status codes
- Response body correctness
- Negative and invalid input handling
- Basic response time checks

Each test case was executed step by step and supported with screenshots.

## Test Results
- Total Test Cases: 15
- Passed: 13
- Failed: 2

## Key Observations
- GET and DELETE operations worked as expected.
- Valid POST and PUT requests were processed successfully.
- Input validation is limited in some cases.

## Issues Identified
- API accepts missing required fields during user creation.
- API accepts invalid data types during update.

These behaviors are acceptable for a mock API, but they would be defects in a production system.

## Repository Contents
- Test case document
- Test execution document with screenshots
- Bug report
- Test summary report

## Tools Used
- Postman
- GitHub

## Author
Kaleemuddin Mohammed
