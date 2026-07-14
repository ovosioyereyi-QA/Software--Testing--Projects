# Bug Report

## Bug ID
BUG-001

## Title
Customers can add closed products to the cart, proceed to checkout, and successfully complete payment.

## Module
Shopping Cart / Checkout

## Severity
High

## Priority
High

## Environment
- Web Application
- Google Chrome
- Windows 11

## Preconditions
- Product status is "Closed."
- Customer is logged in or able to shop.

## Steps to Reproduce
1. Open the application.
2. Navigate to a product marked as **Closed**.
3. Click **Add to Cart**.
4. Proceed to Checkout.
5. Complete the payment process.

## Expected Result
The system should prevent customers from adding closed products to the cart or completing checkout. An appropriate message should inform the user that the product is unavailable.

## Actual Result
Customers can add closed products to the cart, proceed through checkout, and successfully complete payment.

## Status
Open

## Reported By
Ovosi Oyereyi
