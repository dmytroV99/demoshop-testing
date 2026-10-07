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

- [BUG-001](bug-reports/BUG-001.md) — Toys category displays products from Audio category
- [BUG-002](bug-reports/BUG-002.md) — "Name Z-A" sorting does not sort products correctly
- [BUG-003](bug-reports/BUG-003.md) — Last Name field allows more than 30 characters
- [BUG-004](bug-reports/BUG-004.md) — Phone country code is editable and is not automatically restored when changing country
- [BUG-005](bug-reports/BUG-005.md) — Senior discount is 10% instead of the required 5%
- [BUG-006](bug-reports/BUG-006.md) — Order total is calculated incorrectly on the order confirmation page
- [BUG-007](bug-reports/BUG-007.md) — FLAT20 discount applies $200 instead of $20
- [BUG-008](bug-reports/BUG-008.md) — Description field is incorrectly marked as required

## Test coverage

Detailed test coverage is available in [TEST-COVERAGE.md](TEST-COVERAGE.md).
