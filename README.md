
# Restful-Booker API Testing Project

## Overview
A comprehensive API testing project for the Restful-Booker hotel booking system.
This project demonstrates manual and automated API testing using Postman and Newman.

## Test Coverage
- Authentication endpoint
- Booking CRUD operations
- Error handling and negative testing
- Data-driven testing

## Tools Used
- Postman
- Newman 6.2.2
- Google Docs for test documentation

## Endpoints Tested
| Endpoint | Method | Description |
|----------|--------|-------------|
| /auth | POST | Generate token |
| /booking | GET | Get all bookings |
| /booking/:id | GET | Get single booking |
| /booking | POST | Create booking |
| /booking/:id | PUT | Update booking |
| /booking/:id | DELETE | Delete booking |

## Test Results
- Total Test Cases: 11
- Passed: 11
- Failed: 0
- Bugs Found: 3

## Bugs Found
| Bug ID | Severity | Description |
|--------|----------|-------------|
| BUG001 | Medium | Invalid login returns 200 instead of 401 |
| BUG002 | High | Missing fields returns 500 instead of 400 |
| BUG003 | Low | Delete returns 201 instead of 204 |

## Project Documentation
[Test Plan & Bug Report](YOUR_GOOGLE_DOC_LINK)
