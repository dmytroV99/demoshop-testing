# UI-Bug-002 – Credit Card discount is not displayed separately in order summary

*Type:* UI / Information  
*Severity:* Low  
*Priority:* Medium  

## Environment
- Browser: Chrome 155.0.8059.40
- OS: Windows 11 Home x64
- Page: Order confirmation

## Preconditions
- A product is added to the cart.
- Credit Card is selected as the payment method.

## Steps to Reproduce
1. Add a product to the cart.
2. Proceed to checkout.
3. Select Credit Card as the payment method.
4. Complete the order.
5. Review the order summary on the confirmation page.

## Expected Result
The order summary should clearly display all applied discounts, including the *5% Credit Card discount*, with the corresponding discount amount.

## Actual Result
The 5% Credit Card discount is included in the final total, but it is not displayed as a separate discount line in the order summary.

## Notes
The discount calculation is correct. The issue is related to transparency and presentation of the order details.
<img width="719" height="553" alt="Снимок экрана 2026-10-07 235954" src="https://github.com/user-attachments/assets/8bd21d95-b429-40a9-b7b7-0f848847e2e6" />
