# JSONPlaceholder – API Testing

## Objective
Manual API testing of the JSONPlaceholder REST API (https://jsonplaceholder.typicode.com) using Postman, covering the core HTTP methods, status code validation, response body accuracy, nested resource retrieval, and error handling.

## Scope
- GET requests (list resources, single resource, nested resources)
- POST (create a resource)
- PUT (full update of a resource)
- PATCH (partial update of a resource)
- DELETE (remove a resource)
- Error handling for non-existent and invalid resource IDs (404)

## Summary of Results
- **10 test cases executed**
- **10 passed**
- Includes a verification note comparing PUT vs. PATCH behavior, confirmed directly from response data rather than assumed from status codes alone

## Files in this folder
- `JSONPlaceholder_API_Test_Report.pdf` – full test report, including test case table, PUT vs PATCH verification note, and screenshot evidence
- Screenshots (`tc01.png`–`tc10.png`) – raw evidence for each executed test case

## Tools Used
Postman
