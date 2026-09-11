# QA Testing Portfolio

Hi! I'm an ISTQB Certified Tester building hands-on manual testing experience through independent practice projects. This repository documents my testing work on public demo applications, following a real QA workflow: test design → execution → defect reporting → verification.

## Projects

### 1. [SauceDemo – Login Feature Testing](./saucedemo-login-testing)
10 test cases covering valid/invalid login, empty fields, session persistence, and a basic security check (SQL injection attempt). Found and documented **1 defect**: incorrect product images displayed for a specific test account.

### 2. [SauceDemo – Cart & Checkout Testing](./saucedemo-cart-checkout-testing)
12 test cases covering cart management, checkout form validation, price/tax calculation verification, and checkout cancellation. Identified **1 usability finding** (checkout accessible with an empty cart), and verified a suspected pricing defect turned out to be correct behavior — demonstrating careful validation before reporting.

### 3. [JSONPlaceholder – API Testing](./jsonplaceholder-api-testing)
10 test cases covering GET, POST, PUT, PATCH, and DELETE requests against a REST API using Postman. Verified status codes, response body accuracy, nested resource retrieval, and error handling for invalid/non-existent resources. Includes a detailed verification note on the behavioral difference between PUT (full update) and PATCH (partial update), confirmed directly from response data.

## Skills Demonstrated
- Manual functional test case design (positive, negative, edge case, boundary)
- Exploratory testing
- API testing (GET/POST/PUT/PATCH/DELETE, status codes, response validation) using Postman
- Defect reporting with severity, repro steps, and evidence
- Test result verification (avoiding false positives)
- Professional test reporting and documentation

## Tools Used
Manual browser testing (Chrome), Postman, Microsoft Word / PDF for reporting

---
*Certifications: ISTQB Foundation Level*

## Tools Used
Manual browser testing (Chrome), Microsoft Word / PDF for reporting

---
*Certifications: ISTQB Foundation Level*
