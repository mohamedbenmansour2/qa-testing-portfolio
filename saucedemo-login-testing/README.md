# SauceDemo – Login Feature Testing

## Objective
Manual functional testing of the Login feature on SauceDemo (https://www.saucedemo.com/), covering valid/invalid credentials, empty field validation, session persistence, and a basic security check.

## Scope
- Valid login
- Invalid login (wrong password, locked-out account)
- Empty username / password / both fields
- Case sensitivity of credentials
- SQL injection attempt (security-oriented test)
- Session persistence after page refresh
- Visual/UI check across different test accounts

## Summary of Results
- **10 test cases executed**
- **10 passed**
- **1 defect found**: the `problem_user` account displays an unrelated image (a dog) instead of correct product images on the Products page

## Files in this folder
- `SauceDemo_Login_Test_Report.pdf` – full test report, including test case table, defect report (DEF-01), and screenshot evidence
- Screenshots (`tc01.png`–`tc09.png`) – raw evidence for each executed test case

## Tools Used
Manual testing via Google Chrome
