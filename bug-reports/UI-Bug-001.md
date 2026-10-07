# UI-Bug-001 – Audio discount message displays incorrect discount percentage

*Type:* UI / Information  
*Severity:* Low  
*Priority:* Medium  

## Environment
- Browser: Chrome 155.0.8059.40
- OS: Windows 11 Home x64
- Page: Checkout

## Preconditions
- Product is added to the cart.
- Checkout page is opened.

## Steps to Reproduce
1. Add an audio product to the cart.
2. Proceed to checkout.
3. Enter discount code AUDIO20PC.
4. Apply the discount.
5. Check the discount confirmation message.

## Expected Result
The application should display a message indicating that a *20% audio discount* has been applied.

## Actual Result
The application displays:

> "50% Audio Discount Applied!"

The displayed discount percentage is incorrect.

## Notes
The actual discount calculation is 20%, but the confirmation message displays 50%, which may mislead the user.
<img width="714" height="545" alt="Снимок экрана 2026-10-07 215928" src="https://github.com/user-attachments/assets/d5dbf3b0-8785-4517-842c-2aba2851496b" />
