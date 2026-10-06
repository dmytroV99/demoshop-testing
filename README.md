# DemoShop – QA Testing

## Overview

Functional testing of the DemoShop e-commerce application based on the provided functional requirements.

## Application under test

DemoShop: https://eshop-demo-766125429055.europe-central2.run.app/

Admin panel: https://eshop-demo-766125429055.europe-central2.run.app/admin

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

- OS: Windows
- Browser: Opera
- Testing type: Functional testing
- Test data: Dummy data

## Defect reports

All identified defects are documented in the bug-reports directory.

| ID | Summary | Severity | Priority |
|---|---|---|---|
| BUG-001 | Toys category displays products from Audio category | Medium | High |
| BUG-002 | "Name Z-A" sorting does not sort products correctly | Medium | Medium |
| BUG-003 | Product color does not match the displayed product image | Low | Medium |

## Test coverage

Detailed test coverage is available in [TEST-COVERAGE.md](TEST-COVERAGE.md).
