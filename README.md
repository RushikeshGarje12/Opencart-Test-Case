# OpenCart E-Commerce Website - Manual Testing

Manual test cases and execution results for the **OpenCart demo store** (https://demo.opencart.com), covering the main shopping flow from registration to checkout.

## Project Summary
| Item | Details |
|---|---|
| Application | OpenCart demo e-commerce website |
| Test type | Manual: functional, positive, negative, UI |
| Total test cases | 40 |
| Result | 40 Pass, 0 Blocked, 0 Fail |

## Modules Covered
| Module | Test cases |
|---|---:|
| Login | 6 |
| Registration | 6 |
| Search | 6 |
| Product Details | 6 |
| Shopping Cart | 6 |
| Wishlist | 5 |
| Checkout | 5 |
| **Total** | **40** |

## Highlights
- Registration validation: blank fields, duplicate email, password mismatch, invalid email, Privacy Policy not accepted.
- Search: existing, non-existing, blank and upper-case keywords, description search, category filter.
- Cart and wishlist: add, update quantity, remove, quantity 0, invalid coupon, guest cart kept after login, guest vs logged-in wishlist.
- Checkout: guest checkout, registered-user checkout, empty cart redirect, blank billing details, Terms and Conditions not accepted.

## Notes
- No defects were found in the tested scenarios.
- Orders were placed on the demo site using Cash On Delivery; no real payment was made.

## Files
- `OpenCart_Test_Cases.xlsx`: test cases in a standard template (Scenario ID, Test Case ID, Pre Condition, Steps, Expected Result, Actual Result, Status, Priority) with a Summary sheet.

## Tools and Skills
Microsoft Excel, Git, GitHub. Test case design, functional testing, negative testing, UI testing, test documentation.

## Author
**Rushikesh Garje**, QA Analyst (fresher)
[LinkedIn](https://www.linkedin.com/in/rushikesh-garje-450a9239a) | 
