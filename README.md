# DemoShop – Testing

## Overview

Functional testing of the DemoShop e-commerce application based on the provided functional requirements.

## Testing scope

The following functionality was tested:

- Main page and product categories
- Product cards and product details
- Shopping cart
- Checkout and order form
- Input field validation
- Discounts and discount combinations
- Delivery methods
- Payment methods
- Order summary and confirmation
- Product administration
- Product creation, editing and deletion
- Excel export
- Application reset

## Test environment

- OS: Windows 11 Home x64
- Browser: Chrome Version 155.0.8059.40
- Testing type: Functional testing

## Defect reports

All identified defects are documented in the bug-reports directory.


| ID | Type | Title | Severity | Priority |
|---|---|---|---|---|
| BUG-001 | Functional | Toys category displays products from Audio category | Medium | High |
| BUG-002 | Functional | "Name Z-A" sorting does not sort products correctly | Medium | Medium |
| BUG-003 | Functional | Last Name field allows more than 30 characters | Medium | Medium |
| BUG-004 | Functional | Phone country code is editable and is not automatically restored when changing country | Medium | High |
| BUG-005 | Functional | Senior discount is 10% instead of the required 5% | Medium | High |
| BUG-006 | Functional | FLAT20 discount applies $200 instead of $20 | High | High |
| BUG-007 | Functional | Description field is incorrectly marked as required | Medium | Medium |

## Test coverage

Detailed test coverage is available in [TEST-COVERAGE.md](TEST-COVERAGE.md).
