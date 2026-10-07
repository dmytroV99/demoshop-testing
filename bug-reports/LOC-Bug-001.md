# LOC-Bug-001 – Inconsistent language in product information

*Type:* Localization / UI  
*Severity:* Low  
*Priority:* Low  

## Environment
- Browser: Chrome 155.0.8059.40
- OS: Windows 11 Home x64
- Page: Product details

## Steps to Reproduce
1. Open any product detail page.
2. Check the product information section.
3. Look at the color attribute label.

## Expected Result
The product information should use a consistent language throughout the interface.

## Actual Result
The color attribute is displayed as:

> "Barva: Black"

The word *"Barva"* is Czech, while the rest of the product information is displayed in English.

## Notes
"Barva" means "Color" in Czech. This is a localization/language consistency issue rather than a functional issue.
<img width="954" height="409" alt="Снимок экрана 2026-10-07 235626" src="https://github.com/user-attachments/assets/08dd166b-b5fd-45ad-bf19-7e468b814685" />
