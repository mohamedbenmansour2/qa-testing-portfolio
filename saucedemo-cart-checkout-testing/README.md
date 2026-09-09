# SauceDemo – Cart & Checkout Testing

## Objective
Manual functional testing of the Cart and Checkout flow on SauceDemo (https://www.saucedemo.com/), covering item management, checkout form validation, price/tax calculation, and checkout cancellation.

## Scope
- Adding/removing items from the cart (from both the cart page and products page)
- Cart persistence across navigation
- Checkout behavior with an empty cart
- Required-field validation at checkout (first name, last name, postal code)
- Full checkout completion
- Price and tax calculation verification
- Checkout cancellation

## Summary of Results
- **12 test cases executed**
- **11 passed**
- **1 finding**: checkout is accessible and proceeds normally even with an empty cart (FIND-01)
- A suspected pricing defect (tax calculation) was investigated and confirmed to be correct behavior after manual recalculation — documented as a verification note rather than a false defect report

## Files in this folder
- `SauceDemo_Cart_Checkout_Test_Report.pdf` – full test report, including test case table, finding report (FIND-01), tax verification note, and screenshot evidence
- Screenshot – tax/price breakdown used for TC21 verification

## Tools Used
Manual testing via Google Chrome
