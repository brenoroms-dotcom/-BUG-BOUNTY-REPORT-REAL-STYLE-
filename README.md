# Bug Bounty Report - Authentication Bypass (Lab App)

## Description
The application uses hardcoded credentials and performs authentication locally without server-side validation.

## Impact
An attacker with access to the application can bypass authentication via simple guessing or reverse engineering.

This leads to full authentication bypass.

## Steps to Reproduce
1. Open the application
2. Enter username: "admin"
3. Enter password: "1234"
4. Access is granted

## Severity
High

## Root Cause
Client-side authentication using hardcoded credentials.

## Recommendation
Implement server-side authentication and use secure session/token handling.

---

## Note
Version v1.1 will be released on June 21st at 1:30 PM (Lab update).
